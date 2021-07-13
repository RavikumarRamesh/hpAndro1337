# [@hpAndro1337](https://twitter.com/hpandro1337) Android Application Security 

## CTF Style Android Security Challenges [ctf.hpandro.raviramesh.info](http://ctf.hpandro.raviramesh.info)
![hpAndro](Android%20AppSec%20(Kotlin)/img/logo.png "http://ctf.hpandro.raviramesh.info") 

**[Android AppSec (Kotlin)](https://play.google.com/store/apps/details?id=com.hpandro.androidsecurity)** app will help you to practice for Android Security points. We do it for the right reasons - to help developers make their apps more secure. The best way to verify that your app follows secure mobile development best practices is to perform security assessments of the app, which can include automated mobile app security testing, fuzzing, manual penetration testing, and more. This application represents some of the knowledge we share with the infosec community. We are trying to build a vulnerable application based on ***[OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg)***.

We ([@hpAndro](https://twitter.com/hpandro) and [@_RaviRamesh](https://twitter.com/_RaviRamesh)) spend a lot of time attacking android app hacking, breaking encryption, finding bussiness logic flaws, penetration testing, and looking for sensitive data stored insecurely.

We try harder to build vulnerable application for you..

In this application we are covering below points:

1. **HTTP Traffic**
   1. [HTTP Traffic](https://play.google.com/store/apps/details?id=hpandro.java.infosec.http)
   2. [HTTPS Traffic](https://play.google.com/store/apps/details?id=hpandro.java.infosec.https)
2. **Public Key Pinning**
   1. Certificate Pinning Bypass (network_security_config.xml) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   2. Certificate Pinning Bypass (okhttp) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   3. Certificate Pinning Bypass (Cert check) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   4. Certificate Pinning Bypass (Cert Hash match) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
3. **Non-HTTP Traffic**
   1. [TCP Traffic](https://play.google.com/store/apps/details?id=hpandro.java.infosec.tcp_traffic)
   2. [UDP Traffic](https://play.google.com/store/apps/details?id=hpandro.java.infosec.udp_traffic)
4. **WebSocket Traffic**
   1. [Web Socket (WS)](https://play.google.com/store/apps/details?id=hpandro.java.infosec.ws)
   2. [Web Socket Secure (WSS)](https://play.google.com/store/apps/details?id=hpandro.java.infosec.wss)
5. **Root Detection**
   1. [Root Management Apps](https://play.google.com/store/apps/details?id=hpandro.java.infosec.rootmanager)
   2. Potentially Dangerous Apps
   3. [Root Cloaking Apps](https://play.google.com/store/apps/details?id=hpandro.java.infosec.rootclock)
   4. [Test Keys](https://play.google.com/store/apps/details?id=hpandro.java.infosec.testkeys)
   5. Dangerous Props
   6. [BusyBox Binary](https://play.google.com/store/apps/details?id=hpandro.java.infosec.busybox)
   7. Su Binary
   8. [Su Exists](https://play.google.com/store/apps/details?id=hpandro.java.infosec.su)
   9. RW System
   10. SafetyNet [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   11. Using running processes [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
6. **Emulator detection**
   1. Virtual Phone Number
   2. Device IDs
   3. Hardware Specifications
   4. QEmu Detection
   5. File Based Checking
   6. IP Based Checking
   7. Package Name
   8. Debug Flag
   9. Network Operator Name
7. **Anti-Debugging detection**
   1. PMS Hook Detection [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   2. Checking TracerPid [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   3. Using Fork and ptrace [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   4. Frida Detection [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   5. SafetyNet [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   6. Debuggable Flag [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   7. isDebugger Connected [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   8. Timer Checks [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   9. JDWP-Related Data Structures [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
8. **Insecure Data Storage**
   1. [SQLite Databases (Unencrypted)](https://play.google.com/store/apps/details?id=hpandro.java.infosec.sqlitedb)
   2. SQLite Databases (Encrypted) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   3. Realm Databases (Unencrypted) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   4. Realm Databases (Encrypted) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   5. Firebase Real-time Databases [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   6. [Shared Preferences](https://play.google.com/store/apps/details?id=hpandro.java.infosec.sharedpref)
   7. [Internal Storage](https://play.google.com/store/apps/details?id=hpandro.java.infosec.internal_storage)
   8. [External Storage](https://play.google.com/store/apps/details?id=hpandro.java.infosec.external_storage)
   9. KeyStore [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   10. KeyChain [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   11. Keyboard Cache [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   12. User Interface [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   13. App Backup [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   14. Screenshots [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   15. Memory [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   16. User Dictionary Cache [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   17. Paste Board [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
   18. [Activity data](https://play.google.com/store/apps/details?id=hpandro.java.infosec.activity_data)
9. **Logs**
   1. [Informational Logs](https://play.google.com/store/apps/details?id=hpandro.java.infosec.infolog)
   2. [Error Logs](https://play.google.com/store/apps/details?id=hpandro.java.infosec.infolog)
   3. [Warnings Logs](https://play.google.com/store/apps/details?id=hpandro.java.infosec.infolog)
   4. [Debug Logs](https://play.google.com/store/apps/details?id=hpandro.java.infosec.infolog)
   5. [Verbose Logs](https://play.google.com/store/apps/details?id=hpandro.java.infosec.infolog)
   6. [WTF Logs](https://play.google.com/store/apps/details?id=hpandro.java.infosec.infolog)
10. **Content Providers**
    1. [SQL Injection](https://play.google.com/store/apps/details?id=hpandro.java.infosec.sqlinjection)
    2. File System Expose [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
11. **Encryption**
    1. Message Authentication Codes [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    2. Message Digest [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    3. Signatures [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    4. Custom Implementations [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    5. [Caesar Cipher](https://play.google.com/store/apps/details?id=hpandro.java.infosec.caesar)
    6. Weak Key Generation [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    7. Weak Random Number [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    8. Weaker Padding [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
12. **Symmetric Encryption**
    1. [DES](https://play.google.com/store/apps/details?id=hpandro.java.infosec.des)
    2. [3DES](https://play.google.com/store/apps/details?id=hpandro.java.infosec.triple_des)
    3. [RC4](https://play.google.com/store/apps/details?id=hpandro.java.infosec.rc4)
    4. [Blowfish](https://play.google.com/store/apps/details?id=hpandro.java.infosec.blowfish)
    5. [AES](https://play.google.com/store/apps/details?id=hpandro.java.infosec.aes)
    6. [Predictable Initialization Vector](https://play.google.com/store/apps/details?id=hpandro.java.infosec.predictable)
13. **Asymmetric Encryption**
    1. [RSA](https://play.google.com/store/apps/details?id=hpandro.java.infosec.rsa)
14. **Hashing**
    1. [MD4](https://play.google.com/store/apps/details?id=hpandro.java.infosec.md4)
    2. [MD5](https://play.google.com/store/apps/details?id=hpandro.java.infosec.md5)
    3. [SHA1](https://play.google.com/store/apps/details?id=hpandro.java.infosec.sha1)
15. **Authentication**
    1. Biometric [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    2. Confirm Credentials [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    3. [2FA - OTP Leakage](https://play.google.com/store/apps/details?id=hpandro.java.infosec.FA2)
    4. 2FA - Response Manipulation
    5. 2FA - Status Code Manipulation
    6. 2FA - OTP Brute-Force
    7. 2FA - OTP Brute-Force 2
    8. 2FA - Integrity Validation
    9. Application lock [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
16. **Binary Protection**
    1. Library (NDK) [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    2. Packers [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    3. Obfuscator [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
17. **Device ID**
    1. [SSAID/ANDROID_ID](https://play.google.com/store/apps/details?id=hpandro.java.infosec.android_id)
    2. [Device Wi-Fi MAC](https://play.google.com/store/apps/details?id=hpandro.java.infosec.device_mac)
    3. [GPS Location](https://play.google.com/store/apps/details?id=hpandro.java.infosec.gps)
    4. [IMEI/ESN](https://play.google.com/store/apps/details?id=hpandro.java.infosec.imei)
    5. MEID
    6. IMSI
18. **Web Application**
    1. HTML5 Controls
    2. Bruteforce
    3. Login Bypass - Cookies Manipulation
    4. Encoding - Hashing
    5. JavaScript - Info leak
    6. Server Fingerprint
    7. Client Side Validation Bypass
    8. User Password Enumeration
    9. OTP Bruteforce
    10. JWT Misconfiguration
    11. Guessable Session ID
    12. REST API HTTP Methods
    13. SSRF
    14. XXE
    15. Unrestricted File Upload
    16. LFI [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    17. RFI
    18. Deserialization
    19. XPATH Injection
    20. Metafiles - Info Leakage
    21. RIA Cross Domain Policy
    22. Default Credentials
    23. OS Command Injection
    24. S3 bucket misconfiguration
    25. Path Traversal
    26. Captcha Bypass
    27. IP whitelisting Bypass
    28. SSTI
    29. Review comment and Metadata
    30. Code Injection
    31. Old Backup Files
    32. Insecure Direct Object Reference
    33. JSON to XXE (Blind)
19. **Miscellaneous**
    1. Deeplink [Coming Soon...](http://hpandro.raviramesh.info/soon.php)
    2. [QR Code](https://play.google.com/store/apps/details?id=hpandro.java.infosec.qr)
    3. [Backdoor1](https://play.google.com/store/apps/details?id=hpandro.java.infosec.backdooor1)
    4. [Backdoor2](https://play.google.com/store/apps/details?id=hpandro.java.infosec.backdooor2)
    5. [Backdoor3](https://play.google.com/store/apps/details?id=hpandro.java.infosec.backdooor3)
    6. [Backdoor4](https://play.google.com/store/apps/details?id=hpandro.java.infosec.backdooor4)
    7. [Backdoor5](https://play.google.com/store/apps/details?id=hpandro.java.infosec.backdooor0)

It will be great if you can support and share your thoughts with us to improve this application.
