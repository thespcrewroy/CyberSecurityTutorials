# Cyber Security Tutorials

<details>
<summary>📖 Table of Contents</summary>
<br />

- [Artificial Intelligence](#artificial-intelligence)
- [Blockchain](#blockchain)
- [Cloud Security](#cloud-security)
- [Cryptography](#cryptography)
- [Defensive Security (Blue Team)](#defensive-security-blue-team)
- [Forensics](#forensics)
- [Log Analysis](#log-analysis)
- [Network Traffic Analysis](#network-traffic-analysis)
- [Offensive Security (Red Team)](#offensive-security-red-team)
- [Open Source Intelligence (OSINT)](#open-source-intelligence-osint)
- [Operating Systems](#operating-systems)
- [Password Cracking](#password-cracking)
- [Physical Security & Internet of Things (IoT)](#physical-security--internet-of-things-iot)
- [PWN](#pwn)
- [Scanning and Reconnaissance](#scanning-and-reconnaissance)
- [Web Exploitation](#web-exploitation)

</details>

## Artificial Intelligence
* **[OWASP LLM Top 10](https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/)**: most critical security vulnerabilities and risks when building AI systems 
* **[LakeraAI](https://www.lakera.ai/)**: leading security platform to secure your AI future

## Blockchain
- **Atomic Swaps**
    - **[EigenWallet (formerly UnstoppableSwap)](https://unstoppableswap.net/)**: a platform for atomic swaps between Bitcoin and Monero
- **Cryptocurrency Exchange Aggregators**
    - **[OrangeFren](https://orangefren.com/)**: a directory and rate aggregator for cryptocurrency exchange services
    - **[Trocador](https://trocador.app/)**: a cryptocurrency exchange aggregator that compares and routes swaps through third-party providers
- **Cryptocurrency Wallet**
    - **[Feather Wallet](https://docs.featherwallet.org/)**: a lightweight, privacy-focused desktop wallet for Monerome

## Cloud Security
- **[Cloudflare](https://developers.cloudflare.com/fundamentals/security/)**: a cloud platform providing CDN, DNS, DDoS protection, and web security services
- **[Cyera](https://www.cyera.com/platform)**: discovers, classifies, and protects sensitive data across cloud, SaaS, and hybrid environments
- **Containerization**
    - **[Docker](https://docs.docker.com/get-started/)**: a platform for building and running applications inside containers
    - **Container Images**
        - **[Dive](https://github.com/wagoodman/dive)**: a tool for inspecting container-image layers and identifying wasted space
    - **Container Orchestration**
        - **[Kubernetes](https://kubernetes.io/docs/concepts/overview/)**: a platform that automates the deployment, scaling, and management of containerized applications
        - **[Red Hat OpenShift](https://docs.redhat.com/en/documentation/openshift_container_platform/4.20/html/overview/ocp-overview)**: an enterprise Kubernetes platform
    - **Container Security**
        - **[Grype](https://oss.anchore.com/docs/guides/vulnerability/getting-started/)**: a vulnerability scanner for container images, filesystems, and software bills
- **[Google Security Command Center](https://cloud.google.com/security-command-center/docs/overview)**: Google Cloud’s platform for identifying vulnerabilities

## Cryptography
- **Cryptanalysis**
    - **[Cash Sleuth](https://www.cachesleuth.com/multidecoder/)**: a free collection of online tools and cipher solvers designed specifically for geocachers
    - **[Crypto Attacks](https://github.com/jvdsn/crypto-attacks)**: Python implementations of cryptographic attacks and utilities
- **Data-at-Rest Encryption**
    - **[Cryptomator](https://docs.cryptomator.org/)**: encrypts files inside vaults before local or cloud storage
    - **FDE (Full-Disk Encryption)**
        - **[BitLocker](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/)**: Microsoft’s full-disk encryption feature
        - **[FileVault](https://support.apple.com/guide/deployment/intro-to-filevault-dep82064ec40/web)**: Apple’s full-disk encryption feature for macOS
    - **[VeraCrypt](https://veracrypt.io/en/Downloads.html)**: an open-source encryption application for files, partitions, and storage devices
- **PGP (Pretty Good Privacy)**
    - **OpenPGP**
        - **[GPA (GNU Privacy Assistant)](https://www.gnupg.org/software/gpa/)**: a graphical interface for managing OpenPGP keys
        - **[MIT PGP Key Server](https://pgp.mit.edu/)**: a public server for finding and submitting OpenPGP keys

## Defensive Security (Blue Team)
- **Access Control**
    - **[Active Directory](https://learn.microsoft.com/en-us/training/paths/active-directory-domain-services/)**: Microsoft’s directory service for centrally managing identities
    - **[AppLocker](https://learn.microsoft.com/en-us/windows/security/application-security/application-control/app-control-for-business/applocker)**: restricts what users run
    - **[CyberArk](https://docs.cyberark.com/)**: an identity-security platform specializing in privileged-access management
    - **Directory Access Protocol**
        - **LDAP (Lightweight Directory Access Protocol)**
            - **[OpenLDAP](https://www.openldap.org/)**: an open-source implementation of the Lightweight Directory Access Protocol
    - **[Google Authenticator](https://shorturl.at/CdUos)**: a mobile application that generates verification codes for two-factor authentication
    - **GPO (Group Policy Object)**
        - **[Local Group Policy Editor](https://shorturl.at/NjQIl)**: a Microsoft utility for configuring local Group Policy settings
    - **[JumpCloud](https://support.jumpcloud.com/)**: a cloud platform for managing identities, devices, authentication, and access
    - **[Microsoft Authenticator](https://shorturl.at/9NEvE)**: a mobile application supporting multifactor and passwordless authentication
    - **[Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/)**: Microsoft’s cloud identity and access-management platform
    - **[NIST SP 800-63](https://pages.nist.gov/800-63-3/)**: NIST guidance covering digital identity, authentication, credentials, and federation
    - **[OpenNAC](https://doc-opennac.opencloudfactory.com/1.2.1/introduction/whatis/intro.html)**: an open-source network-access-control platform
    - **[SailPoint](https://documentation.sailpoint.com/)**: an identity-governance platform for managing access, permissions, and identity lifecycles
    - **[Two-Factor Authentication for Apple ID](https://support.apple.com/en-us/102660)**: Apple guidance for enabling two-factor authentication on Apple accounts
- **Asset Management**
    - **[Axonius](https://www.axonius.com/)**: cybersecurity asset management and asset intelligence platform
    - **[CIS Asset Tracking Spreadsheet](https://www.cisecurity.org/insights/white-papers/cis-controls-inventory-tracking-spreadsheets)**: a spreadsheet for inventorying assets
    * **[Daniel Miessler’s Cybersecurity Resources](https://danielmiessler.com/blog/continuous-asset-management-security)**: tutorails for asset management security
    - **[Lansweeper](https://www.lansweeper.com/)**: an IT asset-discovery and inventory platform
    - **[NIST SP 1800-5](https://www.nccoe.nist.gov/publication/1800-5/)**: practical NIST guidance for improving IT asset management
    - **[Open-AudIT](https://www.open-audit.org/about.php)**: a network discovery and inventory-auditing platform
    - **[Snipe-IT](https://snipeitapp.com/)**: an open-source IT asset-management platform
    - **[Spiceworks](https://www.spiceworks.com/free-pc-network-inventory-software/)**: an IT inventory and asset-management platform
    - **[Spirion](https://www.archtis.com/spirion-platform-overview/)**: a data-discovery and classification platform for locating sensitive information
    - **[State of Oregon Data Inventory Template](https://shorturl.at/MGJet)**: a template for documenting and managing an organization’s data inventory
- **Business Continuity and Disaster Recovery (BCDR)**
    - **[Amanda Network Backup](https://www.amanda.org/)**: an open-source backup solution that uses a central server to back up multiple OS's to disks
    - **[Apple Time Machine](https://support.apple.com/en-us/104984)**: a backup utility built into macOS that automatically creates versioned backups
    - **[Bacula](https://www.bacula.org/)**: an open-source network backup, recovery, and data-verification platform
    - **[CISA and MS-ISAC Joint Ransomware Guide](https://www.cisa.gov/sites/default/files/publications/CISA_MS-ISAC_Ransomware%20Guide_S508C.pdf)**: joint guidance in backups
    - **[Clonezilla](https://clonezilla.org/clonezilla-live-doc.php)**: an open-source disk-imaging and cloning tool used to back up, restore, and deploy complete disks
    - **[Microsoft Backup and Restore](https://support.microsoft.com/en-us/windows/experience/backup-recovery/back-up-and-restore-with-windows-backup)**: built-in Windows
    - **[Microsoft Volume Shadow Copy Service](https://learn.microsoft.com/en-us/windows-server/storage/file-server/volume-shadow-copy-service)**: a Windows service
    - **[No More Ransom](https://www.nomoreransom.org/)**: ransomware-prevention guidance, IR resources, and free decryption tools for supported ransomware variants
    - **[Syncthing](https://docs.syncthing.net/)**: a decentralized continuous file-synchronization tool
    - **[Redo Rescue](https://redorescue.com/)**: an open-source bootable backup and recovery environment used to create and restore complete system images
- **Endpoint Management**
    - **[Microsoft Configuration Manager (formerly SCCM)](https://learn.microsoft.com/en-us/intune/configmgr/)**: an enterprise platform for monitoring endpoint devices
    - **[Microsoft Intune](https://learn.microsoft.com/en-us/intune/intune-service/)**: a cloud platform for managing devices, applications, and endpoint policies
- **GRC (Governance, Risk, and Compliance)**
    - **[CCPA (California Consumer Privacy Act)](https://oag.ca.gov/privacy/ccpa)**: privacy law protecting California residents
    - **[CIS Controls](https://www.cisecurity.org/controls)**: best-practice security controls checklist
        - **[CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)**: consensus-developed secure configuration guidelines for OS, apps, cloud, and network devices
        - **[CIS Build Kits](https://www.cisecurity.org/insights/blog/build-kits-speed-implementation-of-secure-configurations)**: automated config files, scripts, and GPOs
        - **[CIS-CAT Pro](https://www.cisecurity.org/cybersecurity-tools/cis-cat-pro)**: automated assessment tool that scans systems and reports their compliance with CIS
        - **[CIS InfoSec Policy Templates](https://www.cisecurity.org/controls/policy-templates)**: customizable policy templates that to help document security requirements
        - **[CIS SecureSuite Membership](https://www.cisecurity.org/cis-securesuite)**: membership providing access to CIS security tools and resources
    - **[CMMC (Cybersecurity Maturity Model Certification)](https://dodcio.defense.gov/CMMC/Resources-Documentation/):** ensure defense contractors protect unclassified info
    - **[DISA STIGs](https://public.cyber.mil/stigs/downloads/)**: security configuration standards developed by the Defense Information Systems Agency DoD Sytems and tech
    - **[GDPR (General Data Protection Regulation)](https://gdpr-info.eu/)**: EU regulation on personal data protection
    - **[HIPAA (Health Insurance Portability and Accountability Act)](https://www.hhs.gov/hipaa/index.html)**: US law protecting health information
    - **[HITRUST CSF (Common Security Framework)](https://hitrustalliance.net/hitrust-framework)**: health data security
    - **[ISO/IEC 27001](https://www.iso.org/standard/27001)**: world's leading international standard for managing information security
    - **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview):** unified data security, governance, and compliance platform
    - **[NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework)**: a framework for understanding and managing cybersecurity risk
    - **[PCI-DSS (Payment Card Industry Data Security Standard)](https://www.pcisecuritystandards.org/standards/pci-dss/)**: requirements for handling cardholder data
    - **[SOC (System and Organization Controls)](https://www.aicpa-cima.com/resources/)**: audit standard for service organizations
- **Incident Response**
    - **[Carnegie Mellon Incident Response Plan](https://www.cmu.edu/iso/governance/procedures/IRPlan.html)**: an example university incident-response plan
    - **CSIRT (Computer Security Incident Response Team)**
        - **[Forum of Incident Response and Security Teams](https://www.first.org/)**: an international organization supporting incident-response teams     
    - **[MS-ISAC Incident Reporting](https://www.cisecurity.org/isac/report-an-incident)**: channels for reporting cybersecurity incidents to MS-ISAC
    - **[Open Trust Alliance Cyber Incident and Breach Response Guide](https://www.internetsociety.org/wp-content/uploads/2019/04/2017dpd.pptx.pdf)**: a checklist and guide
    - **[State of Oregon IR Plan Template](https://www.oregon.gov/eis/cyber-security-services/pages/security-operations-center.aspx)**: a custoxmizable IR plan template
- **Operational Security (OpSec)**
    - **Adblock**
        - **[Decentraleyes](https://git.synz.io/Synzvato/decentraleyes)**: locally provides common web resources to reduce third-party requests
        - **[uBlock Origin](https://github.com/gorhill/uBlock)**: an efficient and configurable content-blocking browser extension
    - **Antivirus/Antimalware**
        - **[Bitdefender](https://www.bitdefender.com/consumer/support/)**: provides malware protection and endpoint-security products
        - **[ClamAV](https://www.clamav.net/)**: an open-source anti-malware toolkit commonly used on Unix-like systems
        - **[EICAR Anti-Malware Test File](https://www.eicar.org/download-anti-malware-testfile/)**: a harmless standardized file for testing anti-malware detection
        - **[Kaspersky](https://support.kaspersky.com/)**: a commercial antivirus and security-product suite
        - **[Malwarebytes](https://www.malwarebytes.com/)**: anti-malware software focused on modern threats
        - **[McAfee](https://www.mcafee.com/)**: a provider of consumer antivirus and online-protection products
        - **[Norton](https://support.norton.com/)**: a provider of consumer antivirus and online-security products
        - **[Microsoft Defender](https://learn.microsoft.com/en-us/defender-endpoint/)**: Microsoft’s endpoint-protection and threat-detection platform
    - **Browsers**
        - **[Brave](https://support.brave.com/)**: a privacy-focused browser with built-in content blocking
        - **[Comodo Dragon](https://www.comodo.com/home/browsers-toolbars/browser.php)**: a security-focused Chromium-based web browser
        - **[Firefox](https://support.mozilla.org/)**: an open-source browser with configurable privacy controls
        - **[GNU IceCat](https://www.gnu.org/software/icecat/)**: GNU’s privacy-oriented version of Firefox
        - **[Tor Browser](https://tb-manual.torproject.org/)**: a browser that routes traffic through the Tor network
    - **End-to-End Encryption (E2EE) Services**
        - **[Briar](https://briarproject.org/manual/)**: a decentralized encrypted messaging application
        - **[Element](https://docs.element.io/)**: a messaging client built on the Matrix protocol
        - **[Signal](https://support.signal.org/)**: an end-to-end encrypted messaging application
        - **[Telegram](https://telegram.org/faq)**: a cloud-based messaging application with optional end-to-end encrypted chats
    - **Passwords**
        - **[CIS Password Policy Guide](https://www.cisecurity.org/insights/white-papers/cis-password-policy-guide)**: CIS guidance for managing enterprise password policies
        - **[Have I Been Pwned](https://haveibeenpwned.com/)**: a service for checking whether email addresses or passwords appear in known breaches
        - **Password Managers**
            - **[Bitwarden](https://bitwarden.com/help/)**: an open-source password manager supporting hosted and self-hosted vaults
            - **[Google Password Manager](https://support.google.com/accounts/answer/6208650)**: Google’s browser- and account-integrated credential manager
            - **[KeePassXC](https://keepassxc.org/docs/)**: an open-source password manager that stores credentials in a local encrypted database
            - **[LastPass](https://support.lastpass.com/)**: a commercial cloud-based password manager
            - **[Password Safe](https://pwsafe.org/)**: an open-source password manager for storing credentials in an encrypted database
        - **[Specops Password Auditor](https://specopssoft.com/product/specops-password-auditor/)**: an Active Directory auditing tool for identifying weak or compromised passwords
    - **Secure Email**
        - **[Addy.io (formerly AnonAddy)](https://addy.io/help/)**: an email-alias service
        - **[Guerrilla Mail](https://www.guerrillamail.com/)**: a disposable email-address service
        - **[Mailfence](https://kb.mailfence.com/)**: an encrypted email and collaboration service
        - **[Microsoft 365 Quarantine](https://learn.microsoft.com/en-us/defender-office-365/quarantine-about)**: isolates suspected spam, phishing, malware, etc.
        - **[NIST SP 800-177 Revision 1](https://csrc.nist.gov/pubs/sp/800/177/r1/final)**: NIST guidance for establishing trustworthy email systems
        - **[Private-Mail](https://privatemail.com/)**: a privacy-focused encrypted email service
        - **[Proton Mail](https://proton.me/support/mail)**: an encrypted email service with end-to-end and zero-access encryption
        - **[Temp Mail](https://temp-mail.org/)**: a temporary inbox and disposable email service
        - **[Tuta (formerly Tutanota)](https://tuta.com/support)**: an encrypted email service
    - **Secure Search Engines**
        - **[DuckDuckGo](https://duckduckgo.com/duckduckgo-help-pages/)**: a search engine designed to limit user tracking
        - **[SearXNG](https://docs.searxng.org/)**: an open-source, privacy-respecting metasearch engine
        - **[Startpage](https://support.startpage.com/)**: a privacy-oriented search engine and search proxy
- **Security Awareness and Training:**
    - **[Federal Virtual Training Environment Online Courses](https://niccs.cisa.gov/training/cisa-learning)**: former FedVTE program now provided through CISA Learning
    - **[GCA Cybersecurity Toolkit for Small Business](https://gcatoolkit.org/smallbusiness/)**: cybersecurity and MFA guidance and tools for small businesses
    - **[MS-ISAC Cybersecurity Awareness Toolkit](https://www.cisecurity.org/ms-isac/ms-isac-toolkit)**: collection of no-cost cybersecurity awareness materials
    - **[MS-ISAC Newsletter](https://resources.cisecurity.org/ms-isac-subscription)**: provides advisories, vulnerability information, and security updates
    - **[National Cybersecurity Alliance](https://staysafeonline.org/)**: nonprofit organization that provides cybersecurity, privacy, and online-safety education
    - **[SANS OUCH Newsletters](https://www.sans.org/newsletters/ouch)**: free monthly security awareness newsletters explaining current cybersecurity topics in language
    - **[Security Awareness Toolbox](https://www.sans.org/tools/security-awareness-planning-toolkit)**: collection of templates, planning guides, metrics, and other resources
    - **[Stay Safe Online](https://www.staysafeonline.org/resources/online-safety-and-privacy/videos)**: collection of videos and educational resources about online behavior
- **Security Operations**
    - **[ANY.RUN](https://any.run/)**: an interactive sandbox for analyzing malware behavior
    - **[CrowdStrike Falcon](https://www.crowdstrike.com/en-us/platform/)**: a cloud-native endpoint-protection and threat-detection platform
    - **CTI (Cyber Threat Intelligence)**
        - **[Elections Infrastructure Information Sharing and Analysis Center](https://www.cisecurity.org/ei-isac)**: cybersecurity support and threat sharing for elections
        - **[Google Threat Intelligence](https://cloud.google.com/security/products/threat-intelligence)**: combines threat intelligence from Google, Mandiant, and VirusTotal
        - **[Homeland Security Information Network](https://www.dhs.gov/homeland-security-information-network-hsin)**: a secure platform for info sharing and collaboration
        - **[Mandiant](https://cloud.google.com/security/mandiant)**: provides threat intelligence, incident response, and managed defense services
        - **[MITRE ATT&CK](https://attack.mitre.org/)**: a knowledge base describing adversary tactics and techniques
        - **[ReversingLabs Spectra Analyze](https://docs.reversinglabs.com/SpectraAnalyze/)**: a malware-analysis and threat-intelligence platform
        - **[SANS Internet Storm Center](https://isc.sans.edu/)**: a threat-monitoring and information-sharing service analyzing malicious internet activity
        - **[VirusTotal](https://docs.virustotal.com/)**: analyzes files, URLs, domains, and IP addresses for malicious activity
    - **[ENISA Incident Response Plan](https://www.enisa.europa.eu/topics/eu-incident-response-and-cyber-crisis-management)**: IR and resilience guidance from ENISA
    - **[MS-ISAC](https://www.cisecurity.org/ms-isac)**: cybersecurity resources, threat intelligence, and incident-response support for SLTT governments
    - **[MS/EI-ISAC Malicious Code Analysis Platform](https://www.cisecurity.org/services/malicious-code-analysis-platform)**: nonpublic sandbox for analyzing sus files
    - **[MS-ISAC Services](https://www.cisecurity.org/ms-isac/services)**: cybersecurity services available through MS-ISAC
    - **IDS/IPS (Intrusion Detection & Intrusion Prevention System):**
        - **[Snort](https://www.snort.org/):** open-source network intrusion detection and prevention system
        - **[Suricata](https://docs.suricata.io/)**: an open-source intrusion-detection, intrusion-prevention, and network-monitoring engine
    - **[Zabbix](https://www.zabbix.com/)**: an open-source platform for monitoring infrastructure, networks, applications, and services
- **Vulnerability Management**
    - **[endoflife.date](https://endoflife.date/)**: a community-maintained resource tracking product support and end-of-life dates
    - **[Lynis](https://cisofy.com/lynis/)**: an open-source security-auditing and system-hardening tool
    - **[OpenSCAP](https://www.open-scap.org/)**: an open-source ecosystem for assessing and enforcing security baselines
    - **[OpenVAS](https://openvas.org/)**: an open-source vulnerability-scanning and management framework
    - **Patch Management**
        - **[NIST SP 800-40 Revision 4](https://csrc.nist.gov/pubs/sp/800/40/r4/final)**: NIST guidance for enterprise patch-management planning and prevention
    - **[Snyk](https://docs.snyk.io/)**: identifies vulnerabilities in code, dependencies, containers, and infrastructure
    - **[U.S. National Vulnerability Database](https://nvd.nist.gov/)**: a searchable repository of standardized information about publicly disclosed vulnerabilities

## Forensics
- **[ExifTool by Phil Harvey](https://exiftool.org/)**: a command-line utility for reading, writing, and inspecting file metadata
- **File-System Forensics**
    - **[Autopsy](https://www.sleuthkit.org/autopsy/)**: a graphical digital-forensics platform built on The Sleuth Kit
    - **[Binwalk](https://github.com/ReFirmLabs/binwalk)**: identifies and extracts files embedded inside firmware and other binary data 
    - **[Disk Wipe](https://www.diskwipe.org/)**: a portable Windows application for permanently erasing storage volumes
    - **[Foremost](https://foremost.sourceforge.net/)**: recovers files using headers, footers, and internal data structures
    - **[FTK Imager](https://www.exterro.com/ftk-product-downloads/ftk-imager-version-4-7-1)**: a forensic tool for creating disk images
    - **[NIST SP 800-88](https://csrc.nist.gov/pubs/sp/800/88/r2/final)**: NIST guidance for sanitizing storage media
    - **[The Sleuth Kit (TSK)](https://www.sleuthkit.org/sleuthkit/)**: command-line tools and libraries for analyzing disks and file systems
- **Memory Forensics**
    - **[Volatility 2](https://github.com/volatilityfoundation/volatility)**: a legacy Python framework for analyzing memory captures
    - **[Volatility 3](https://volatility3.readthedocs.io/en/latest/)**: the modern Volatility framework for memory forensics
- **Spectrography**
    - **[Audacity](https://manual.audacityteam.org/man/spectrogram_view.html)**: an audio editor used to inspect waveforms and spectrograms
- **Steganography**
    - **[Aperi'Solve](https://www.aperisolve.fr/)**: an online platform that performs multiple steganographic analyses on images
    - **[Steghide](https://steghide.sourceforge.net/)**: hides and extracts data within supported image and audio files
    - **[StegSeek](https://github.com/RickdeJager/stegseek)**: performs high-speed password recovery and extraction against Steghide files
    - **[StegSolve](https://github.com/zardus/ctf-tools/tree/master/stegsolve)**: a Java tool for examining image color channels and bit planes
- **[`strings`](https://sourceware.org/binutils/docs/binutils/strings.html)**: a command-line utility that extracts readable character sequences from binary files
- **[`xxd`](https://github.com/vim/vim/tree/master/src/xxd)**: creates hexadecimal dumps and converts hexadecimal data back into binary
- **[YARA](https://yara.readthedocs.io/en/stable/)**: identifies malware and other files using pattern-matching rules

## Log Analysis
- **[Datadog](https://docs.datadoghq.com/logs/)**: a cloud platform for monitoring logs, applications, infrastructure, and security events
- **[`grep` (Global Regular Expression Print)](https://www.gnu.org/software/grep/manual/grep.html)**: a command-line utility that searches text for matching patterns
- **[Microsoft Excel](https://support.microsoft.com/en-us/excel/)**: a spreadsheet tool for filtering, organizing, and analyzing exported log data
- **[ELK Stack](https://www.elastic.co/docs/get-started/the-stack)**: a collection of Elastic tools for ingesting, storing, searching, and visualizing log data
- **SIEM (Security Information and Event Management)**
    - **[Datadog Cloud SIEM](https://docs.datadoghq.com/security/cloud_siem/)**: a cloud-native platform for detecting and investigating threats using security telemetry
    - **[Elastic Security](https://www.elastic.co/docs/solutions/security)**: Elastic’s SIEM, threat-detection, and security-investigation platform
    - **[Google SecOps (formerly Chronicle)](https://docs.cloud.google.com/chronicle/docs/overview)**: Google’s cloud-native SIEM and SOAR platform
    - **[Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/overview)**: Microsoft’s cloud-native SIEM and security orchestration platform
    - **[Splunk](https://docs.splunk.com/Documentation/Splunk/)**: a platform for searching, monitoring, and analyzing machine-generated data
  
## Network Traffic Analysis
- **[Bettercap](https://www.bettercap.org/project/introduction/)**: a framework for network reconnaissance and traffic manipulation
- **[Darktrace](https://www.darktrace.com/)**: an AI-driven security platform that detects anomalous behavior across networks and other environments
- **DNS (Domain Name System)**
    - **[BlueCat Address Manager (formerly Proteus)](https://bluecatnetworks.com/)**: a centralized IP management platform for administering DNS, DHCP, and IP addresses
    - **[OpenDNS](https://www.opendns.com/)**: a DNS service providing security filtering and customizable content controls
    - **[Pi-hole](https://docs.pi-hole.net/)**: a DNS-level ad and tracker blocking appliance
    - **[Quad9](https://quad9.net/)**: a privacy-focused public DNS service that blocks known malicious domains
- **[Ettercap](https://www.ettercap-project.org/)**: a tool for analyzing and testing network communications
- **Firewalls**
    - **[AWS Network Firewall](https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html)**: a managed network firewall for filtering and inspecting traffic within Amazon Virtual Private Clouds
    - **[Azure Firewall](https://learn.microsoft.com/en-us/azure/firewall/overview)**: Microsoft Azure’s managed cloud firewall for controlling and inspecting traffic across Azure networks
    - **[Palo Alto Networks Next-Generation Firewalls](https://docs.paloaltonetworks.com/pan-os)**: application-layer firewalls that identify and control traffic
        - **[Panorama](https://docs.paloaltonetworks.com/panorama)**: Palo Alto Networks’ centralized platform for managing multiple firewalls and their security policies
    - **[Windows Firewall](https://learn.microsoft.com/en-us/windows/security/operating-system-security/network-security/windows-firewall/)**: a host-based firewall built into Windows that filters incoming and outgoing network traffic
- **[Impacket](https://github.com/fortra/impacket)**: a Python collection for interacting with Windows network protocols
- **IPS (Intrusion Prevention System)**
    - **[Snort](https://www.snort.org/)**: an intrusion detection and prevention system for analyzing network traffic
- **ISP (Internet Service Providers)**
    - **[Starlink](https://www.starlink.com/support)**: a satellite internet service provider
- **[NetworkMiner](https://www.netresec.com/?page=NetworkMiner)**: a packet analysis and network forensics tool
- **[RANCID](https://shrubbery.net/rancid/index.html)**: automatically collects, stores, and tracks changes to router and switch configurations
- **[`tcpdump`](https://www.tcpdump.org/manpages/tcpdump.1.html)**: a command-line packet capture utility
- **VPN (Virtual Private Network)**
    - **[Mullvad](https://mullvad.net/en/help)**: a privacy-focused VPN provider
    - **[Tailscale](https://tailscale.com/kb)**: a mesh VPN service that connects devices using WireGuard
    - **[WireGuard](https://www.wireguard.com/quickstart/)**: a modern, fast VPN protocol
- **Wifi**
    - **[Aircrack-ng](https://www.aircrack-ng.org/documentation.html)**: a suite for assessing and monitoring wireless-network security
    - **[HPE Aruba Networking](https://arubanetworking.hpe.com/techdocs/ArubaDocPortal/content/docportal.htm)**: a vendor of wireless access points, switches, gateways, and network-management products
    - **[Kismet](https://www.kismetwireless.net/docs/)**: a wireless-network detector, sniffer, and monitoring system
- **[Wireshark](https://www.wireshark.org/docs/wsug_html_chunked/)**: a GUI packet analyzer for network troubleshooting
    - **[`tshark`](https://www.wireshark.org/docs/man-pages/tshark.html)**: the command-line version of Wireshark
- **[Zeek](https://docs.zeek.org/en/master/)**: an open-source network security monitor that produces detailed traffic logs

## Offensive Security (Red Team)
- **[BloodHound](https://github.com/SpecterOps/BloodHound)**: a tool for mapping attack paths in Active Directory environments
- **Bug Bounty Programs**
    - **[HackerOne](https://www.hackerone.com/)**: a bug bounty platform connecting ethical hackers with companies
    - **[Open Bug Bounty](https://www.openbugbounty.org/)**: a platform for reporting web vulnerabilities through coordinated disclosure
- **[Metasploit Framework](https://docs.metasploit.com/)**: a platform for developing, testing, and executing exploits
- **[NetExec](https://www.netexec.wiki/)**: a tool for assessing and automating attacks against network services
- **[SearchSploit](https://www.exploit-db.com/searchsploit)**: a command-line interface for searching the Exploit Database
- **Social Engineering**
    - **Phishing**
        - **[Berkeley Phish Tank](https://security.berkeley.edu/phish-tank)**: a collection of real phishing examples and guidance from UC Berkeley
        - **[NIST You’ve Been Phished](https://www.nist.gov/video/youve-been-phished)**: an educational video explaining why users fall for phishing messages
    - **[Professor Messer Social Engineering Videos](https://www.professormesser.com/network-plus/n10-009/n10-009-video/social-engineering-n10-009/)**: free educational videos on social-engineering attacks
- **Spoofing**
    - **[Responder](https://github.com/lgandx/Responder)**: a tool for capturing authentication attempts through poisoned name-resolution responses

## Open Source Intelligence (OSINT)
- **Data Brokers**
    - **[Names Directory](https://namesdir.com/)**: a people-search directory for finding public identity information
    - **[ThatsThem](https://thatsthem.com/)**: a people-search service that can associate usernames with public records
- **[Maltego](https://docs.maltego.com/)**: a graphical platform for mapping relationships between public information
- **Piracy**
    - **[The Pirate Bay](https://en.wikipedia.org/wiki/The_Pirate_Bay)**: a popular torrent index site for sharing files
- **Querying**
    - **[GitHub User](https://api.github.com/users/%3Cusername%3E/events/public)**: a manual query for a specific GitHub user’s public activity
    - **[Proton Mail Domains](https://api.protonmail.ch/pks/lookup?op=index&search=%3Cemail_address%3E)**: a manual query for Proton Mail addresses using a domain
    - **[Proton Mail Users](https://api.protonmail.ch/pks/lookup?op=index&search=%3Cusername%3E@protonmail.com)**: a manual query for a public Proton Mail username
    - **[Tinder Usernames](https://tinder.com/@%3Cusername%3E)**: a manual lookup for public Tinder profiles associated with a username
- **[Recon-ng](https://github.com/lanmaster53/recon-ng)**: a modular framework for conducting web-based reconnaissance
- **Search Engine**
    - **[FootprintIQ](https://footprintiq.app/)**: a platform for locating usernames and analyzing digital footprints
    - **[GitFive](https://github.com/mxrch/GitFive)**: a tool for gathering public intelligence about GitHub users
    - **[Google Reverse Image Search](https://lens.google/)**: finds similar images and their sources
    - **[Lullar](https://com.lullar.com/)**: a search tool for finding online accounts associated with usernames or email addresses
    - **[NameCheckup](https://namecheckup.com/)**: a web tool for checking usernames across websites and domain extensions
    - **[Namechk](https://namechk.com/)**: a web tool for checking username and domain availability
    - **[PullPush Reddit Search](https://search.pullpush.io/)**: searches archived Reddit posts and comments
    - **[Sherlock](https://github.com/sherlock-project/sherlock)**: a command-line tool for finding accounts with a username across social networks
    - **[Sylva Identity Discovery](https://sylva.pfeister.dev/)**: a tool for connecting online identities with possible real-world identities
    - **[WhatsMyName](https://github.com/WebBreacher/WhatsMyName)**: a community-maintained dataset for checking usernames across hundreds of websites
    - **[WhatsMyName Web](https://whatsmyname.app/)**: a browser-based interface for finding accounts associated with a username
    - **[Yandex](https://yandex.com/images/)**: a Russian search engine with image and web search features
- **Search-Engine Dorking**
    - **Google Dorking (Google Hacking)**
        - **[Amazon Usernames](https://www.google.com/search?q=site:amazon.com+%3Cusername%3E)**: a manual search for public Amazon profiles
        - **[Hidden Reddit Posts](https://www.google.com/search?q=site:reddit.com+%3Cusername%3E)**: a manual search for hidden Reddit posts
- **[theHarvester](https://github.com/laramies/theHarvester)**: a tool for gathering public emails, subdomains, hosts, and employee names
  
## Operating Systems
- **[Android Automatic Updates](https://support.google.com/android/answer/7680439)**: guidance for automatically updating Android devices
- **[Apple iOS Automatic Updates](https://support.apple.com/en-us/118575)**: guidance for automatically updating iOS devices
- **[TempleOS](https://templeos.org/)**: a lightweight biblical-themed operating system created entirely by Terry A. Davis
- **Terminal**
    - **[MobaXterm](https://mobaxterm.mobatek.net/documentation.html)**: a Windows terminal and remote-access suite supporting SSH, SFTP, X11, and Unix commands
    - **Shell**
        - **[Bash (Bourne Again Shell)](https://www.gnu.org/software/bash/manual/)**: a Unix shell and scripting language commonly used on Linux
        - **[PowerShell](https://learn.microsoft.com/en-us/powershell/)**: a cross-platform command shell and scripting language built around structured objects
        - **[Windows Command Prompt](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)**: the traditional Windows command-line interpreter for executing commands and batch scripts
        - **[Zsh (Z Shell)](https://zsh.sourceforge.io/Doc/)**: a Unix shell with advanced customization, completion, and interactive features
- **Unix**
    - **BSD**
        - **[FreeBSD](https://docs.freebsd.org/en/books/handbook/)**: a Unix-like operating system known for performance and permissive licensing
            - **[DragonFly BSD](https://www.dragonflybsd.org/docs/)**: a Unix-like operating system focused on performance and scalable file systems
            - **[HardenedBSD](https://hardenedbsd.org/)**: a fork of FreeBSD focused on security hardening
        - **[NetBSD](https://www.netbsd.org/docs/guide/en/)**: a unified, multi-platform, production-quality Unix-like operating system
            - **[OpenBSD](https://www.openbsd.org/faq/)**: a 1995 fork of NetBSD focused heavily on security and networking
    - **[Darwin](https://opensource.apple.com/)**: Apple’s open-source Unix-based operating-system foundation
        - **[macOS](https://support.apple.com/guide/mac-help/welcome/mac)**: Apple’s Unix-certified desktop operating system built on Darwin
            - **[Apple macOS Application-Removal Instructions](https://support.apple.com/en-us/102610)**: Apple guidance for uninstalling applications from macOS
            - **[Apple macOS Automatic Updates](https://support.apple.com/HT201541)**: guidance for automatically updating macOS
            - **[Microsoft Office Automatic Updates for macOS](https://support.microsoft.com/en-us/office/update-office-for-mac-automatically-bfd1e497-c24d-4754-92ab-910a4074d7c1)**: Microsoft guidance for automatically updating Office on macOS
    - **Linux**
        - **Arch Family**
            - **[BlackArch Linux](https://blackarch.org/guide.html)**: a security-focused Arch-based distribution
            - **[Manjaro](https://wiki.manjaro.org/)**: a user-friendly Arch-based distribution with curated software updates
        - **Debian Family**
            - **[Kali Linux](https://www.kali.org/docs/)**: a penetration-testing-focused Debian derivative
            - **[Parrot OS](https://parrotsec.org/docs/)**: a security-oriented Debian-based distribution
            - **[Tails](https://tails.net/doc/)**: a live operating system designed for anonymity
            - **[Ubuntu](https://help.ubuntu.com/)**: a popular user-friendly Debian derivative
                - **[Linux Mint](https://linuxmint.com/documentation.php)**: a free, user-friendly, and highly stable desktop operating system
                - **[Lubuntu](https://manual.lubuntu.me/)**: a lightweight official flavor of Ubuntu
                    - **[DragonOS](https://sourceforge.net/projects/dragonos-focal/)**: an SDR-focused Linux distribution
                - **[Pop!_OS](https://support.system76.com/)**: an Ubuntu-based distribution designed for productivity, gaming, and development
            - **[Whonix](https://www.whonix.org/wiki/Documentation)**: a privacy-focused operating system that isolates traffic through Tor
        - **Gentoo Family**
            - **[Gentoo Linux](https://wiki.gentoo.org/wiki/Handbook:Main_Page)**: a source-based distribution offering extensive control and optimization
        - **[Linux Man Pages](https://linux.die.net/)**: an online reference of Linux manual pages
        - **Qubes OS Family**
            - **[Qubes OS](https://www.qubes-os.org/doc/)**: a security-focused operating system that isolates activities within virtual machines
        - **Red Hat Family**
            - **[Fedora](https://docs.fedoraproject.org/)**: a cutting-edge community distribution sponsored by Red Hat
            - **[RHEL (Red Hat Enterprise Linux)](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/)**: Red Hat’s enterprise Linux distribution with commercial support
                - **[CentOS](https://docs.centos.org/)**: a community project centered on the development stream leading to RHEL
        - **SUSE Family**
            - **[openSUSE](https://doc.opensuse.org/)**: a community distribution available in rolling and stable editions
            - **[SLES (SUSE Linux Enterprise Server)](https://documentation.suse.com/sles/)**: an enterprise-grade server operating system designed for mission-critical workloads
- **Virtualization**
    - **Hypervisors**
        - **[QEMU](https://www.qemu.org/docs/master/)**: an open-source tool for machine emulation and virtualization
        - **[VirtualBox](https://www.virtualbox.org/manual/)**: Oracle’s free, cross-platform desktop hypervisor
        - **[VMware](https://www.vmware.com/)**: a family of commercial virtualization and cloud-computing products
        - **[Xen](https://xenproject.org/)**: an open-source type-1 hypervisor for running isolated virtual machines
    - **[WSL (Windows Subsystem for Linux)](https://learn.microsoft.com/en-us/windows/wsl/)**: a Windows feature for running Linux environments without a VM
- **Windows NT Family**
    - **[Microsoft Windows](https://learn.microsoft.com/en-us/windows/)**: Microsoft’s proprietary family of desktop operating systems
        - **[CIS Microsoft Windows Cyber Hygiene Guide](https://www.cisecurity.org/insights/white-papers/cis-controls-microsoft-windows-10-cyber-hygiene-guide)**: CIS guidance for improving foundational Windows security
        - **[Microsoft Supported Windows Lifecycle Information](https://learn.microsoft.com/en-us/lifecycle/products/?products=windows)**: Microsoft’s support and end-of-life information for Windows releases
        - **[Windows Application-Removal Instructions](https://support.microsoft.com/en-us/windows/uninstall-or-remove-apps-and-programs-in-windows-4b55f974-2cc6-2d2b-d092-5905080eaf98)**: Microsoft guidance for uninstalling Windows applications
        - **[Windows Automatic Updates](https://support.microsoft.com/help/311047)**: Microsoft guidance for automatically installing Windows updates
    - **[Windows Server](https://learn.microsoft.com/en-us/windows-server/)**: Microsoft’s operating-system family for servers and enterprise infrastructure
- **[Wine](https://www.winehq.org/)**: a compatibility layer for running Windows applications on Unix-like systems

## Password Cracking
- **Brute-Force Attack**
    - **[Hydra](https://github.com/vanhauser-thc/thc-hydra)**: a tool for testing credentials against network authentication services
- **Dictionary Attack**
    - **[CeWL](https://github.com/digininja/CeWL)**: a tool that generates custom wordlists from website content
    - **[rockyou.txt](https://www.kali.org/tools/wordlists/)**: a famous password wordlist included with Kali’s default wordlists package
    - **[SecLists](https://github.com/danielmiessler/seclists)**: an installable Kali package containing password, username, discovery, and fuzzing lists
- **[Hashcat](https://hashcat.net/wiki/)**: a password-recovery tool that uses CPUs and GPUs to crack password hashes
- **Hashing**
    - **SHA-256 (Secure Hash Algorithm 256-bit)**
        - **[`sha256sum`](https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html)**: a command-line utility that calculates and verifies SHA-256 file hashes
- **[John the Ripper](https://www.openwall.com/john/doc/)**: a password-recovery tool that detects and cracks numerous hash formats
    - **[PDF2John](https://github.com/openwall/john/tree/bleeding-jumbo/run)**: a utility that extracts password hashes from encrypted PDF files for use with John the Ripper
- **Mask Attack**
    - **[Crunch](https://sourceforge.net/projects/crunch-wordlist/)**: a tool that generates wordlists from specified character patterns
- **Rainbow Table Attack**
    - **[Ophcrack](https://ophcrack.sourceforge.io/)**: a password-recovery tool that uses rainbow tables to crack Windows LM and NTLM password hashes

## Physical Security & Internet of Things (IoT)
- **[ALFA Wi-Fi Adapter](https://docs.alfa.com.tw/)**: an external wireless adapter commonly used for Wi-Fi monitoring and security testing
- **[Bus Pirate Kit](https://docs.buspirate.com/)**: a hardware interface for communicating with and debugging electronic buses and chips
- **[CatSniffer](https://github.com/ElectronicCats/CatSniffer)**: a wireless security tool for monitoring and analyzing IoT radio protocols
- **Embedded Systems**
    - **Firmware**
        - **[ESP32 Marauder](https://github.com/justcallmekoko/ESP32Marauder/wiki)**: Wi-Fi and Bluetooth security-testing firmware for compatible ESP32 boards
        - **[FreshTomato](https://wiki.freshtomato.org/)**: open-source replacement firmware for supported wireless routers
    - **GPIO Board**
        - **[Raspberry Pi](https://www.raspberrypi.com/documentation/computers/raspberry-pi.html)**: a single-board computer with GPIO support for hardware and networking projects
    - **Microcontroller**
        - **[D1 Mini ESP8266](https://www.wemos.cc/en/latest/d1/d1_mini.html)**: a compact Wi-Fi microcontroller development board
        - **[M5Stack Cardputer Adv Version](https://docs.m5stack.com/en/core/Cardputer-Adv)**: a portable ESP32-S3 development device
        - **[Raspberry Pi Pico](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html)**: a low-cost microcontroller development board
        - **[Wi-Fi Devboard for Flipper Zero](https://developer.flipper.net/flipperzero/doxygen/dev_board.html)**: an ESP32-S2 development board that adds Wi-Fi and debugging
- **Hardware Keylogger**
    - **[Keelog KeyGrabber USB Keylogger](https://keelog.com/docs/keygrabber-usb-users-guide/)**: a USB hardware keylogger placed between a keyboard and computer
- **Hardware Security Key**
    - **[FEITIAN Security Key](https://fido.ftsafe.com/guide-2/)**: a hardware authenticator manufactured by FEITIAN
    - **[Google Titan Security Key](https://support.google.com/titansecuritykey/)**: Google’s hardware security-key product line
    - **[Yubico YubiKey](https://docs.yubico.com/)**: Yubico’s hardware security-key product line
        - **[`ykman` (YubiKey Manager)](https://docs.yubico.com/software/yubikey/tools/ykman/)**: used to configure YubiKey apps such as OTP, FIDO, PIV, and OpenPGP
- **[HP EliteDesk 800 G2 SFF](https://shorturl.at/mWctg)**:  i5-6500 @ 3.2GHz 8GB RAM 240GB SSD Linux Mint 22
- **[HP ProDesk 600 G2 SFF](https://shorturl.at/Lb6w3)**:  i5-6500 @ 3.2GHz 8GB RAM 240GB SSD Linux Mint 22
- **[LAN Turtle](https://documentation.hak5.org/lan-turtle/)**: a covert USB network adapter used for authorized remote access and network assessments
- **Network Hardware**
    - **Network TAP (Test Access Point)**
        - **[Profitap ProfiShark 1G](https://www.profitap.com/wp-content/uploads/ProfiShark-1G-Manual.pdf)**: a portable Gigabit Ethernet network TAP used to capture traffic
    - **Router**
        - **[ASUS](https://www.asus.com/support/)**: a manufacturer of consumer and business networking equipment
        - **[Netgear](https://www.netgear.com/support/)**: a manufacturer of routers, switches, and other networking equipment
        - **[RouterSploit](https://github.com/threat9/routersploit)**: a framework for testing routers and embedded devices for vulnerabilities
        - **[TP-Link](https://www.tp-link.com/us/support/)**: a manufacturer of consumer and business networking equipment
- **Physical Access Control**
    - **RFID (Radio-Frequency Identification)**
        - **[Chameleon Ultra](https://github.com/RfidResearchGroup/ChameleonUltra/wiki)**: an RFID and NFC research device for reading, emulating, and analyzing supported cards
        - **[ESP RFID Tool](https://github.com/rfidtool/ESP-RFID-Tool)**: an ESP-based tool for testing RFID systems that use Wiegand interfaces
        - **[iCopy-XS](https://www.icopyx.co.uk/Instructions.pdf)**: a portable RFID reader and writer used for analyzing compatible access cards
        - **[Proxmark3 RDV4](https://github.com/RfidResearchGroup/proxmark3/)**: an advanced device for researching low- and high-frequency RFID systems
            - **[PM3 BLE Module](https://proxmark.com/proxmark-3-hardware/proxmark-3-rdv4)**: a Bluetooth Low Energy expansion module for the Proxmark3 RDV4
            - **[PM3 HF Antenna Set](https://proxmark.com/proxmark-3-hardware/proxmark-3-rdv4)**: high-frequency antennas for Proxmark3 RFID testing
            - **[PM3 LF Antenna Set](https://proxmark.com/proxmark-3-hardware/proxmark-3-rdv4)**: low-frequency antennas for Proxmark3 RFID testing
- **Programmable USB Device**
    - **[FaceDancer21](https://facedancer.readthedocs.io/)**: a development board for emulating USB devices and testing USB hosts
    - **[Raspberry Pi Pico BadUSB](https://github.com/dbisu/pico-ducky)**: a Raspberry Pi Pico configured to emulate a USB keyboard
    - **[USB Nugget](https://github.com/RetiaLLC/USB-Nugget)**: a programmable security-testing device capable of emulating USB peripherals
    - **[USB Rubber Ducky](https://documentation.hak5.org/hak5-usb-rubber-ducky/)**: a programmable USB device that impersonates a keyboard to execute scripted keystrokes
- **Radio Hardware**
    - **[Crazyradio PA](https://www.bitcraze.io/documentation/repository/crazyradio-firmware/master/)**: a long-range USB radio dongle for compatible 2.4 GHz devices
    - **[Flipper Zero](https://docs.flipper.net/zero)**: a portable device for exploring radio, access-control, infrared, and hardware systems
    - **SDR (Software-Defined Radio)**
        - **[GNU Radio](https://www.ettus.com/sdr-software/gnu-radio/)**: free software development framework that provides signal processing functions for SDR
        - **[HackRF One](https://hackrf.readthedocs.io/en/stable/hackrf_one.html)**: a half-duplex SDR capable of transmitting and receiving a broad range of frequencies
            - **[PortaPack H2 Kit](https://github.com/portapack-mayhem/mayhem-firmware/wiki)**: gives the HackRF One a display and portable controls
        - **[KrakenSDR Kit](https://github.com/krakenrf/krakensdr_docs/wiki)**: a five-channel SDR receiver used for radio direction finding and beamforming
        - **[RTL-SDR](https://www.rtl-sdr.com/rtl-sdr-quick-start-guide/)**: an inexpensive SDR receiver used to explore radio signals
- **Surveillance System**
    - **CCTV (Closed-Circuit Television)**
        - **[Cameradar](https://github.com/Ullaakut/cameradar)**: a tool for discovering and assessing RTSP surveillance-camera systems
- **[USB Armory Mk II](https://github.com/usbarmory/usbarmory/wiki/Mk-II-Introduction)**: a compact Linux computer designed for security, networking, and embedded applications
- **[WiFi Nugget](https://github.com/tom4ta/WiFi-Nugget)**: a portable device for learning about and testing Wi-Fi security

## PWN
- **Concolic Execution**
    - **[CO3](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-changming)**: a concolic execution system combining real microcontroller execution with workstation-based constraint solving
- **Dynamic Analysis (Binary Exploitation)**
    - **Debugger**
        - **[GDB (GNU Debugger)](https://sourceware.org/gdb/documentation/)**: a debugger for inspecting and controlling programs during execution
            - **[pwndbg](https://github.com/pwndbg/pwndbg)**: a GDB and LLDB plug-in that makes debugging suck less
- **Emulation**
    - **[AIM (Automatic Interrupt Modeling)](https://arxiv.org/abs/2312.01195)**: a system that automatically models interrupts for dynamic firmware analysis
- **Exploit**
    - **Race Condition**
        - **[SDRacer](https://arxiv.org/abs/2305.17869)**: a system for detecting, validating, and repairing race conditions in interrupt-driven embedded software
- **Exploit Development**
    - **[pwntools](https://docs.pwntools.com/)**: a Python framework for developing exploits and interacting with binaries
- **Fuzzing**
    - **[AidFuzzer](https://www.usenix.org/conference/usenixsecurity25/presentation/wang-jianqiang)**: an adaptive firmware fuzzer that models runtime states to trigger interrupts correctly
    - **[Fuzzware](https://github.com/fuzzware-fuzzer/fuzzware)**: a hardware-free platform for emulating and fuzzing embedded firmware
    - **[HD-Fuzz](https://www.sciencedirect.com/science/article/abs/pii/S1084804524000122)**: a hardware-dependency-aware firmware fuzzer using hybrid MMIO modeling
- **Static Analysis (Reverse Engineering)**
    - **[Binary Ninja](https://docs.binary.ninja/)**: a commercial reverse-engineering platform for analyzing compiled binaries
    - **[BinSync](https://binsync.net/)**: an open-source Git-based collaboration framework for synchronizing RE analysis across multiple decompilers
    - **Decompiler**
        - **[DecBench](https://decbench.com/)**: an open-source living benchmark for decompilers created by the Noelo Lab at UGA
        - **[Kuna](https://kuna.noelo.org/)**: a Rust-based decompiler, derived from Ghidra, for fast binary decompilation and AI-assisted reverse engineering
    - **[Ghidra](https://github.com/NationalSecurityAgency/ghidra)**: an open-source reverse-engineering suite developed by the NSA
    - **[Hopper](https://www.hopperapp.com/)**: a commercial disassembler and decompiler primarily used for macOS, Linux, and iOS applications
    - **[IDA Pro](https://docs.hex-rays.com/)**: a commercial disassembler and debugger for reverse engineering binaries
    - **[Operation Mango](https://www.usenix.org/conference/usenixsecurity24/presentation/gibbs)**: a static-analysis system for finding taint-style vulnerabilities in Linux-based firmware
    - **[radare2](https://book.rada.re/)**: an open-source framework for reverse engineering and binary analysis
    - **[REA (Reverse Engineer Anything)](https://github.com/morluto/rea)**: an AI-agent toolkit using CLI and MCP to analyze binaries, apps, and runtime behavior
- **Symbolic Execution**
    - **[angr](https://docs.angr.io/)**: a Python framework for binary analysis and symbolic execution
    - **[FIE on Firmware](https://www.usenix.org/conference/usenixsecurity13/technical-sessions/paper/davidson)**: a symbolic-execution platform for finding vulnerabilities in MSP430 firmware
        
## Scanning and Reconnaissance
- **ASM (Attack Surface Management)**
    - **[Armada](https://risk3sixty.com/secure/attack-surface-management)**: risk3sixty’s offensive security and attack surface management platform
- **Enumeration**
    - **DNS Enumeration**
        - **[Amass](https://github.com/owasp-amass/amass)**: a tool for discovering subdomains and mapping external attack surfaces
        - **[DNSRecon](https://github.com/darkoperator/dnsrecon)**: a tool for enumerating DNS records and configurations
    - **[Enum4linux-ng](https://github.com/cddmp/enum4linux-ng)**: a tool for enumerating information from Windows and Samba systems
- **Internet-Wide Scanning**
    - **[GreyNoise](https://docs.greynoise.io/)**: a threat-intelligence platform that identifies internet-wide scanning activity
    - **Internet Asset Search Engine**
        - **[Censys](https://censys.com/)**: an internet-wide search engine for hosts, services, and certificates
        - **[Insecam](https://en.wikipedia.org/wiki/Insecam)**: an index of publicly accessible and unsecured CCTV streams
        - **[Shodan](https://help.shodan.io/)**: a search engine for internet-connected devices and services
        - **[ZoomEye](https://www.zoomeye.ai/)**: an internet asset search engine developed in China
    - **[ZMap](https://github.com/zmap/zmap)**: a high-speed scanner designed for internet-wide network surveys
- **Network Scanning**
    - **[Fing](https://www.fing.com/)**: a network scanner for discovering and identifying connected devices
    - **[Nmap](https://nmap.org/book/man.html)**: a network scanner for discovering hosts, ports, services, and operating systems
        - **[Nmap Scripting Engine](https://nmap.org/book/nse.html)**: Nmap functionality that uses scripts for discovery, vulnerability detection, and network testing
        - **[Zenmap](https://nmap.org/zenmap/)**: a graphical interface for configuring and reviewing Nmap scans
- **Vulnerability Scanning**
    - **[Nikto](https://github.com/sullo/nikto)**: an open-source scanner for identifying web-server vulnerabilities and misconfigurations
    - **[Nuclei](https://github.com/projectdiscovery/nuclei)**: a template-based scanner for detecting known vulnerabilities and exposures
    - **[Tenable Nessus](https://docs.tenable.com/nessus/)**: a vulnerability scanner that identifies software flaws, exposed services, and misconfigurations

## Web Exploitation
- **[Burp Suite](https://portswigger.net/burp/documentation)**: a web-security testing platform for intercepting and modifying HTTP traffic
- **Cross-Site Scripting (XSS)**
    - **[BeEF (Browser Exploitation Framework)](https://github.com/beefproject/beef)**: a framework for testing security weaknesses through web browsers
- **[ffuf](https://github.com/ffuf/ffuf)**: a fast web fuzzer for discovering hidden files, directories, and parameters
- **[Gobuster](https://github.com/OJ/gobuster)**: a tool for discovering web paths, DNS names, and virtual hosts
- **[OWASP Top 10](https://owasp.github.io/www-project-top-ten/)**: the ten most critical web application security risks
- **[Postman](https://learning.postman.com/docs/)**: an API platform for creating, sending, and testing HTTP requests
- **SQL Injection (SQLi)**
    - **[sqlmap](https://sqlmap.org/)**: a tool for detecting and testing SQL-injection vulnerabilities
- **[WhatWeb](https://github.com/urbanadventurer/WhatWeb)**: a tool for identifying technologies used by websites
- **[WPScan](https://github.com/wpscanteam/wpscan)**: a security scanner designed for WordPress websites
- **[ZAP (Zed Attack Proxy)](https://www.zaproxy.org/docs/)**: an open-source platform for testing web-application security

## TODO
* Add a Table of Contents
* [CIS Benchmarks](https://learn.cisecurity.org/benchmarks): CIS best-practice security configuration guides for a bunch of resoures
* [GeoSpy](https://geospy.ai/): an AI-powered tool for estimating the geographic location of photos
* [dCode](https://www.dcode.fr/en): a collection of tools for solving ciphers, codes, puzzles, and mathematical problems
* [AES Encryption/Decryption](https://www.devglan.com/online-tools/aes-encryption-decryption): an online tool for encrypting and decrypting data using AES
* [CyberChef](https://gchq.github.io/CyberChef/): a web application for encoding, decoding, encryption, compression, and data analysis
* [Omni Calculator – RSA Calculator](https://www.omnicalculator.com/math/rsa): an online calculator demonstrating RSA key generation, encryption, and decryption
* [JAB Code](https://jabcode.org/): a color barcode format capable of storing large amounts of data
* [JSFuck](https://jsfuck.com/): encodes JavaScript using only six different characters
* [de4js](https://lelinhtinh.github.io/de4js/): an online JavaScript deobfuscation and unpacking tool
* [VulnHub](https://www.vulnhub.com/): downloadable vulnerable virtual machines for cybersecurity practice
* [Claude Mythos Preview](https://www.anthropic.com/research/mythos-preview): Anthropic’s research model for evaluating advanced cybersecurity capabilities
* [Friendly Hacker Resources](https://docs.google.com/spreadsheets/d/1SVm4Bu-L6eiyXlN8Kf_fszWeP1VSLNuVOJ-SguS9qtI/edit?gid=16563866#gid=16563866)
* [Google Dorking](https://en.wikipedia.org/wiki/Google_hacking)
* [Hak5 Documentation (Ask AI for Best Tools)](https://documentation.hak5.org/hak5-docs)
* [National Cyber League Resource](https://github.com/jfisher009/NationalCyberLeagueResource)
* [HackTrix](https://hacktricks.wiki/en/network-services-pentesting/pentesting-web/web-api-pentesting.html)
* [./ncl-tools](https://lydia-england.github.io/ncl-tools/)
* [OSINT Framework (Beyond Username)](https://osintframework.com/): a web-based directory that organizes free OSINT tools and resources by investigation type
* [OSINT Tools](https://outlookuga.sharepoint.com/sites/InfoSec_KB/SitePages/OSINT-Tools.aspx?e=4%3a22b65a4624904fcb9f87841894226051&web=1&sharingv2=true&fromShare=true&at=9&CT=1781544543014&OR=OWA-NT-Mail&CID=28f0a04c-959b-d2df-24fe-5bce3bdfaea2&SI=NonSentItems)
* [Shellphish Repositories](https://github.com/orgs/shellphish/repositories)
* [The Hack Pack Resources](https://thehackpack.org/resources/intro/ )
* [Awesome Security Newsletters](https://github.com/TalEliyahu/awesome-security-newsletters)
* [Randar2](https://github.com/spawnmason/randar-explanation)
* [GitHub Repo Watchlist](https://github.com/stars/thespcrewroy/lists/my-repo-watchlist)
* Orrin Adotavi ADP Stack
* CIS Controls Tools
* Security+ Terms and Definitions
* Speaker Events
* Club Events
* Course Quizlets
* Tutorial Repos (for terms, but any links to other resources/tools especially)
* [CTF Challenges](https://drive.google.com/drive/u/1/folders/11jv6QYFiSfn1BxVJy5EGRm5xSbBiKGui)
* [Student Discounts](https://docs.google.com/document/d/1uKuvSKlZcADBmoY-O5sF5rBQE6kMSPbRxr7UpVni1f8/edit?tab=t.5lo6aln59n65)
* Hemant Gautum Darkweb Links (prepare for PwnSec and OSINT hackpack presentation)
* Take the finished list and add it to thehackpack website (make it in the style of [OSINT Framework](https://github.com/lockfale/osint-framework) and/or [HackTricks](https://github.com/HackTricks-wiki/hacktricks))

<p align="right"><a href="#top">🔼 Back to top</a></p>
</small>
