<!-- 0xvanguard — GitHub Profile README -->

<div align="center">

```
 ██████╗ ██╗  ██╗██╗   ██╗ █████╗ ███╗  ██╗ ██████╗ ██╗   ██╗ █████╗ ██████╗ ██████╗
██╔═████╗╚██╗██╔╝██║   ██║██╔══██╗████╗ ██║██╔════╝ ██║   ██║██╔══██╗██╔══██╗██╔══██╗
██║██╔██║ ╚███╔╝ ██║   ██║███████║██╔██╗██║██║  ███╗██║   ██║███████║██████╔╝██║  ██║
████╔╝██║ ██╔██╗ ╚██╗ ██╔╝██╔══██║██║╚████║██║   ██║██║   ██║██╔══██║██╔══██╗██║  ██║
╚██████╔╝██╔╝╚██╗ ╚████╔╝ ██║  ██║██║ ╚███║╚██████╔╝╚██████╔╝██║  ██║██║  ██║██████╔╝
 ╚═════╝ ╚═╝  ╚═╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚══╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝
```

**`Security Analyst · AppSec · OSINT · Blue Team · DevSecOps`**

[![Location](https://img.shields.io/badge/📍-Bogota%2C%20Colombia-0d1117?style=flat-square&labelColor=161b22)](https://github.com/0xvanguard)
[![Focus](https://img.shields.io/badge/Focus-Cybersecurity%20%7C%20AI%20Security-a855f7?style=flat-square&labelColor=161b22)](https://github.com/0xvanguard)
[![Status](https://img.shields.io/badge/Status-Open%20to%20Remote%20Work-22c55e?style=flat-square&labelColor=161b22)](https://github.com/0xvanguard)

</div>

---

## 🎯 Who is 0xvanguard?

Security practitioner from Colombia focused on **applied offensive and defensive security**. I don't just list tools — I document the *why*, the *how*, the *risk*, and the *fix*.

- 🔴 **Red/AppSec:** web vulnerabilities (OWASP Top 10 + API Security), recon, OSINT, exploitation workflows
- 🔵 **Blue Team:** SIEM deployment (Wazuh), log analysis, alert tuning, MITRE ATT&CK-mapped detections
- 🟣 **Purple:** bridging findings to remediations, threat modeling, DevSecOps pipelines
- 🤖 **AI Security:** LLM attack surfaces, prompt injection, AI-assisted threat hunting

> *"Un portafolio real no dice 'sé herramientas'. Dice: puedo investigar, documentar evidencia, explicar riesgo y comunicar una remediación."*

---

## 🛠️ Technical Stack

| Layer | Tools & Frameworks |
|---|---|
| **Languages** | Python · Bash · JavaScript · SQL |
| **AppSec / Web** | Burp Suite · OWASP WSTG · PortSwigger Labs · Nikto · SQLMap |
| **OSINT & Recon** | Shodan · theHarvester · Maltego · WHOIS APIs · Recon-ng |
| **Blue Team / SIEM** | Wazuh · Splunk (basic) · ELK Stack · Sigma rules |
| **Frameworks** | OWASP Top 10 · MITRE ATT&CK · PTES · NIST CSF |
| **Infra / DevSecOps** | Docker · GitHub Actions · Linux (Pop OS · Mint) · VPS |
| **AI Tooling** | LangChain · OpenAI API · Claude · Prompt Engineering |

---

## 📂 Portfolio — Technical Projects

> Each project includes: **objective → methodology → evidence → risk → remediation**

### 🔴 AppSec & Web Security

| Project | Description | Frameworks |
|---|---|---|
| [`GovLLM-Sentinel`](https://github.com/0xvanguard/GovLLM-Sentinel) | Framework de evaluación y hardening de LLMs para sector público — PII Guard, Compliance Filter, Alignment Module, Red-Teaming con 13 vectores de ataque, 40 tests | AI Security · LLM · Docker |
| [`osint-exposure-report`](https://github.com/0xvanguard/osint-exposure-report) | Automated OSINT recon tool — generates professional PDF exposure reports for companies. Subdomains, DNS, ports, emails, IP reputation. 37 tests + CI | Python · nmap · ReportLab |
| [`hibp-audit-tool`](https://github.com/0xvanguard/hibp-audit-tool) | Automated password breach audit using HIBP API v3 — generates PDF/Excel reports in Spanish with risk scoring per employee. 17 tests + CI | Python · HIBP · ReportLab |
| [`gophish-phishing-simulator`](https://github.com/0xvanguard/gophish-phishing-simulator) | Phishing campaign automation via GoPhish API — generates professional PDF reports with risk scores per employee. 10 tests + CI | Python · GoPhish · ReportLab |

### 🟡 OSINT & Intelligence

| Project | Description | Frameworks |
|---|---|---|
| [`cyberremote-monitor-pro`](https://github.com/0xvanguard/cyberremote-monitor-pro) | Global intelligence board for remote cybersecurity jobs — 3D globe, choropleth maps, signal feed, government mode. React + FastAPI + PostgreSQL. 21 tests + CI | React · FastAPI · globe.gl |
| [`bug-bounty-vault`](https://github.com/0xvanguard/bug-bounty-vault) | Educational bug bounty platform — 12-week roadmap, 40+ tools guide, first-$500 guide, hunter tracker. Interactive dashboard with Matrix background | HTML · CSS · JS |
| [`latam-cybersecurity-salaries-2026`](https://github.com/0xvanguard/latam-cybersecurity-salaries-2026) | Visual analysis of cybersecurity salaries in LATAM — local vs remote US/EU comparison with interactive Chart.js dashboard | HTML · Chart.js |

### 🔵 Education & Labs

| Project | Description | Frameworks |
|---|---|---|
| [`0xVKRAD-Evolution-Academy`](https://github.com/0xvanguard/0xVKRAD-Evolution-Academy) | Offensive cybersecurity academy — missions, Docker labs, XP progression system, writeup templates. Spanish, free, no filters | Docker · Flask · MySQL |
| [`cognitive-tracker`](https://github.com/0xvanguard/cognitive-tracker) | Personal cognitive performance tracker — IQ, memory, logic & focus tests with progress analytics and AI coach. Python + FastAPI + Streamlit | Python · FastAPI · Streamlit |

---

## 📝 Writeup Format I Follow

Every security finding I document uses this structure (based on OWASP WSTG + PTES):

```
📋 EXECUTIVE SUMMARY    → What was found, severity, business risk
🔍 SCOPE & METHODOLOGY  → Test parameters, tools used, rules of engagement  
🎯 FINDING              → Vulnerability, CWE/CVE reference, MITRE technique
📸 EVIDENCE             → Reproducible proof (request/response, payload, PoC)
💥 IMPACT               → Technical + business risk explanation
🛠️ REMEDIATION          → Specific fix with code/config example where applicable
📊 CVSS SCORE           → Calculated severity vector
```

> *No capturas sueltas. No flags sin contexto. Solo criterio técnico documentado.*

---

## 🎓 Certifications & Education

- 📘 **Information Security** — Politécnico Grancolombiano *(Aug 2026 →)*
- 🎯 **Ethical Hacking & DevSecOps** — CIIF Latam *(in progress)*
- 🏛️ **Multiple IT & Cybersecurity courses** — SENA
- 🌐 **PortSwigger Web Security Academy** — Advanced labs *(ongoing)*
- 🔐 **TryHackMe / Hack The Box** — Active practitioner

---

## 🤝 Open Source Contributions

Contributing to security-related open source projects is how I validate knowledge beyond labs.

- 🔍 Reviewing CVE reports and open issues in security tooling repos
- 🛡️ Targeting projects with known vulnerabilities needing fixes (Open CSF and similar)
- 📖 Documenting security improvements with full evidence and remediation

> *"Si podés mostrar un commit que soluciona un problema de seguridad real, eso vale más que cualquier certificado."*

---

## 📊 GitHub Activity

<div align="center">

![0xvanguard's GitHub Stats](https://github-readme-stats.vercel.app/api?username=0xvanguard&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a855f7&icon_color=a855f7&text_color=94a3b8)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=0xvanguard&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a855f7&text_color=94a3b8)

</div>

---

## 📡 Contact & Links

| Platform | Link |
|---|---|
| 🐙 GitHub | [@0xvanguard](https://github.com/0xvanguard) |
| 🌐 Portfolio Web | [0xvanguard.github.io/trillion-income-streams](https://0xvanguard.github.io/trillion-income-streams) |
| 💼 LinkedIn | *Próximamente* |
| 📧 Email | *Disponible en solicitud* |

---

<div align="center">

```
[ Built with purpose from Bogotá, Colombia ]
[ Criterion over credentials. Evidence over screenshots. ]
```

</div>
