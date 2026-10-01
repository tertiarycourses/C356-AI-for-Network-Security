# AI for Network Security

Apply artificial intelligence to network monitoring, threat detection, vulnerability assessment
and incident response — and learn to defend the AI itself.

| Course detail | Information |
|---|---|
| Course code | `C356` |
| Programme | Non-WSQ |
| Duration | 2 days · 9:30am – 5:30pm · 15 instructional hours |
| Level | Beginner |
| Registration | [View course details and register](https://www.tertiarycourses.com.sg/ai-for-network-security.html) |

**[→ Register for this course](https://www.tertiarycourses.com.sg/ai-for-network-security.html)**

Conducted by **Tertiary Infotech Academy Pte Ltd** · UEN 201200696W

---

## About the course

Attacks now move at machine speed and at a volume no analyst can read. Signature-based
detection only finds what someone has already named, and a security team can only triage
so many alerts an hour. This course closes both gaps.

Over two days you use AI to analyse network configurations, baseline normal traffic,
detect anomalies, prioritise vulnerabilities, score risk, design and implement controls,
triage alerts and document incidents. You also do something most AI courses skip: you
attack your own detection model with evasion and poisoning, measure how far it degrades,
and then harden it against those attacks using the NIST and NSA/CISA guidance.

Everything is hands-on. The twelve labs form **one continuous engagement** — each
deliverable feeds the next.

## Learning outcomes

| | Outcome |
|---|---|
| **LO1** | Identify and assess network threats and vulnerabilities by analysing ICT configurations |
| **LO2** | Evaluate organisational assets and develop risk management plans addressing infrastructure weaknesses |
| **LO3** | Design and implement security measures for network components by managing security phases |
| **LO4** | Document security incidents and apply incident response configurations based on established procedures |

## Topics covered

| Topic | Covers | Weight |
|---|---|---|
| **1 · AI-Assisted Network Threat and Vulnerability Analysis** | ICT networks & configuration · the AI threat landscape · pattern-of-life baselines · NDR · AI vulnerability prioritisation | 25% |
| **2 · AI-Powered Network Risk Assessment and Management Planning** | Asset discovery & classification · CIA business impact · AI risk scoring · risk registers · NIST CSF & AI RMF | 25% |
| **3 · Designing and Implementing AI-Enhanced Network Security Measures** | Defence in depth · the three security phases · segmentation & zero trust · AI firewalls, IDS/IPS, UEBA · securing the AI itself | 30% |
| **4 · AI-Assisted Security Incident Documentation and Response** | Logging & syslog · SIEM/SOAR · AI alert triage · NIST SP 800-61 lifecycle · incident documentation · playbooks | 20% |

## Labs

Twelve labs, each building on the last. Full step-by-step procedures are in the
[Learner Guide](LG-AI-for-Network-Security.md); each lab folder under [`labs/`](labs/) carries
its own guide.

| # | Lab | Topic | Produces |
|---|---|---|---|
| 1 | [Map the ICT Network and Analyse Its Configuration](labs/lab-01-map-the-ict-network-and-analyse-its-configuration/) | 1 | Network configuration inventory + weakness list |
| 2 | [Baseline Normal Traffic and Detect an Anomaly with AI](labs/lab-02-baseline-normal-traffic-and-detect-an-anomaly-with-a/) | 1 | Isolation Forest anomaly report, TP/FP verified |
| 3 | [AI-Assisted Vulnerability Analysis and Prioritisation](labs/lab-03-ai-assisted-vulnerability-analysis-and-prioritisatio/) | 1 | Prioritised CVE worklist (CVSS × criticality × KEV) |
| 4 | [Build an Asset Register and Classify What Needs Protecting](labs/lab-04-build-an-asset-register-and-classify-what-needs-prot/) | 2 | Classified asset register with C/I/A ratings |
| 5 | [AI-Assisted Risk Scoring and the Risk Register](labs/lab-05-ai-assisted-risk-scoring-and-the-risk-register/) | 2 | Scored register with inherent + residual risk |
| 6 | [Develop the Risk Management Plan](labs/lab-06-develop-the-risk-management-plan/) | 2 | Treatment plan mapped to the NIST CSF |
| 7 | [Design the Layered Architecture Across the Three Security Phases](labs/lab-07-design-the-layered-architecture-across-the-three-sec/) | 3 | Segmented design + zone access matrix |
| 8 | [Implement AI-Enhanced Controls — Firewall Policy, IDS and Adaptive Access](labs/lab-08-implement-ai-enhanced-controls-firewall-policy-ids-a/) | 3 | Default-deny ruleset + tuned detections |
| 9 | [Secure the AI Itself — Adversarial ML and the NSA/CISA Deployment Controls](labs/lab-09-secure-the-ai-itself-adversarial-ml-and-the-nsa-cisa/) | 3 | Demonstrated evasion + poisoning, hardening checklist |
| 10 | [Centralise Logs and Triage Alerts with AI](labs/lab-10-centralise-logs-and-triage-alerts-with-ai/) | 4 | Logging specification + triaged alert queue |
| 11 | [Document a Security Incident to the Standard](labs/lab-11-document-a-security-incident-to-the-standard/) | 4 | Evidence-based incident record |
| 12 | [Implement the Incident Response Configuration and Playbook](labs/lab-12-implement-the-incident-response-configuration-and-pl/) | 4 | Tested playbook + measured containment time |

## Tools used

`Nmap` · `Wireshark / tshark` · `Python 3` with `pandas` and `scikit-learn` ·
a generative AI assistant (Claude, ChatGPT or Copilot) · a spreadsheet · a modern browser

### Browser practice tools

Free, no install, used directly in the lab procedures. The PCAP Analyzer processes your
capture locally in the browser — nothing is uploaded.

| Tool | Used in |
|---|---|
| [IP Calculator](https://alfredang.github.io/ipcalculator/) | Lab 1 — scan scope · Lab 7 — subnet the security zones |
| [PCAP Analyzer](https://alfredang.github.io/pcapanalyzer/) | Lab 2 — capture triage · Lab 11 — capture evidence |
| [Cybersecurity Simulator](https://alfredang.github.io/cybersecuritysimulator/) | Lab 5 — ground the likelihood scores |
| [Cryptography Toolkit](https://alfredang.github.io/cryptography-toolkit/) | Lab 8 — confidentiality control · Lab 11 — hash tamper-evidence |
| [RegexLab](https://alfredang.github.io/regexgenerator/) | Lab 10 — build and negatively test the log filters |

Two further tools are optional extension work. They teach offensive penetration testing,
which sits outside the scope of this course, so they are not part of any lab — run them to see what an attacker learns about a target:
[Hacklab](https://alfredang.github.io/ethnicalhacking/) ·
[FauxBank](https://pentest-fauxbank.vercel.app/)

## Public package

**Current version: v1.0 · 30 September 2026**

| File | What it is |
|---|---|
| [`courseware/AI-for-Network-Security-v1.0.pptx`](courseware/AI-for-Network-Security-v1.0.pptx) | Trainer slide deck — 145 slides |
| [`courseware/AI-for-Network-Security-v1.0.pdf`](courseware/AI-for-Network-Security-v1.0.pdf) | Learner slides (PDF of the deck) |
| [`courseware/LP-AI-for-Network-Security.docx`](courseware/LP-AI-for-Network-Security.docx) · [`.pdf`](courseware/LP-AI-for-Network-Security.pdf) | Lesson Plan |
| [`courseware/LG-AI-for-Network-Security.docx`](courseware/LG-AI-for-Network-Security.docx) · [`.pdf`](courseware/LG-AI-for-Network-Security.pdf) | Learner Guide |
| [`LG-AI-for-Network-Security.md`](LG-AI-for-Network-Security.md) | Learner Guide, Markdown mirror of the DOCX |
| [`labs/`](labs/) | 12 lab folders, each with its own step-by-step README |

This repository publishes the learner courseware only. Trainer reference material is kept
private and is not part of this repository.

## Reference sources

The AI content is grounded in authoritative guidance:

- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [NIST AI 100-2e2025 — Adversarial Machine Learning](https://csrc.nist.gov/pubs/ai/100/2/e2025/final)
- [NSA / CISA / FBI — Deploying AI Systems Securely](https://www.cisa.gov/news-events/alerts/2024/04/15/joint-guidance-deploying-ai-systems-securely)
- [CISA Artificial Intelligence](https://www.cisa.gov/ai)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [NIST SP 800-61 — Incident Handling](https://csrc.nist.gov/pubs/sp/800/61/r2/final)
- [CISA Known Exploited Vulnerabilities](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

## Responsible use

Every scanning, capture and testing technique in this course must only be run against
systems you own or have **written authorisation** to test. Unauthorised access to a
computer is a criminal offence under the Singapore Computer Misuse Act and its
equivalents elsewhere.

## Contact

**Tertiary Infotech Academy Pte Ltd** · UEN 201200696W
📧 enquiry@tertiaryinfotech.com · 📞 +65 6100 0613
🌐 [www.tertiarycourses.com.sg](https://www.tertiarycourses.com.sg)

---

© 2026 Tertiary Infotech Academy Pte Ltd. All rights reserved.
