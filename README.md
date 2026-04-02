# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

This report provides an overview of ongoing Iran-linked cyber operations, highlighting activity attributed to state-aligned proxies and hacktivist groups. The vulnerabilities listed are suspected to be exploited by actors associated with Iran in real-world campaigns, consistent with observed tactics, techniques, and procedures (TTPs).

Iran-linked operations continue to rely on distributed, lower-complexity techniques, including phishing, DDoS, data exfiltration, and destructive attacks. Initial access is primarily achieved through exploitation of known, unpatched vulnerabilities and exposed edge infrastructure, reflecting a persistent and opportunistic threat posture targeting government, critical infrastructure, and enterprise environments. 

 The **Outbreak Response - Iran-linked Cyber Attacks** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/iran-linked-cyber-attacks) contains information about the outbreak alert **Outbreak Response - Iran-linked Cyber Attacks**. 

## Background: 

The vulnerability landscape is dominated by critical weaknesses in edge infrastructure, enterprise applications, and core identity systems, with active exploitation focused on internet-facing devices and management platforms. High-risk exposure includes remote access solutions (Cisco, Ivanti, Citrix, BeyondTrust) enabling unauthenticated or low-complexity access, alongside enterprise software flaws (Oracle, SmarterMail, React components) that facilitate remote code execution and file upload abuse. 

Additional risk is driven by deserialization vulnerabilities in security and update platforms (Wazuh, WSUS) and privilege escalation issues in Windows and Netlogon, allowing attackers to expand access post-compromise. Legacy but widely exploitable issues such as Log4j and Confluence, along with IoT device weaknesses (Hikvision) and browser-level exploits (Chromium V8), continue to provide scalable entry points. 

Overall, exploitation is opportunistic and volume-driven, relying heavily on unpatched systems and exposed services across the attack surface. Recent breaches confirm that Iran-linked activity is active and operational, with demonstrated capability to:

- Compromise individual accounts
- Disrupt enterprise environments
- Access real-world surveillance infrastructure 

## Announced: 

Continuous intelligence updates, indicators of compromise (IOCs), and mitigation guidance will be provided as new information emerges.
 

## Latest Developments: 

March 31, 2026: FortiGuard Labs published Threat Actor profle of Handala (Iran Linked Group)
https://www.fortiguard.com/threat-actor/6378/handala

March 19, 2026: FortiGuard Labs released Threat Signal related to Handala Wiper Attack. 
https://www.fortiguard.com/threat-signal-report/6383/handala-wiper-attack

March 18, 2026: CISA Urges Endpoint Management System Hardening After Cyberattack Against US Organization
https://www.cisa.gov/news-events/alerts/2026/03/18/cisa-urges-endpoint-management-system-hardening-after-cyberattack-against-us-organization?utm_source=IranHardening202603&utm_medium=GovDelivery 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|