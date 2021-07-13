# [@hpAndro1337](https://twitter.com/hpandro1337) Android Application Security 

## CTF Style Android Security Challenges [ctf.hpandro.raviramesh.info](http://ctf.hpandro.raviramesh.info)

**[Android AppSec (Kotlin)](https://play.google.com/store/apps/details?id=com.hpandro.androidsecurity)** app will help you to practice for Android Security points. We do it for the right reasons - to help developers make their apps more secure. The best way to verify that your app follows secure mobile development best practices is to perform security assessments of the app, which can include automated mobile app security testing, fuzzing, manual penetration testing, and more. This application represents some of the knowledge we share with the infosec community. We are trying to build a vulnerable application based on ***[OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg)***.

In this application we are covering below points:

1. **HTTP Traffic**
   1. HTTP Traffic
   2. HTTPS Traffic
2. **Public Key Pinning**
   1. Certificate Pinning Bypass (network_security_config.xml)
   2. Certificate Pinning Bypass (okhttp)
   3. Certificate Pinning Bypass (Cert check)
   4. Certificate Pinning Bypass (Cert Hash match)
3. **Non-HTTP Traffic**
   1. TCP Traffic
   2. UDP Traffic
4. **WebSocket Traffic**
   1. Web Socket (WS)
   2. Web Socket Secure (WSS)
5. **Root Detection**
   1. Root Management Apps
   2. Potentially Dangerous Apps
   3. Root Cloaking Apps
   4. Test Keys
   5. Dangerous Props
   6. BusyBox Binary
   7. Su Binary
   8. Su Exists
   9. RW System
   10. SafetyNet
   11. Using running processes
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
   1. PMS Hook Detection
   2. Checking TracerPid
   3. Using Fork and ptrace
   4. Frida Detection
   5. SafetyNet
   6. Debuggable Flag
   7. isDebugger Connected
   8. Timer Checks
   9. JDWP-Related Data Structures
8. **Insecure Data Storage**
   1. SQLite Databases (Unencrypted)
   2. SQLite Databases (Encrypted)
   3. Realm Databases (Unencrypted)
   4. Realm Databases (Encrypted)
   5. Firebase Real-time Databases
   6. Shared Preferences
   7. Internal Storage
   8. External Storage
   9. KeyStore
   10. KeyChain
   11. Keyboard Cache
   12. User Interface
   13. App Backup
   14. Screenshots
   15. Memory
   16. User Dictionary Cache
   17. Paste Board
   18. Activity data
9. **Logs**
   1. Informational Logs
   2. Error Logs
   3. Warnings Logs
   4. Debug Logs
   5. Verbose Logs
   6. WTF Logs
10. **Content Providers**
    1. SQL Injection
    2. File System Expose
11. **Encryption**
    1. Message Authentication Codes
    2. Message Digest
    3. Signatures
    4. Custom Implementations
    5. Caesar Cipher
    6. Weak Key Generation
    7. Weak Random Number
    8. Weaker Padding
12. **Symmetric Encryption**
    1. DES
    2. 3DES
    3. RC4
    4. Blowfish
    5. AES
    6. Predictable Initialization Vector
13. **Asymmetric Encryption**
    1. RSA
14. **Hashing**
    1. MD4
    2. MD5
    3. SHA1
15. **Authentication**
    1. Biometric
    2. Confirm Credentials
    3. 2FA - OTP Leakage
    4. 2FA - Response Manipulation
    5. 2FA - Status Code Manipulation
    6. 2FA - OTP Brute-Force
    7. 2FA - OTP Brute-Force 2
    8. 2FA - Integrity Validation
    9. Application lock
16. **Binary Protection**
    1. Library (NDK)
    2. Packers
    3. Obfuscator
17. **Device ID**
    1. SSAID/ANDROID_ID
    2. Device Wi-Fi MAC
    3. GPS Location
    4. IMEI/ESN
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
    16. LFI
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
    1. Deeplink
    2. QR Code
    3. Backdoor1
    4. Backdoor2
    5. Backdoor3
    6. Backdoor4
    7. Backdoor5

It will be great if you can support and share your thoughts with us to improve this application.
