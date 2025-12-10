# 🚨 Incident Response Report
This repository contains a detailed **Blue Team Incident Response Investigation Report** based on a simulated cyber attack against a containerized production network environment. The report documents detection, analysis, containment, and recovery actions following unauthorized reconnaissance and exploitation attempts.
---
## 📌 Project Overview
- **Incident ID:** HarshithC-12072025  
- **Date of Incident:** December 7, 2025  
- **Target System IP:** 192.168.0.196  
- **Attacker IP:** 192.168.0.176  
- **Attack Type:** Network Scanning, FTP Login Attempts, Metasploit Exploitation, HTTP & SSH Probing  
- **Environment:** Docker-Based Metasploitable2 Test Network  
- **Result:** ✅ No successful compromise  
- **Overall Severity:** Medium–Low  

All malicious activity was fully contained, and **no data exfiltration, system modification, or service disruption occurred**.
---
## 📂 Repository Structure
```
incident-response-report/
├── Incident_Response_Report.md     # Full incident response documentation
└── screenshots/                    # Evidence screenshots
    ├── image-1.png
    ├── image-2.png
    ├── image-3.png
    ├── image-4.png
    ├── image-5.png
    └── image-6.png
```
---
## 📄 Report Contents

The full report includes:
- Executive Summary
- Detection and Analysis
- Systems Affected
- Timeline of Attack
- Scope and Impact Assessment
- Containment, Eradication, and Recovery
- Security Recommendations
- Lessons Learned
- Embedded Evidence Screenshots

You can view the full report here:  
➡️ **`Incident_Response_Report.md`**

---
## 🛡️ Security Findings Summary
- Multiple reconnaissance scans detected
- FTP anonymous login attempts blocked
- Metasploit exploitation attempt failed
- SSH authentication probing prevented
- No lateral movement observed
- No malware or backdoor deployed

---
## ⚠️ Legal & Ethical Notice
All testing and analysis were conducted on authorized academic lab systems under controlled conditions.  
This repository is strictly for educational and defensive cybersecurity research.  
No real-world production systems were targeted.

---
## 👤 Author
**Harshith Reddy Chitreddy**  
