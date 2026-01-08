# 👋 Hey, I’m @vitalelele

🔐 **Penetration Testing • Offensive Security • Security Tooling**

I don't just look for vulnerabilities, I exploit them to demonstrate real-world risk.  
I don't believe in *security through obscurity*.  
If we don’t find the cracks first, attackers will.

---

## 🧠 About Me

I’m driven by curiosity and a simple belief:  
**to truly understand a system, you first have to break it.**

I’m passionate about exploring systems beyond their intended boundaries,
getting where I *shouldn’t* be able to get, and understanding *why* I can.

Penetration testing, for me, isn’t just about finding vulnerabilities.  
It’s about thinking like an attacker, chaining weaknesses, and proving real-world impact.

I build tooling that helps turn recon and raw data into actionable findings,
because defense only works when offense is truly understood.

---

## 🛠️ Focus Areas

**Offensive Security:** Network recon · Web/API testing · Vulnerability validation · Reporting  
**Security Tooling:** Automation · Data enrichment · Findings normalization · Reporting pipelines  
**Languages:** Python · Java · C / C#

---

## 🎯 Featured Projects

### 🔎 nmap2report  
**Automated Security Reporting from Nmap XML**

Turns Nmap XML scans into structured Markdown/PDF reports with host/service discovery, extracted CVEs/CVSS, enrichment (CWE/severity), and per-host risk metrics. Designed for pentest deliverables and repeatable reporting.

🔗 https://github.com/vitalelele/nmap2report

**MITRE ATT&CK (mapping):**
- Reconnaissance (TA0043): Network Service Discovery (T1046), Network Sniffing/Discovery context (T1040*)
- Discovery (TA0007): Remote System Discovery (T1018), System/Network Information Discovery (T1082/T1016*)
- Resource Development (TA0042): Gather Victim Network Information (T1590)
- (Reporting/Analysis): operational support for post-recon triage and vulnerability-driven prioritization

\*Technique adjacency depends on assessment scope and data sources (e.g., packet capture vs. scan output).

---

### 🔑 WordlistRefinery  
**High-Performance Password Dataset Processing Engine**

Processes real-world password leaks at scale: streaming pipelines, low memory footprint, entropy scoring, policy/complexity filters, and clean exports for cracking tools or analysis workflows.

🔗 https://github.com/vitalelele/WordlistRefinery

**MITRE ATT&CK (mapping):**
- Credential Access (TA0006): Brute Force (T1110) support workflows (wordlist refinement, candidate generation, dataset optimization)
- Resource Development (TA0042): Acquire Infrastructure / Develop Capabilities (T1587*)—tooling to improve operational efficiency
- (Research/Defense): password strength analysis and corpus intelligence for auditing

\*Indirect mapping: the project is a tooling enabler; usage determines the exact technique alignment.

---

### 📡 QRX  
**QR Code Generator & Scanner (Python + Flask)**

A lightweight web tool to generate and decode QR codes.

🔗 https://github.com/vitalelele/QRX

---

### 🛡️ Misinformation Fight System  
**Detection & Analysis of Online Misinformation**

Tooling to analyze content and identify misinformation patterns through automated analysis and feedback loops.

🔗 https://github.com/vitalelele/Misinformation-Fight-System

---

## 🧭 Current Direction

I’m focusing on building a practical offensive-security portfolio:
- recon → enrichment → triage → reporting
- repeatable tooling over one-off scripts
- clean engineering with real-world datasets and constraints

---

## 📫 Let’s Connect

If you’re into penetration testing, offensive security, or building serious security tooling, feel free to reach out.

Let’s break things, responsibly.
