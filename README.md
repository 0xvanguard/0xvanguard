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

[![Location](https://img.shields.io/badge/📍-Chía%2C%20Colombia-0d1117?style=flat-square&labelColor=161b22)](https://github.com/0xvanguard)
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
| [`writeups-portswigger`](#) | Technical writeups of PortSwigger Web Security Academy labs — SQL injection, XSS, SSRF, IDOR, Web LLM attacks. Each writeup follows OWASP WSTG format with executive summary + finding + evidence + remediation | OWASP WSTG · CWE |
| [`api-security-labs`](#) | Practical analysis of OWASP API Security Top 10 vulnerabilities on intentionally vulnerable apps (crAPI, vAPI). Documented with risk impact and fix | OWASP API Top 10 |
| [`osint-recon-toolkit`](#) | Python automation for OSINT recon workflows — passive fingerprinting, data aggregation, report generation | PTES Recon Phase |

### 🔵 Blue Team & Detection Engineering

| Project | Description | Frameworks |
|---|---|---|
| [`wazuh-homelab-siem`](#) | Full Wazuh deployment on local VM — agent enrollment, custom rules, log analysis, alert tuning. Documented as a production-grade implementation report | MITRE ATT&CK · Wazuh |
| [`mitre-detection-rules`](#) | Custom Wazuh/Sigma detection rules mapped to MITRE ATT&CK techniques (T1059, T1078, T1190). Includes TP/FP analysis per rule | MITRE ATT&CK |
| [`log-analysis-lab`](#) | Structured log analysis exercises — identifying C2 beaconing, brute force patterns, lateral movement indicators in raw Apache/auth logs | MITRE · Sigma |

### 🟣 Purple Team / Documentation

| Project | Description | Frameworks |
|---|---|---|
| [`pentest-report-template`](#) | Professional penetration test report template following OWASP WSTG + PTES structure: executive summary → scope → findings → CVSS scoring → remediations | OWASP · PTES · CVSS |
| [`trillion-income-streams`](https://github.com/0xvanguard/trillion-income-streams) | Web platform organizing income vectors with hacker-style UI, Docker backend and Grafana dashboard | Python · FastAPI · Docker |

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
