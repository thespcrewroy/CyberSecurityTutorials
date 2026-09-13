# Cyber Security Tutorials

## Open Source Intelligence (OSINT)
- **Bar Codes**: machine-readable visual patterns used to store data
    - **JAB (Just Another Barcode) Code**: a compact barcode variant for short payloads
    - **QR codes**: two-dimensional codes encoding URLs and small data blocks
- **Data Brokers**: firms that collect and sell personal and business data
- **Geolocation**: techniques to determine physical locations from data
    - **EXIF (Exchangeable Image File Format)**: metadata in images that can reveal location
    - **Universal Transverse Mercator (UTM)**: a grid-based geographic coordinate system
    - **World Geodetic System (WSG84)**: global datum used for GPS coordinates
- **OSINT Framework**: a catalog of tools and methods for open-source research
- **OWASP Top 10**: a prioritized list of common web application security risks
- **Piracy**: unauthorized copying and distribution of copyrighted content
    - **Pirate Bay**: a popular torrent index site for sharing files
 - **Private Investigators**: professionals who gather information discreetly
- **Querying**: crafting searches to efficiently find relevant information
- **Search Engines**: tools that index and retrieve web-hosted information
    - **Google Reverse Image Search**: find similar images and their sources
    - **Yandex**: Russian search engine with image and web search features

