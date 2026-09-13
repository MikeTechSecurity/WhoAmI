<div align="center">

<img src="assets/linkedin-cover.jpg" alt="MikeTechSecurity LinkedIn cover" width="100%" />

# WhoAmI

## MikeTechSecurity

**Endpoint Security • Cybersecurity Operations • Network Security • Cloud Administration • Homelab • Automation**

[![Website](https://img.shields.io/badge/Website-miketechsecurity.com-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://miketechsecurity.com/)
[![GitHub](https://img.shields.io/badge/GitHub-MikeTechSecurity-181717?style=for-the-badge&logo=github)](https://github.com/MikeTechSecurity)
[![YouTube](https://img.shields.io/badge/YouTube-MikeTechSecurity-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@MiketechSecurity)
[![TikTok](https://img.shields.io/badge/TikTok-@MikeTechSecurity-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@miketechsecurity)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-MikeTechSecurity-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/MiketechSecurity)

</div>

---

## About Me

Cybersecurity and endpoint-management professional focused on **endpoint security, EDR/XDR operations, incident response, identity, device management, cloud administration, and defensive security**.

In my professional environment, I work with technologies including **Cortex XDR, Bitdefender, Microsoft Defender for Endpoint, Microsoft Intune, Entra ID, SCCM/MECM, Active Directory, Group Policy, MFA, Conditional Access, Microsoft 365, Google Workspace, and Proofpoint**.

Outside of work, I build and document a practical cybersecurity homelab centered on **pfSense, VLAN segmentation, Pi-hole, Proxmox, Linux, network monitoring, and security automation**.

My approach is simple:

> **Build it. Secure it. Test it. Document it. Improve it.**

---

## Current Focus

- 🔐 Endpoint security, EDR/XDR operations, and incident response
- 🧭 Threat investigation, malware remediation, and device isolation
- 🖥️ Microsoft Intune, Entra ID, SCCM/MECM, Active Directory, and Conditional Access
- ☁️ Microsoft 365, Google Workspace, and cloud administration
- 🧱 pfSense firewall policy and VLAN segmentation
- 🕳️ Pi-hole DNS filtering and group-based network policy
- 🖥️ Proxmox virtualization and isolated lab networking
- 🐧 Linux administration and troubleshooting
- 🐍 Python and PowerShell for utilities and automation
- 📚 Building repeatable documentation from working configurations

---

## Homelab Architecture

```mermaid
flowchart TD
    Internet((Internet))
    FW[pfSense Firewall / Router]
    Trusted[Trusted LAN]
    IoT[IoT Network]
    Lab[Lab / Server Network]
    Guest[Guest / Special-Purpose Network]
    DNS[Pi-hole DNS Filtering]
    PVE[Proxmox]
    NAS[NAS / Storage]
    CCTV[CCTV / Smart Devices]

    Internet --> FW
    FW --> Trusted
    FW --> IoT
    FW --> Lab
    FW --> Guest

    Trusted --> DNS
    IoT --> DNS
    Lab --> DNS
    Guest --> DNS

    Lab --> PVE
    Lab --> NAS
    IoT --> CCTV
```

> Public documentation is intentionally sanitized. Internal addressing, credentials, secrets, and unnecessary implementation details are not published.

---

## Featured Project

### Pi-hole Blocklists

My Pi-hole blocklist project organizes DNS filtering for different network groups, including trusted systems, IoT devices, kids' devices, and other segmented clients.

[![Repository](https://img.shields.io/badge/View_Project-pihole--blocklists-181717?style=for-the-badge&logo=github)](https://github.com/MikeTechSecurity/pihole-blocklists)

Current filtering areas include:

- General advertising and tracker filtering
- Malware and phishing domain protection
- Adult-content filtering
- Gambling filtering
- Social-network filtering
- Search/SafeSearch-related filtering
- DNS/VPN/proxy bypass controls
- A manually maintained **Mike-OWN-List** for custom network blocks

---

## Technology Stack

### Security & Endpoint

![Cortex XDR](https://img.shields.io/badge/Cortex_XDR-Endpoint_Security-005571?style=flat-square)
![Microsoft Defender](https://img.shields.io/badge/Microsoft_Defender_for_Endpoint-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Bitdefender](https://img.shields.io/badge/Bitdefender-EDR%2FAV-D71920?style=flat-square)
![Proofpoint](https://img.shields.io/badge/Proofpoint-Email_Security-000000?style=flat-square)
![Incident Response](https://img.shields.io/badge/Incident_Response-Defensive_Security-B22222?style=flat-square)

### Identity, Endpoint & Cloud

![Intune](https://img.shields.io/badge/Microsoft_Intune-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-512BD4?style=flat-square&logo=microsoftazure&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=windows&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)
![Google Workspace](https://img.shields.io/badge/Google_Workspace-4285F4?style=flat-square&logo=google&logoColor=white)

### Network & Homelab

![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)
![Pi-hole](https://img.shields.io/badge/Pi--hole-96060C?style=flat-square&logo=pihole&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VLAN](https://img.shields.io/badge/VLAN-Segmentation-005571?style=flat-square)

### Code & Tooling

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## Projects & Labs

| Project | Focus | Status |
|---|---|---|
| [Pi-hole Blocklists](https://github.com/MikeTechSecurity/pihole-blocklists) | DNS filtering and group-based network policy | 🟢 Active |
| Endpoint Security Lab | EDR/XDR, alert investigation, malware remediation | 🟡 In progress |
| pfSense Homelab | Firewall rules, aliases, VLANs, DNS enforcement | 🟡 In progress |
| Proxmox Lab | Virtual networking, isolated lab segments, VM testing | 🟡 In progress |
| Security Automation | Python and PowerShell admin/security workflows | 🔵 Expanding |

---

## Security Principles

```text
SEGMENT      -> Do not place every device on one flat network.
LEAST ACCESS -> Allow only the traffic a network or device actually needs.
CONTROL DNS  -> Keep DNS predictable, observable, and policy-driven.
LOG & VERIFY -> Check what actually happened instead of assuming a rule worked.
BACK UP      -> Configuration backups are part of security.
DOCUMENT     -> A secure system should also be understandable and maintainable.
TEST SAFELY  -> Security testing belongs in systems you own or are authorized to test.
```

---

## Roadmap

- [ ] Publish a sanitized pfSense network architecture guide
- [ ] Document VLAN and firewall-rule design patterns
- [ ] Publish Pi-hole client/group filtering examples
- [ ] Document Proxmox isolated-network lab designs
- [ ] Add endpoint-security and defensive monitoring lab notes
- [ ] Build more Python and PowerShell security/admin utilities
- [ ] Add backup and recovery documentation for core services

---

<div align="center">

### Secure • Protect • Defend

**MikeTechSecurity**

[Website](https://miketechsecurity.com/) • [GitHub](https://github.com/MikeTechSecurity) • [YouTube](https://www.youtube.com/@MiketechSecurity) • [TikTok](https://www.tiktok.com/@miketechsecurity) • [LinkedIn](https://www.linkedin.com/in/MiketechSecurity)

</div>
