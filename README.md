### Cloud Security
- **CloudFlare**: CDN and security provider for web infrastructure
- **Grype**: vulnerability scanner for container images and filesystems


## Defensive Security (Blue Team)
- **IAM (Identity and Access Management)**
    - **Microsoft Entra ID**: cloud identity and access management service
    - **Microsoft Intune**: cloud service for managing devices, applications, and endpoint policies
- **Operational Security (OpSec)**
    - **Adblock**
        - **Decentraleyes**: local resource polyfill to reduce third-party calls
        - **Ublock Origin**: efficient configurable ad-blocking extension
    - **Antivirus/Antimalware**
        - **Kapersky**: commercial antivirus and security product suite
        - **MalwareBytes**: anti-malware product focusing on modern threats
        - **McAfee**: longstanding commercial security vendor
        - **Norton**: consumer-focused antivirus and security tools
        - **Windows Defender**: built-in tool that protects your PC from malware
    - **Browsers**
        - **Brave**: privacy-focused browser with built-in ad blocking
        - **Firefox**: open-source browser with strong privacy controls
        - **GNU Icecap**: privacy-oriented browser project
        - **Dark Web (Tor)**: anonymity network and overlay services accessed via Tor
    - **Secure Email**
        - **Permanent**
            - **ProtonMail**: end-to-end encrypted email service
            - **SecureMail**: Privacy-focused email solutions.
            - **Tutanota**: encrypted email provider with zero-knowledge features
            - **Anonady**: privacy-oriented mail service
            - **GudoMail**: alternative secure email provider
            - **MailFence**: encrypted email and collaboration suite
            - **PrivateMail**: privacy-centric email offering
        - **Temporary Mail**
            - **GorillaMail**: disposable email address provider
            - **Temp Mailo**: temporary inbox service
            - **TempMail**: disposable email provider
    - **IRC (Internet Relay Chats)**
        - **Briar**: secure decentralized messaging app
        - **Element**: matrix-based chat client for secure communication
        - **Jabber**: XMPP instant messaging protocol
        - **Signal**: encrypted messaging app for private communication
        - **Telegram:** cloud-based messaging app with a focus on security
        - **Yami**: lightweight chat client
    - **Passwords**: secrets used to authenticate users; best combined with MFA
        - **Password Managers**
            - **Local**
                - **KeePassXC**: open-source local password manager
                - **Syncthing**: filesync tool sometimes used to sync vaults
                - **Veracrypt**: encrypted container tool for storing data
                - **Microsoft Word**: unconventional, not recommended for secrets
             - **Browser-Based**
                - **Google Password Manager**: browser-integrated credential store
             - **Cloud-Based**
                - **Bitwarden**: open-source cloud password manager
                - **Cryptomater**: cloud-based credential storage
                - **LastPass**: commercial cloud password manager
    - **Secure Search Engines**
        - **DuckDuckGo**: search engine that emphasizes privacy
        - **Searx**: open-source metasearch engine that preserves privacy
        - **StartPage**: pivacy-oriented search proxy

## Forensics
- **Autopsy**: a graphical digital-forensics platform built on The Sleuth Kit
- **The Sleuth Kit (TSK)**: command-line tools and libraries for analyzing disks and file systems
- **Volatility 2**: a legacy Python framework for analyzing memory captures
- **Volatility 3**: the modern successor to Volatility 2 for memory forensics

## Hardware Security
- **IoT (Internet of Things)**
    - **CCTV (Closed-Circuit Television)**
        - **Cameradar**: a tool for discovering and testing RTSP surveillance cameras
- **Firmware**
    - **FreshTomato**: open-source replacement firmware for supported wireless routers
- **Hardware Security Key**
    - **Feitian**: a manufacturer of security keys and authentication devices
    - **Google Titan**: Google’s line of hardware security keys
    - **YubiKey**: a hardware security key made by Yubico