## Cryptography
- **Alice & Bob**: placeholder names used in cryptography examples
- **MFA (Multi-Factor Authentication)**: authentication using multiple credential types
    - **FIDO/FIDO2 (Fast Identity Online)**: standards for passwordless authentication
        - **Biometrics**: physiological traits used for user authentication
        - **CTAP (Client to Authentication Protocol)**: protocol for external authenticators
        - **Passkeys**: phishing-resistant credentials replacing passwords
        - **WebAuthn (Web Authentication)**: browser API for strong authentication
            - **Relying Party (RP) ID**: identifier for the service using WebAuthn
    - **Knowledge-Based Authentication (KBA):** challenge questions that ask for personal information (ex. mother's maiden name)
    - **OAuth (Open Authorization)**: protocol for delegated access to resources
    - **PGP (Pretty Good Privacy)**: email encryption and signing standard
        - **GPA (GNU Privacy Assistant)**: GUI tool for managing PGP keys
        - **OpenPGP**: interoperable standard for PGP-compatible encryption
    - **PIV (Personal Identity Verification)**: smartcard standard for identity tokens
    - **TOTP (Time Based One-Time Password)**: time-limited codes for authentication
    - **U2F (Universal 2nd Factor)**: hardware-backed second-factor authentication standard
    - **ZTA (Zero Trust Architecture)**: security model that verifies every access
    - **Zero Knowledge Proof**: prove knowledge without revealing the secret
- **Checksum**: a small value used to detect data corruption
- **Ciphers**: algorithms for encrypting or transforming data
    - **Asymmetric Encryption**: public/private key cryptography for secure exchange
        - **Certificate Based Encryption**: uses certificates to bind identities to keys
            - **SSL/TLS Certificate**: credential used to secure web connections
        - **Diffie-Hellman**: key exchange method for establishing shared secrets
        - **(ECC) Elliptical Curve Cryptography**: efficient public-key crypto using curves
            - **Trapdoor Function**: one-way function easy to compute, hard to invert
        - **RSA (Rivest-Shamir-Adleman)**: widely used public-key encryption algorithm
        - **Charcode Cipher**: character-based substitution or encoding methods
        - **DTMF (Dual Tone Multi-Frequency)**: tones used for telephony signaling
        - **Historical Ciphers**: classical encryption methods from history
            - **Caesar (ROT) Cipher**: simple letter-shift substitution cipher
            - **Jefferson Cipher**: wheel-based transposition cipher
            - **Scytale**: ancient transposition using a wrapped strip
            - **Rail-Fence Cipher**: zigzag transposition of plaintext
            - **Transposition Cipher**: rearranges characters without substitution
            - **Vigenere Cipher**: polyalphabetic substitution using a keyword
        - **Morse**: encoding text as sequences of dots and dashes
        - **Sign Language**: visual-gestural communication system for humans
        - **Symmetric Encryption**: single-key encryption for confidentiality
            - **AES (Advanced Encryption Standard)**: modern symmetric cipher standard
            - **DES (Data Encryption Standard)**: older symmetric cipher, now deprecated
- **Cryptanalysis**: techniques to break or analyze cryptographic systems
    - **Side Channel Attack**: extract secrets from physical leakages
    - **Bullrun Decryption Program**: speculated agency effort to weaken crypto
- **FDE (Full Disk Encryption)**: encrypting an entire storage device at rest

## Password Cracking
- **Hashcat**
- **JohnTheRipper**
- **PDF2John:**

## Log Analysis
- **SIEM (Security Information and Event Management)**: aggregates logs for detection and analytics
    - **Splunk**: commercial SIEM and log analysis platform

## Network Traffic Analysis
- **Bluetooth**: short-range wireless communication protocol
- **Encapsulation**: wrapping data with protocol headers for transport
- **Faraday's Cage**: shielding to block electromagnetic signals
- **Firewalls**: devices that enforce network traffic filtering rules
- **IPS (Intrusion Prevention System)**: detects and blocks malicious network activity
- **ISP (Internet Service Providers)**: companies that provide internet connectivity
    - **Starlink**: satellite internet service provider
- **LAN (Local Area Network)**: network connecting nearby devices
- **MAC (Multimedia Access Control)**: likely meant MAC (Media Access Control) address
- **Mirrors:** an exact copy of a file or website hosted on a traditional central server
- **Networking Commands**: CLI tools for inspecting and managing networks
- **Network Miner**: packet analysis and forensic tool
- **NFC (Near-Field Communication)**: short-range wireless data exchange
- **OSI (Open Systems Interconnection) Model**: seven-layer conceptual networking model
- **Pi-Hole**: DNS-level ad and tracker blocking appliance
- **Ports & Protocols**: endpoint numbers and rules for network services
- **Proxies**: intermediary servers that relay network requests
- **TCP/IP Model**: practical networking model used on the internet
- **`tcpdump`**: command-line packet capture utility
- **Torrents**: peer-to-peer file distribution using BitTorrent protocol
- **VPN (Virtual Private Network)**: secure tunnel for network communications
    - **Mullvad**: privacy-focused VPN provider
    - **Wiregaurd**: modern, fast VPN protocol
- **Wifi**: wireless local area networking technology
    - **PSK (Pre-Shared Key)**: shared secret used to secure Wi‑Fi
    - **WPA (Wifi Protected Access)**: security standards for wireless networks
- **Wireshark**: GUI packet analyzer for network troubleshooting

## Scanning and Reconaissance
- **BinaryEdge**: IoT and internet asset scanning platform
- **Censys**: internet-wide search engine for hosts and certificates
- **GreyNoise**
- **Insecam**: index of unsecured CCTV streams
- **Nikto**
- **Nmap**
- **Shodan**: search engine for internet-connected devices
- **ZoomEye**: Chinese internet asset search engine
- **Zmap**

## PWN
* **Binary Ninja**
* **Ghidra**
* **GNU Debugger (GDB)**
* **IDA Pro**

## Web Exploitation
* **BurpSuite**
* **PostMan**

## Forensics
* **Autopsy**
* **Sleuth-Kit (TSK)**
* **Volatility2**
* **Volatility3**

## Operating Systems
- **Unix**: family of multitasking, multiuser operating systems
    - **BSD:** unix-like system with a focus on stability and networking
        - **FreeBSD**: unix-like OS known for performance and licensing
            - **DragonFly BSD**: a Unix-like operating system focused on performance, scalability, and advanced file systems
            - **HardenedBSD**: fork of FreeBSD that focuses more on hardening its security
        - **NetBSD:** provide a unified, multi-platform, production-quality operating system
            - **OpenBSD:** fork of NetBSD in 1995 focused heavily on hardening its security and networking
    - **illumos**: an open-source Unix operating system derived from OpenSolaris
    - **Linux**: open-source Unix-like kernel used in many distros
        - **Arch Linux Family**: rolling-release distributions focused on simplicity
            - **Black Arch Linux**: security-focused Arch-based distribution
            - **EndeavourOS**: a lightweight, terminal-focused Arch Linux distribution
            - **Garuda Linux**: a performance-focused Arch Linux distribution with graphical tools
            - **Manjaro**: a user-friendly Arch-based distribution with curated software updates
        - **Debian Linux Family**: stable distributions derived from Debian
            - **Kali**: penetration-testing focused Debian derivative
            - **ParrotOS**: security-oriented Debian-based distro
            - **SubgraphOS**: hardening-focused privacy distro
            - **TailsOS**: live OS designed for anonymity
            - **Ubuntu**: popular user-friendly Debian derivative
                - **Elementary OS**: a polished Ubuntu-based Linux distribution with a simple, macOS-inspired interface
                - **Linux Mint:** free, user-friendly, and highly stable desktop operating system
                - **Kubuntu**: an Ubuntu-based Linux distribution featuring the customizable KDE Plasma desktop
                - **Lubuntu:** a lightweight official flavor of Ubuntu
                    - **DragonOS**: SDR-focused Linux distribution
                - **Pop!_OS**: an Ubuntu-based distribution designed for productivity, gaming, and development
                - **Zorin OS**: a beginner-friendly Ubuntu-based distribution with a Windows-like interface
                - **Xubuntu**: a lightweight Ubuntu flavor featuring the Xfce desktop
            - **Whonix**: privacy OS using Tor isolation
        - **Gentoo Family**: a family of highly customizable, source-based Linux distributions
            - **Gentoo Linux**: a source-based distribution offering extensive control and optimization
        - **Qubes OS Family**: security-focused systems that isolate activities within virtual machines
        - **Red Hat Family**: Linux distributions built around Red Hat technologies and RPM packages
            - **Fedora**: a cutting-edge community distribution sponsored by Red Hat
            - **RHEL**: Red Hat’s enterprise Linux distribution with commercial support
                - **AlmaLinux**: a community-maintained, RHEL-compatible enterprise distribution
                - **CentOS**: a community project centered on the development stream leading to RHEL
                - **Rocky Linux**: a community-maintained, RHEL-compatible enterprise distribution
        - **SUSE Family**: Linux distributions using SUSE technologies and YaST administration tools
            - **openSUSE**: a community distribution available in rolling and stable editions
            - **SUSE Linux Enterprise**: a commercially supported enterprise Linux platform
                - **SLES for SAP**: a SUSE Enterprise edition optimized for SAP workloads
        - **Slackware Family**: traditional Linux distributions emphasizing simplicity and Unix-like design
            - **Slackware Linux**: one of the oldest actively maintained Linux distributions
                - **Salix OS**: a user-friendly, Slackware-compatible Linux distribution
        - **Void Family**: independent distributions based on Void Linux and its XBPS package system
            - **Void Linux**: an independent rolling-release distribution using the runit init system
        - **Xenix**: a discontinued Microsoft-licensed version of Unix for microcomputers
- **TempleOS**: a lightweight biblical-themed operating system created entirely by Terry A. Davis.
- **Terminal**: Text-based shell interface for system interaction
    - **Commands**: Executable operations entered in a shell
    - **Shell Operators**: Symbols that control shell behavior
    - **Shortcuts**: Key combinations for quicker navigation
- **Virtualization**: technology that creates simulated computing environments on physical hardware
    - **Hypervisors**: xoftware that creates and manages virtual machines
        - **VirtualBox**: Oracle’s free, cross-platform desktop hypervisor
        - **VMware**: a family of commercial virtualization and cloud-computing products
        - **Xen**: an open-source, type-1 hypervisor for running isolated virtual machines
    - **WSL (Windows Subsystem for Linux)**: a Windows feature for running Linux environments without a traditional virtual machine
- **Wine**: a compatibility layer for running Windows applications on Unix-like systems

## Hardware Security
- **Burner Phones**: low-cost phones used temporarily to limit identity exposure
- **GPIO Boards**: development boards with pins for controlling electronic components
- **ICS (Industrial Control System)**: systems that monitor and control industrial processes
- **IoT (Internet of Things)**: physical devices that communicate and exchange data over networks
    - **CCTV (Closed-Circuit Television)**: private video systems used for monitoring and surveillance
        - **Cameradar**: a tool for discovering and testing RTSP surveillance cameras
- **Firmware**: low-level software embedded within hardware devices
    - **FreshTomato**: open-source replacement firmware for supported wireless routers
- **Flipper Zero**: a portable tool for exploring radio, access-control, and hardware systems
- **Hardware Backdoor**: a hidden hardware mechanism that bypasses normal security controls
- **Hardware Keyloggers**: physical devices that secretly record keyboard input
- **Hardware Security Key**: a physical device used for secure authentication
    - **Feitian**: a manufacturer of security keys and authentication devices
    - **Google Titan**: Google’s line of hardware security keys
    - **SSH Keys**: cryptographic credentials used to authenticate SSH connections
        - **Non-Resident Keys**: security-key credentials requiring the private key handle from the client
        - **Resident Keys**: discoverable credentials stored directly on a security key
        - **TOFU (Trust on First Use)**: a model that trusts a key initially and warns about later changes
    - **YubiKey**: a hardware security key made by Yubico
- **Physical Firewalls**: dedicated appliances that filter and control network traffic
- **Routers**: devices that forward traffic between different networks
    - **RouterSploit**: a framework for testing routers and embedded devices for vulnerabilities
- **SCADA (Supervisory Control and Data Acquisition)**: systems that remotely monitor and control industrial operations
- **SDR (Software-Defined Radio)**: radio technology that processes signals primarily through software
    - **Directional Wi-Fi Antenna**: an antenna that concentrates wireless signals in one direction
        - **Yagi Antenna**: a directional antenna designed for focused signal transmission and reception
    - **HackRF**: a device for transmitting and receiving a broad range of radio frequencies
    - **RTL-SDR (Realtek Software-Defined Radio)**: an inexpensive receiver used to explore radio signals

## Offensive Security (Red Team)
- **Card Skimming**: stealing payment-card data using a hidden reader
- **Evil Maid**: altering or compromising a device while it is unattended
- **Hardware Backdoor**: using a hidden hardware mechanism to bypass normal security controls
- **Malware**: software designed to damage, disrupt, spy on, or exploit systems
    - **Adware**: software that displays unwanted advertisements and may track user activity
    - **Bloatware**: unnecessary preinstalled software that consumes system resources
    - **Botnet**: a network of compromised devices controlled by an attacker
    - **Computer Virus**: malware that attaches to files and spreads when executed
    - **Computer Worm**: malware that automatically spreads across systems and networks
    - **Logic Bomb**: malicious code activated when a specific condition is met
    - **Ransomware**: malware that encrypts or blocks data and demands payment
    - **Rootkit**: malware that hides itself while maintaining privileged system access
    - **Spyware**: software that secretly monitors and collects user information
        - **Pegasus**: advanced spyware used to compromise and monitor mobile devices
        - **Keylogger**: software or hardware that secretly records keyboard input
    - **Time Bomb**: malicious code triggered at a predetermined time or date
    - **Trojans**: malware disguised as legitimate or desirable software
        - **MalDoc**: a malicious document designed to execute code or deliver malware
        - **Remote Access Trojan (RAT)**: malware that gives an attacker remote control of a system
- **MITM (Man-in-the-Middle Attack)**: secretly intercepting and possibly altering communication between parties
- **Social Engineering**: manipulating people into revealing information or performing unsafe actions
    - **Phishing**: using deceptive messages or websites to steal information
        - **Angler Phishing**: impersonating customer support through social media
        - **Baiting**: offering something enticing to trick a victim into an unsafe action
        - **Business Email Compromise**: impersonating a trusted business contact to enable fraud
        - **Pharming**: manipulating DNS or systems to redirect users to fraudulent websites
        - **Pretexting**: using a fabricated scenario to obtain information or access
        - **Smishing (SMS Phishing)**: delivering phishing messages through text messages
        - **Social Media Phishing**: using deceptive social media content to steal information
        - **Spear Phishing**: targeting a specific person or organization with customized messages
        - **Typosquatting (URL Hijacking)**: registering look-alike domains to deceive users
        - **Watering Hole**: compromising a website frequently visited by intended targets
        - **Whaling**: targeting executives or other high-profile individuals with phishing
        - **Vishing (Voice Phishing)**: using phone calls or voice messages to deceive victims
- **Threat Actors**: individuals or groups that intentionally or unintentionally create cyber risk
    - **Advanced Persistent Threat (APT)**: a skilled, well-resourced group conducting prolonged targeted attacks
    - **Cybercriminal Organization**: an organized group conducting cyberattacks for financial gain
    - **Hacktivist**: an attacker motivated by political or social causes
    - **Insider Threat**: a trusted individual who intentionally or accidentally causes harm
    - **Nation-State**: a government-sponsored actor conducting cyber operations
    - **Script Kiddie**: an inexperienced attacker who relies on existing tools and exploits
    - **Shadow IT**: technology used without an organization’s approval or oversight
- **Schools of Thought**: informal labels describing hackers by experience, authorization, or motivation
    - **Black Hat**: a hacker who acts maliciously and without authorization
    - **Blue Hat**: an external tester invited to find vulnerabilities before release
    - **Green Hat**: a beginner who is actively learning hacking techniques
    - **Grey Hat**: a hacker who may act without permission but lacks clear malicious intent
    - **Red Hat**: a vigilante who aggressively targets malicious hackers
    - **White Hat**: an ethical hacker who tests systems with authorization
- **SIM Swapping**: hijacking a phone number by transferring it to an attacker-controlled SIM
- **Spoofing**: falsifying an identity or data source to appear trustworthy
    - **Biometric Spoofing**: faking biometric traits to bypass identity sensors
    - **CDP (Cisco Discovery Protocol) Spoofing**: sending forged CDP messages to impersonate network devices

## Defensive Security (Blue Team)

- **CSIRT (Computer Security Incident Response Team)**: Group that handles security incidents.
- **GRC (Governance, Risk Management, and Compliance)**: Practices aligning security with business requirements.
    - **CCPA (California Consumer Privacy Act)**: Privacy law protecting California residents.
    - **CIS (Center for Internet Security) Controls**: Best-practice security controls checklist.
    - **GDPR (General Data Protection Regulation)**: EU regulation on personal data protection.
    - **HIPAA (Health Insurance Portability and Accountability Act)**: US law protecting health information.
    - **HITRUST CSF (Health Information Trust Alliance Common Security Framework)**: Compliance framework for health data security.
    - **NIST (National Institutes of Standards and Technology)**: US agency publishing security standards.
    - **PCI-DSS (Payment Card Industry Data Security Standard)**: Requirements for handling cardholder data.
    - **SOC2 (System and Organization Controls)**: Audit standard for service organizations.
- **Honeypots**: Traps designed to detect and study attackers.
- **SOC (Security Operations Center)**: Centralized team monitoring security events.
- **SIEM (Security Information and Event Management)**: Aggregates logs for detection and analytics.
    - **Splunk**: Commercial SIEM and log analysis platform.

## Intersectional Security (Purple Team)
- **Purple Teaming**: Collaborative approach to align red and blue team activities.

## Computer & Digital Forensics
- **Reverse Engineering**: Analyzing binaries to understand behavior.

- **Operational Security (OpSec)**: protects sensitive info getting to an adversary
  - **Adblock**: browser extensions that block ads and trackers
    - **Decentraleyes**: local resource polyfill to reduce third-party calls
    - **Ublock Origin**: efficient configurable ad-blocking extension
- **Antivirus/Antimalware**: software that detects and removes malware
    - **Kapersky**: commercial antivirus and security product suite
    - **MalwareBytes**: anti-malware product focusing on modern threats
    - **McAfee**: longstanding commercial security vendor
    - **Norton**: consumer-focused antivirus and security tools
    - **Windows Defender**: built-in tool that protects your PC from malware
  - **Browsers**: software used to access web content securely when configured
      - **Brave**: privacy-focused browser with built-in ad blocking
      - **Firefox**: open-source browser with strong privacy controls
      - **GNU Icecap**: privacy-oriented browser project
  - **Compartmentalization**: separating activities and data to limit exposure
  - **Dark Web (Tor)**: anonymity network and overlay services accessed via Tor
  - **Email**: communication medium with varying privacy properties
      - **Permanent**: Long-term secure email providers
          - **ProtonMail**: end-to-end encrypted email service
          - **SecureMail**: Privacy-focused email solutions.
          - **Tutanota**: encrypted email provider with zero-knowledge features
          - **Anonady**: privacy-oriented mail service
          - **GudoMail**: alternative secure email provider
          - **MailFence**: encrypted email and collaboration suite
          - **PrivateMail**: privacy-centric email offering
       - **Temporary Mail**: disposable email services for short-term use
           - **GorillaMail**: disposable email address provider
           - **Temp Mailo**: temporary inbox service
           - **TempMail**: disposable email provider
  - **IRC (Internet Relay Chats)**: real-time chat protocol used in communities
      - **Briar**: secure decentralized messaging app
      - **Element**: matrix-based chat client for secure communication
      - **Jabber**: XMPP instant messaging protocol
      - **Signal**: encrypted messaging app for private communication
      - **Telegram:** cloud-based messaging app with a focus on security
      - **Yami**: lightweight chat client
  - **MAC Address Randomization**: technique to prevent device tracking on networks
  - **Passwords**: secrets used to authenticate users; best combined with MFA
      - **Passphrases**: longer memorable strings used as passwords
      - **Password Managers**: tools to generate and store credentials securely
          - **Local**: run on the user's device without cloud sync
              - **KeePassXC**: open-source local password manager
              - **Syncthing**: filesync tool sometimes used to sync vaults
              - **Veracrypt**: encrypted container tool for storing data
              - **Microsoft Word**: unconventional, not recommended for secrets
           - **Browser-Based**: integrated password storage in browsers
               - **Google Password Manager**: browser-integrated credential store
           - **Cloud-Based**: hosted password services with sync
               - **Bitwarden**: open-source cloud password manager
               - **Cryptomater**: cloud-based credential storage
               - **LastPass**: commercial cloud password manager
  - **Secure Search Engines**: privacy-respecting web search alternatives
      - **DuckDuckGo**: search engine that emphasizes privacy
      - **Searx**: open-source metasearch engine that preserves privacy
      - **StartPage**: pivacy-oriented search proxy
 
## Blockchain
- **Atomic Swappers**: Protocols enabling trustless token exchanges.
- **Empty Entry**: Placeholder for future blockchain topics.

## Cloud Security
- **CloudFlare**: CDN and security provider for web infrastructure.
- **Grype**: Vulnerability scanner for container images and filesystems.
