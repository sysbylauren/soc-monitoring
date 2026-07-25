# 🛡️ SOC Operations & Threat Hunting (LetsDefend Labs)

## 📌 Repository Overview
This repository documents hands-on Security Operations Center (SOC) investigation workflows, malware analysis, and alert triage completed using the **LetsDefend** platform. Each lab reflects real-world incident response scenarios, detailing initial detection, log analysis, containment strategies, and remediation steps.

---

## 🚀 LetsDefend Investigations & Case Studies

| Case / Lab Title | Category & Tactics | Key Artifacts & Investigation | Write-Up |
| :--- | :--- | :--- | :--- |
| **SOC146: Phishing Mail Detected** | Email Security / Phishing | Header analysis, malicious link extraction, C2 domain IP lookups | [View Write-Up](./lab-01-phishing-investigation/READme.md) |
| **SOC165: Malware Detected** | Endpoint Security / Malware | MD5/SHA256 hashing, VirusTotal analysis, process tree review | [View Write-Up](./lab-02-malware-analysis/READme.md) |
| **SOC170: Password Spraying** | Identity & Access / Auth | Event ID 4625 logs, IP reputation checking, account lockout triage | [View Write-Up](./lab-03-password-spraying/READme.md) |

---

## 🛠️ Tools & Technologies Used
* **SIEM & Log Analysis:** LetsDefend Monitoring Dashboard, Windows Event Viewer
* **Threat Intelligence & OSINT:** VirusTotal, AbuseIPDB, Any.Run, Hybrid Analysis, MXToolbox
* **Endpoint / EDR:** LetsDefend Endpoint Security, Sysmon, Command Line / PowerShell
* **Network & PCAP:** Wireshark, Network Miner

---

## 🎯 Investigation Workflow
1. **Alert Triage:** Review incoming alerts on the LetsDefend Monitoring console and analyze rule conditions.
2. **Data Gathering:** Search endpoint logs, network connections, and process command lines for indicator of compromise (IOC) confirmation.
3. **OSINT Verification:** Check file hashes, domain reputation, and IP addresses against threat intelligence databases.
4. **Containment & Reporting:** Isolate compromised endpoints, request blocklists, complete the LetsDefend playbook, and draft an incident report.