- **Routers**
    - **ASUS**: a manufacturer of consumer and business networking equipment
    - **Netgear**: a manufacturer of routers, switches, and other networking equipment
    - **TP-Link**: a manufacturer of consumer and business networking equipment
    - **RouterSploit**: a framework for testing routers and embedded devices for vulnerabilities
- **SDR (Software-Defined Radio)**
    - **Directional Wi-Fi Antenna**
            - **Yagi Antenna**: a directional antenna designed for focused signal transmission and reception
    - **Flipper Zero**: a portable tool for exploring radio, access-control, and hardware systems
    - **HackRF**: a device for transmitting and receiving a broad range of radio frequencies
    - **RTL-SDR (Realtek Software-Defined Radio)**: an inexpensive receiver used to explore radio signals

## Log Analysis
- **Datadog**: a cloud platform for monitoring logs, applications, infrastructure, and security events
- **Microsoft Excel**: a spreadsheet tool for filtering, organizing, and analyzing exported log data
- **SIEM (Security Information and Event Management)**: aggregates and analyzes logs to detect security threats
    - **Elastic Security**: an Elastic Stack solution for security analytics and investigation
    - **Microsoft Sentinel**: Microsoft’s cloud-native SIEM and security orchestration platform
    - **Splunk**: a commercial platform for searching, monitoring, and analyzing machine-generated data

## Network Traffick Analysis
- **ISP (Internet Service Providers)**
    - **Starlink**: satellite internet service provider
- **Network Miner**: packet analysis and forensic tool
- **Pi-Hole**: DNS-level ad and tracker blocking appliance
- **`tcpdump`**: command-line packet capture utility
- **`tshark`**: command-line port of the Wireshark packet analyzer tool
- **VPN (Virtual Private Network)**
    - **Mullvad**: privacy-focused VPN provider
    - **Wiregaurd**: modern, fast VPN protocol
- **Wireshark**: GUI packet analyzer for network troubleshooting

## Offensive Security (Red Teaming)
- **Malware**: software designed to damage, disrupt, spy on, or exploit systems
    - **Spyware**
        - **Pegasus**: advanced spyware used to compromise and monitor mobile devices
        - **Keylogger**
            - **Pico BadUSB:** simple implementation of the BadUSB idea

## Open Source Intelligence (OSINT)
- **Piracy**
    - **Pirate Bay**: a popular torrent index site for sharing files
- **Search Engines**
    - **Google Reverse Image Search**: find similar images and their sources
    - **Yandex**: Russian search engine with image and web search features

