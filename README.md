# Hi, I'm Felix 👋

### **QA Engineer & Cybersecurity Analyst** · Open to entry-level QA and SOC Analyst roles

I test software and I secure it. As a QA engineer I've designed test plans and built
Playwright and API automation for a multi-tenant ERP platform.

On the security side, I run a self-contained **Active Directory + Wazuh SIEM** home lab where
I attack, detect, investigate, and respond — every attack I launch, I also write the detection
for. All of it documented, all of it built with free tooling on a 16 GB host.

<p align="left">
  <img src="https://img.shields.io/badge/QA-Test%20Automation-0e7490?style=flat-square" alt="QA: Test Automation" />
  <img src="https://img.shields.io/badge/Security-Blue%20Team%20%2F%20SOC-1f6feb?style=flat-square" alt="Security: Blue Team / SOC" />
  <img src="https://img.shields.io/badge/Also-Offensive%20Security-c9302c?style=flat-square" alt="Also: Offensive Security" />
  <img src="https://img.shields.io/badge/Lab-100%25%20Free%20Tooling-2ea44f?style=flat-square" alt="Lab: 100% Free Tooling" />
</p>

---

## 🎯 What I do

| | |
|---|---|
| 🧪 **QA** | Test plan design, manual and exploratory testing, Playwright + TypeScript automation, Postman/Newman API testing, SQL data validation, defect triage |
| 🔴 **Red** | Active Directory attack paths (Kerberoasting, AS-REP Roasting, DCSync, BloodHound), web-app pentesting against the OWASP Top 10, professional reporting |
| 🔵 **Blue** | Detection engineering (Sigma + Wazuh), incident response (NIST lifecycle, timeline reconstruction), threat hunting, log analysis |
| 🟣 **Purple** | I detect the exact attacks I launch — both sides of the same event, in the same lab |

---

## 🧪 QA projects

