# Paid Cyber Security Tools

Tools without a free tier or free edition. Free and freemium tools live in TOOLS.md.

<details>
<summary>📖 Table of Contents</summary>
<br />

- [Cloud Security](#cloud-security)
- [Cryptography](#cryptography)
- [Defensive Security (Blue Team)](#defensive-security-blue-team)
- [Forensics](#forensics)
- [Log Analysis](#log-analysis)
- [Network Traffic Analysis](#network-traffic-analysis)
- [Offensive Security (Red Team)](#offensive-security-red-team)
- [Open Source Intelligence (OSINT)](#open-source-intelligence-osint)
- [Operating Systems](#operating-systems)
- [Physical Security & Internet of Things (IoT)](#physical-security--internet-of-things-iot)
- [PWN](#pwn)
- [Scanning and Reconnaissance](#scanning-and-reconnaissance)

</details>

## Cloud Security
- **[AWS Config](https://docs.aws.amazon.com/config/)**: records AWS resource configurations and checks them against rules
- **Containerization**
    - **Container Orchestration**
        - **[Red Hat OpenShift](https://docs.redhat.com/en/documentation/openshift_container_platform/4.20/html/overview/ocp-overview)**: an enterprise Kubernetes platform
- **[Cyera](https://www.cyera.com/platform)**: discovers, classifies, and protects sensitive data across cloud, SaaS, and hybrid environments
- **Secrets Management**
    - **[AWS Secrets Manager](https://docs.aws.amazon.com/secretsmanager/)**: stores and rotates AWS credentials and secrets
    - **[Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/)**: Azure’s service for storing secrets, keys, and certificates

## Cryptography
- **Key Management**
    - **[AWS KMS](https://docs.aws.amazon.com/kms/)**: AWS’s managed service for creating and controlling encryption keys
    - **[Google Cloud KMS](https://cloud.google.com/kms/docs)**: GCP’s managed service for creating and controlling encryption keys

## Defensive Security (Blue Team)
- **Access Control**
    - **[CyberArk](https://docs.cyberark.com/)**: an identity-security platform specializing in privileged-access management
    - **[SailPoint](https://documentation.sailpoint.com/)**: an identity-governance platform for managing access, permissions, and identity lifecycles
- **Asset Management**
    - **[Axonius](https://www.axonius.com/)**: cybersecurity asset management and asset intelligence platform
    - **[Spirion](https://www.archtis.com/spirion-platform-overview/)**: a data-discovery and classification platform for locating sensitive information
- **Endpoint Management**
    - **[Microsoft Configuration Manager (formerly SCCM)](https://learn.microsoft.com/en-us/intune/configmgr/)**: an enterprise platform for monitoring endpoint devices
    - **[Microsoft Intune](https://learn.microsoft.com/en-us/intune/intune-service/)**: a cloud platform for managing devices, applications, and endpoint policies
- **GRC (Governance, Risk, and Compliance)**
    - **[CIS Controls](https://www.cisecurity.org/controls)**: best-practice security controls checklist
        - **[CIS SecureSuite Membership](https://www.cisecurity.org/cis-securesuite)**: membership providing access to CIS security tools and resources
        - **[CIS-CAT Pro](https://www.cisecurity.org/cybersecurity-tools/cis-cat-pro)**: automated assessment tool that scans systems and reports their compliance with CIS
    - **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)**: unified data security, governance, and compliance platform
- **Operational Security (OpSec)**
    - **Antivirus/Antimalware**
        - **[McAfee](https://www.mcafee.com/)**: a provider of consumer antivirus and online-protection products
        - **[Norton](https://support.norton.com/)**: a provider of consumer antivirus and online-security products
    - **Secure Email**
        - **[Microsoft 365 Quarantine](https://learn.microsoft.com/en-us/defender-office-365/quarantine-about)**: isolates suspected spam, phishing, malware, etc.
        - **[Private-Mail](https://privatemail.com/)**: a privacy-focused encrypted email service
- **Security Operations**
    - **[Amazon GuardDuty](https://docs.aws.amazon.com/guardduty/)**: AWS’s threat detection service for accounts, workloads, and data
    - **[CrowdStrike Falcon](https://www.crowdstrike.com/en-us/platform/)**: a cloud-native endpoint-protection and threat-detection platform
    - **CTI (Cyber Threat Intelligence)**
        - **[Google Threat Intelligence](https://cloud.google.com/security/products/threat-intelligence)**: combines threat intelligence from Google, Mandiant, and VirusTotal
        - **[Mandiant](https://cloud.google.com/security/mandiant)**: provides threat intelligence, incident response, and managed defense services
        - **[ReversingLabs Spectra Analyze](https://docs.reversinglabs.com/SpectraAnalyze/)**: a malware-analysis and threat-intelligence platform

## Forensics
- **Mobile Forensics**
    - **[Charles Proxy](https://www.charlesproxy.com/)**: commercial HTTP/HTTPS proxy for traffic analysis

## Log Analysis
- **SIEM (Security Information and Event Management)**
    - **[Datadog Cloud SIEM](https://docs.datadoghq.com/security/cloud_siem/)**: a cloud-native platform for detecting and investigating threats using security telemetry
    - **[Google SecOps (formerly Chronicle)](https://docs.cloud.google.com/chronicle/docs/overview)**: Google’s cloud-native SIEM and SOAR platform
    - **[Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/overview)**: Microsoft’s cloud-native SIEM and security orchestration platform

## Network Traffic Analysis
- **[Darktrace](https://www.darktrace.com/)**: an AI-driven security platform that detects anomalous behavior across networks and other environments
- **DNS (Domain Name System)**
    - **[BlueCat Address Manager (formerly Proteus)](https://bluecatnetworks.com/)**: a centralized IP management platform for administering DNS, DHCP, and IP
- **Firewalls**
    - **[AWS Network Firewall](https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html)**: a managed network firewall for filtering and inspecting traffic within Amazon Virtual Private Clouds
    - **[Azure Firewall](https://learn.microsoft.com/en-us/azure/firewall/overview)**: Microsoft Azure’s managed cloud firewall for controlling and inspecting traffic across Azure networks
    - **[Palo Alto Networks Next-Generation Firewalls](https://docs.paloaltonetworks.com/pan-os)**: application-layer firewalls that identify and control traffic
        - **[Panorama](https://docs.paloaltonetworks.com/panorama)**: Palo Alto Networks’ centralized platform for managing multiple firewalls and their security policies
    - **WAF (Web Application Firewall)**
        - **[AWS WAF](https://docs.aws.amazon.com/waf/)**: AWS’s managed web application firewall
        - **[Azure Web Application Firewall](https://learn.microsoft.com/en-us/azure/web-application-firewall/)**: Azure’s managed web application firewall
- **ISP (Internet Service Providers)**
    - **[Starlink](https://www.starlink.com/support)**: a satellite internet service provider
- **VPN (Virtual Private Network)**
    - **[Mullvad](https://mullvad.net/en/help)**: a privacy-focused VPN provider
- **Wifi**
    - **[HPE Aruba Networking](https://arubanetworking.hpe.com/techdocs/ArubaDocPortal/content/docportal.htm)**: a vendor of wireless access points, switches, gateways, and network-management products

## Offensive Security (Red Team)
- **Post-Exploitation**
    - **[Cobalt Strike](https://www.cobaltstrike.com/)**: a commercial adversary-simulation and command-and-control platform for red teams

## Open Source Intelligence (OSINT)
- **Business Records**
    - **[Orbis Directory](https://orbisdirectory.bvdinfo.com/version-2016121/OrbisDirectory/Companies)**: bureau van Dijk's global company database covering 400+ million companies
- **Data Brokers**
    - **[findmypast.com](https://www.findmypast.com/discover)**: UK-focused genealogy and historical records platform
    - **[usa-people-search.com](https://www.usa-people-search.com/)**: US people search and background check service accessing public records
- **Domain Intelligence**
    - **[SEMrush](https://www.semrush.com/)**: SEO intelligence platform for domain analytics, keyword intelligence, backlinks
- **Email Lookup**
    - **[Email to Address](https://www.melissa.com/)**: Melissa.com's data quality and verification service that validates
    - **[MailboxValidator](https://www.mailboxvalidator.com/demo)**: email verification API that validates email deliverability, detects catch-all addresses
    - **[OSINT Industries](https://www.osint.industries/)**: account linking service that extracts all registered accounts tied to an email or phone
- **Evidence Capture**
    - **[ZeeMaps](https://www.zeemaps.com/)**: interactive map creation and sharing tool with unlimited markers, 3-level access control
- **Phone Number Lookup**
    - **[Data24-7](https://www.data24-7.com/signup.php)**: commercial data enrichment provider supporting phone-based identity and risk intelligence lookups
    - **[HLR Lookup Portal](https://www.hlr-lookups.com/en/start)**: HLR lookup service for telecom reachability, network, and carrier status checks
    - **[Next Caller](https://nextcaller.com/)**: caller-identification and spam intelligence service for reverse lookup workflows
    - **[OpenCNAM API](https://api.opencnam.com/v2/phone/+19073372323)**: CNAM lookup API for resolving caller-name metadata from North American numbers
    - **[Twilio Lookup](https://www.twilio.com/lookup)**: twilio API endpoint for phone intelligence including line type, carrier, and validation data
- **Public Records**
    - **[Melissa Data - Property Viewer](https://melissa-data.com)**: commercial property lookup and real estate information provider with verified tax assessor data
    - **[PACER](https://pacer.uscourts.gov/)**: public Access to Court Electronic Records
- **Social Media**
    - **Dating Sites**
        - **[eHarmony](https://www.eharmony.com/)**: personality-based matchmaking platform focused on long-term relationships
- **Transportation Tracking**
    - **[carVertical VIN Decoder](https://www.carvertical.com/vin-decoder)**: international VIN and registration decoder with vehicle history reporting
    - **[Vessel Tracker](https://www.vesseltracker.com/)**: commercial maritime tracking platform combining AIS and satellite feeds
- **WHOIS**
    - **[Domaincrawler.com](https://domaincrawler.com/)**: enterprise-grade domain database covering 1.4+ billion registered and unregistered domains
    - **[MarkMonitor Whois Search](https://domains.markmonitor.com/whois/)**: ICANN-accredited registrar and brand protection company offering WHOIS lookup

## Operating Systems
- **Unix**
    - **Linux**
        - **SUSE Family**
            - **[SLES (SUSE Linux Enterprise Server)](https://documentation.suse.com/sles/)**: an enterprise-grade server OS designed for mission-critical workloads

## Physical Security & Internet of Things (IoT)
- **[Cloud C²](https://documentation.hak5.org/cloud-c2/)**: a self-hosted server for remotely managing deployed Hak5 devices

## PWN
- **Static Analysis (Reverse Engineering)**
    - **[Hopper](https://www.hopperapp.com/)**: a commercial disassembler and decompiler primarily used for macOS, Linux, and iOS applications
    - **[IDA Pro](https://docs.hex-rays.com/)**: a commercial disassembler and debugger for reverse engineering binaries

## Scanning and Reconnaissance
- **ASM (Attack Surface Management)**
    - **[Armada](https://risk3sixty.com/secure/attack-surface-management)**: risk3sixty’s offensive security and attack surface management platform
