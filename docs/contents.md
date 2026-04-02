| [Home](../README.md) |
 | -------------------------------------------- |

# Contents

The **Outbreak Response - Iran-linked Cyber Attacks** solution pack contains the following resources.

## Outbreak Alerts Record Set

| Name | Description |
|:-------------------------|:------------------|
| Iran-linked Cyber Attacks | This report provides an overview of ongoing Iran-linked cyber operations, highlighting activity attributed to state-aligned proxies and hacktivist groups. The vulnerabilities listed are suspected to be exploited by actors associated with Iran in real-world campaigns, consistent with observed tactics, techniques, and procedures (TTPs).

Iran-linked operations continue to rely on distributed, lower-complexity techniques, including phishing, DDoS, data exfiltration, and destructive attacks. Initial access is primarily achieved through exploitation of known, unpatched vulnerabilities and exposed edge infrastructure, reflecting a persistent and opportunistic threat posture targeting government, critical infrastructure, and enterprise environments. |

## Threat Hunt Rules Record set

| Name | Rule Type |
|:-------------------------|:------------------|
| Suspicious Command from Node.Js | Sigma |
| React2Shell CVE-2025-55182 Exploitation Attempt Detection | Sigma |
| Ivanti EPMM CVE-2026-1281/1340 - High-Confidence Pre-Auth RCE Attempt | Sigma |
| Ivanti EPMM CVE-2026-1281/1340 - Suspicious Access to Vulnerable Endpoints (BROAD Hunting) | Sigma |
| Cisco Secure Firewall - Citrix NetScaler Memory Overread Attempt | Sigma |
| Cisco Secure Firewall - Oracle E-Business Suite Exploitation | Sigma |
| Windows Suspicious Child Process from Node.js - React2Shell | Sigma |
| Exploitation Activity of CVE-2025-59287 - WSUS Deserialization | Sigma |
| Suspicious Windows Update Service Child | Sigma |
| CVE-2026-1731 - BeyondTrust - Recon to WebSocket Channel (BROAD) | Sigma |
| Potential JAVA/JNDI Exploitation Attempt | Sigma |
| CVE-2021-44228 - Log4j RCE | Sigma |
| Exploitation Attempt Of CVE-2020-1472 - Execution of ZeroLogon PoC | Sigma |
| Potential CVE-2021-44228 Exploitation Attempt - VMware Horizon | Sigma |
| Oracle E-Business Suite Suspicious File Upload Attempt | Sigma |
| FortiAnalyzer Threat Hunting - Iran-linked Cyber Attacks Event-Handler | Fortinet Fabric |
| CVE-2020-0688 Exploitation via Eventlog | Sigma |
| Log4j RCE CVE-2021-44228 Generic | Sigma |
| Hikvision Web Server Command Injection (CVE-2021-36260) | Sigma |
| CVE-2020-0688 Exchange Exploitation via Web Log | Sigma |
| CVE-2026-1731 - BeyondTrust - Suspicious Shell and Tool Execution on Appliance (BROAD) | Sigma |
| Citrix ADC and Gateway CitrixBleed 2 Memory Disclosure | Sigma |
| Cisco SD-WAN - Low Frequency Rogue Peer | Sigma |
| Exploitation Activity of CVE-2025-59287 - WSUS Suspicious Child Process | Sigma |
| Remote domain controller password reset (Zerologon) | Sigma |
| Cisco Secure Firewall - Oracle E-Business Suite Correlation | Sigma |
| Cisco SD-WAN - Uncommon User-Agent Multi-URI Activity | Sigma |
| CVE-2026-1731 - BeyondTrust - Webshell-like PHP File Creation (STRICT) | Sigma |
| Cisco SD-WAN - Arbitrary File Overwrite Exploitation Activity | Sigma |


 <table><th>NOTE</th><td>These SIGMA and Yara rules are sourced from public community repositories are not independently verified or validated by Fortinet. While community-contributed rules can be valuable for timely threat detection, they may vary in quality, accuracy, and relevance. Fortinet is not responsible for any inaccuracies, errors, or omissions in these rules, nor for any damage or loss that may result from their application. We encourage users to conduct their own validation and adapt these rules as necessary to meet specific security needs and contexts</td></table> 

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| ----------------------------------------- | ------------------------------------------- | --------------------- |