## Operating Systems
- **Unix**: family of multitasking, multiuser operating systems
    - **BSD**
        - **FreeBSD**: unix-like OS known for performance and licensing
            - **DragonFly BSD**: a Unix-like operating system focused on performance and scalable file systems
            - **HardenedBSD**: fork of FreeBSD that focuses more on hardening its security
        - **NetBSD**: provide a unified, multi-platform, production-quality operating system
            - **OpenBSD:** fork of NetBSD in 1995 focused heavily on hardening its security and networking
    - **illumos**: an open-source Unix operating system derived from OpenSolaris
    - **Linux**: open-source Unix-like kernel used in many distros
        - **Arch Linux Family**
            - **Black Arch Linux**: security-focused Arch-based distribution
            - **EndeavourOS**: a lightweight, terminal-focused Arch Linux distribution
            - **Garuda Linux**: a performance-focused Arch Linux distribution with graphical tools
            - **Manjaro**: a user-friendly Arch-based distribution with curated software updates
        - **Debian Linux Family**
            - **Kali**: penetration-testing focused Debian derivative
            - **ParrotOS**: security-oriented Debian-based distro
            - **SubgraphOS**: hardening-focused privacy distro
            - **TailsOS**: live OS designed for anonymity
            - **Ubuntu**: popular user-friendly Debian derivative
                - **Elementary OS**: a polished Ubuntu-based Linux distribution with a macOS like interface
                - **Linux Mint:** free, user-friendly, and highly stable desktop operating system
                - **Kubuntu**: an Ubuntu-based Linux distribution featuring the customizable KDE Plasma desktop
                - **Lubuntu:** a lightweight official flavor of Ubuntu
                    - **DragonOS**: SDR-focused Linux distribution
                - **Pop!_OS**: an Ubuntu-based distribution designed for productivity, gaming, and development
                - **Zorin OS**: a beginner-friendly Ubuntu-based distribution with a Windows-like interface
                - **Xubuntu**: a lightweight Ubuntu flavor featuring the Xfce desktop
            - **Whonix**: privacy OS using Tor isolation
        - **Gentoo Family**
            - **Gentoo Linux**: a source-based distribution offering extensive control and optimization
        - **Qubes OS Family**
        - **Red Hat Family**
            - **Fedora**: a cutting-edge community distribution sponsored by Red Hat
            - **RHEL**: Red Hat’s enterprise Linux distribution with commercial support
                - **AlmaLinux**: a community-maintained, RHEL-compatible enterprise distribution
                - **CentOS**: a community project centered on the development stream leading to RHEL
                - **Rocky Linux**: a community-maintained, RHEL-compatible enterprise distribution
        - **SUSE Family**
            - **openSUSE**: a community distribution available in rolling and stable editions
            - **SUSE Linux Enterprise**: a commercially supported enterprise Linux platform
                - **SLES for SAP**: a SUSE Enterprise edition optimized for SAP workloads
        - **Slackware Family**
            - **Slackware Linux**: one of the oldest actively maintained Linux distributions
                - **Salix OS**: a user-friendly, Slackware-compatible Linux distribution
        - **Void Family**
            - **Void Linux**: an independent rolling-release distribution using the runit init system
        - **Xenix**: a discontinued Microsoft-licensed version of Unix for microcomputers
- **TempleOS**: a lightweight biblical-themed operating system created entirely by Terry A. Davis.
- **Virtualization**
    - **Hypervisors**
        - **VirtualBox**: Oracle’s free, cross-platform desktop hypervisor
        - **VMware**: a family of commercial virtualization and cloud-computing products
        - **Xen**: an open-source type-1 hypervisor for running isolated virtual machines
    - **WSL (Windows Subsystem for Linux)**: a Windows feature for running Linux environments without a VM
- **Wine**: a compatibility layer for running Windows applications on Unix-like systems

## Password Cracking
- **Hashcat**: a password-recovery tool that uses CPUs and GPUs to crack password hashes
- **John the Ripper**: a password-recovery tool that detects and cracks numerous hash formats
    - **PDF2John**: a utility that extracts password hashes from encrypted PDF files for use with John the Ripper

## PWN
- **Dynamic Analysis (Binary Exploitation)**
    - **angr**: a Python framework for binary analysis and symbolic execution
    - **GNU Debugger (GDB)**: a debugger for inspecting and controlling programs during execution 
    - **pwntools**: a Python framework for developing exploits and interacting with binaries
- **Static Analysis (Reverse Engineering)**
    - **Binary Ninja**: a commercial reverse-engineering platform for analyzing compiled binaries
    - **Ghidra**: an open-source reverse-engineering suite developed by the NSA 
    - **IDA Pro**: a commercial disassembler and debugger for reverse engineering bin

## Scanning and Reconaissance
- **BinaryEdge**: an internet asset intelligence and scanning platform
- **Censys**: an internet-wide search engine for hosts, services, and certificates
- **GreyNoise**: a threat-intelligence platform that identifies internet-wide scanning activity
- **Insecam**: an index of publicly accessible and unsecured CCTV streams
- **Nikto**: an open-source scanner for identifying web-server vulnerabilities and misconfigurations
- **Nmap**: a network scanner for discovering hosts, ports, services, and operating systems
- **Shodan**: a search engine for internet-connected devices and services
- **ZMap**: a high-speed scanner designed for internet-wide network surveys
- **ZoomEye**: an internet asset search engine developed in China

## Web Exploitation
- **Burp Suite**: a web-security testing platform for intercepting and modifying HTTP traffic
- **Postman**: an API platform for creating, sending, and testing HTTP requests