| Project | What it proves |
|---------|----------------|
| **[ruleguard](https://github.com/manlikefelo/ruleguard)** | A 301-test suite across unit, API and Playwright UI layers, with six defects documented from failure to fix |

---

## 📌 Security projects

> **→ Start here: [cybersecurity-portfolio](https://github.com/manlikefelo/cybersecurity-portfolio)** — the index that ties everything below together.

| Project | Team | What it proves |
|---------|:----:|----------------|
| **[security-homelab](https://github.com/manlikefelo/security-homelab)** | 🟣 | Designing and documenting a full AD + SIEM lab from scratch — on 16 GB of RAM |
| **[ad-attack-chain](https://github.com/manlikefelo/ad-attack-chain)** | 🔴 | Enumeration → exploitation → Domain Admin, with remediation and an executive summary |
| **[detection-engineering](https://github.com/manlikefelo/detection-engineering)** | 🔵 | Portable Sigma rules + deployed Wazuh rules that catch those attacks — plus a real tuning log |
| **[webapp-pentest-juiceshop](https://github.com/manlikefelo/webapp-pentest-juiceshop)** | 🔴 | Web application pentest with CVSS-scored findings and a client-ready PDF report |
| **[ir-threat-hunt](https://github.com/manlikefelo/ir-threat-hunt)** | 🔵 | Incident response using the NIST lifecycle, reconstructed timelines, and proactive threat hunts |
| **[detection-as-code](https://github.com/manlikefelo/detection-as-code)** | 🟣 | Sigma rules under version control, unit tests, and a CI pipeline that fails on a bad rule |
| **[adversary-emulation](https://github.com/manlikefelo/adversary-emulation)** | 🟣 | Atomic Red Team runs that measure detection coverage at 4 of 8 techniques, then close a gap |
| **[soc-automation](https://github.com/manlikefelo/soc-automation)** | 🔵 | A tested Python pipeline that enriches, scores, and tickets Wazuh alerts |
| **[sigmatest](https://github.com/manlikefelo/sigmatest)** | 🛠️ | A packaged CLI that lints and unit-tests Sigma rules with no live SIEM |

**The thread that runs through them:** I attack the lab in `ad-attack-chain`, write the
detections in `detection-engineering`, then investigate the resulting alerts in
`ir-threat-hunt` — the same events, from three perspectives.

---

## 🧭 Lab walkthroughs

Rooms and modules I've worked through on **TryHackMe** and **Hack The Box Academy**, each one
documented as a full written walkthrough with my own notes and screenshots — every title below
links to the PDF.

> 📂 All 25 walkthroughs live in **[lab-walkthroughs](https://github.com/manlikefelo/lab-walkthroughs)**.

### 🔵 Defensive · SOC · Forensics

| Room / Module | Platform | Skills |
|---|:---:|---|
| [Junior Security Analyst Intro](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/04-defensive-soc/thm-junior-security-analyst-intro.pdf) | THM | SOC workflow, alert triage, escalation |
| [Intro to Log Analysis](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/04-defensive-soc/thm-intro-to-log-analysis.pdf) | THM | Log parsing, anomaly spotting, timeline building |
| [Windows Forensics 1](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/04-defensive-soc/thm-windows-forensics-1.pdf) | THM | Registry hives, event logs, artifact analysis |
| [Intro to Digital Forensics](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/04-defensive-soc/thm-intro-to-digital-forensics.pdf) | THM | Evidence acquisition, chain of custody |
| [Intro to Malware Analysis](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/04-defensive-soc/thm-intro-to-malware-analysis.pdf) | THM | Static vs. dynamic analysis, IOC extraction |
| [Threat Intelligence Tools](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/04-defensive-soc/thm-threat-intelligence-tools.pdf) | THM | UrlScan.io, Abuse.ch, PhishTool, Cisco Talos |

### 🔴 Offensive · Pentesting

| Room / Module | Platform | Skills |
|---|:---:|---|
| [Attacktive Directory](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/thm-attacktive-directory.pdf) | THM | Kerbrute, Impacket, AD enumeration → post-exploitation |
| [OWASP Top 10 (2021)](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/thm-owasp-top-10-2021.pdf) | THM | The ten critical web risks, hands-on |
| [SQL Injection Fundamentals](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/htb-sql-injection-fundamentals.pdf) | HTB Academy | DBMS internals, UNION-based SQLi, exploitation |
| [Attacking Web Apps with Ffuf](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/htb-attacking-web-apps-with-ffuf.pdf) | HTB Academy | Directory, subdomain and parameter fuzzing |
| [Metasploit Framework](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/htb-metasploit-framework.pdf) | HTB Academy | Module types, payload generation, responsible use |
| [Intro to Offensive Security](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/thm-intro-to-offensive-security.pdf) | THM | Attacker mindset, gobuster directory fuzzing |
| [Vulnerability Assessment](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/03-offensive/htb-vulnerability-assessment.pdf) | HTB Academy | VA vs. pentest, scanning, prioritising remediation |

### 🌐 Networking · Recon · Wireless

| Room / Module | Platform | Skills |
|---|:---:|---|
| [Passive Reconnaissance](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/02-networking-recon/thm-passive-reconnaissance.pdf) | THM | whois, nslookup, dig — OSINT without touching the target |
| [DNS in Detail](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/02-networking-recon/thm-dns-in-detail.pdf) | THM | Record types, resolution, DNS hierarchy |
| [Introduction to Networking](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/02-networking-recon/htb-introduction-to-networking.pdf) | HTB Academy | OSI & TCP/IP, subnetting, proxies, topologies |
| [Layer 2 MAC Flooding & ARP Spoofing](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/02-networking-recon/thm-layer2-mac-flooding-arp-spoofing.pdf) | THM | ettercap, arpspoof, macof — L2 attack and defence |
| [WiFi Hacking 101](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/02-networking-recon/thm-wifi-hacking-101.pdf) | THM | Aircrack-ng, handshake capture, WPA analysis |

### 🧱 Foundations

| Room / Module | Platform | Skills |
|---|:---:|---|
| [Linux Fundamentals](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/htb-linux-fundamentals.pdf) | HTB Academy | Shell, permissions, services, system administration |
| [Windows Fundamentals](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/htb-windows-fundamentals.pdf) | HTB Academy | CLI, RDP, enumeration on Windows targets |
| [Introduction to Web Applications](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/htb-introduction-to-web-applications.pdf) | HTB Academy | Front/back end, HTTP, common web vulnerabilities |
| [Web Application Security](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/thm-web-application-security.pdf) | THM | How web apps break, and how to defend them |
| [Python Basics](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/thm-python-basics.pdf) | THM | Scripting fundamentals for security automation |
| [Getting Started (Pentesting)](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/htb-getting-started-pentesting.pdf) | HTB Academy | Structured pentest methodology, first boxes |
| [Introduction to Hack The Box](https://github.com/manlikefelo/lab-walkthroughs/blob/main/walkthroughs/01-foundations/htb-introduction-to-hack-the-box.pdf) | HTB Academy | Recon, enumeration, exploitation, privilege escalation |

---

## 🛠️ Tools I work with

**QA** &nbsp;`Playwright` · `TypeScript` · `Postman` · `Newman` · `pytest` · `SQL` · `GitHub Actions`

**Blue** &nbsp;`Wazuh` · `Sigma` · `Sysmon` · `MITRE ATT&CK` · `Windows Event Logs`

**Red** &nbsp;`Kali` · `nmap` · `Impacket` · `BloodHound` · `Metasploit` · `Burp Suite` · `ZAP` · `sqlmap` · `ffuf` · `John the Ripper` · `Aircrack-ng`

**Platform** &nbsp;`Active Directory` · `PowerShell` · `Linux` · `Docker` · `Python` · `VirtualBox`

---

## 💡 How I work

I document the messy bits — where a tool failed, where the evidence has limits, where a
detection missed and why. Honest work beats tidy work.

Every attack in my labs ships with its **detection** *and* its **remediation**. If something
can't be detected with what I have, I say so and explain the gap.

---

## 📫 Reach me

[![Website](https://img.shields.io/badge/Website-felix--githure.vercel.app-22c55e?style=flat-square)](https://felix-githure.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Felix%20Githure-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felix-githure/)
[![Email](https://img.shields.io/badge/Email-felix.maina095%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:felix.maina095@gmail.com)
