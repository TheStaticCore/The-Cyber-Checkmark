# Cyber Checkmark ✦

> A self-paced cybersecurity career roadmap tracker built as a PWA. 100 skills, certs, tools, and frameworks across 5 phases — from IT fundamentals to AI security.

**Live:** [staticcore.io](https://staticcore.io) · **Built by:** [Connor Gibson](https://linkedin.com/in/connorwgibson)

---

## What It Is

Cyber Checkmark maps a complete cybersecurity career path from zero to senior engineer. Every item is curated based on real job postings, NERC CIP compliance requirements, CompTIA/GIAC curricula, and what industry professionals actually use day to day.

Check off skills as you learn them, log lab hours, earn XP, track your pace, and filter by target job role — so you always know exactly what to study next.

---

## Features

- **100 roadmap items** across 5 phases — certs, skills, tools, frameworks, and training
- **XP system** with 10 levels (Iron → Phantom)
- **13 role filters** — view only skills relevant to your target job
- **Lab hour logging** — tap `···` on any item to log hands-on time
- **Study pace calculator** — estimates your completion date based on history
- **Notes per item** — attach context, resources, or study logs
- **Search** — find any skill across all 100 items instantly
- **Custom Phase (Phase 06)** — bookmark items from any phase or add your own goals
- **Progress sharing** — encode your full progress state in a shareable URL
- **Resume export** — generate a plain-text skills summary from completed items
- **Streak tracking** — daily completion streaks with 🔥 badge
- **Cert expiry warnings** — ⚠ RENEW alerts when certs approach renewal date
- **PWA** — installable on mobile and desktop, works offline
- **Dark / light mode**
- **Auto-save** — all progress saved to localStorage automatically

---

## The Roadmap

| Phase | Focus | Salary Range | Items |
|-------|-------|-------------|-------|
| 01 · Foundation | Core IT, scripting, networking | $50k – $70k | 17 |
| 02 · Security Core | Offensive & defensive fundamentals | $75k – $100k | 24 |
| 03 · Cloud & Microsoft | Azure security engineering stack | $100k – $140k | 13 |
| 04 · Advanced & GRC | Architecture, compliance, mastery | $140k – $200k+ | 33 |
| 05 · AI Security | Secure AI deployment & LLM ops | $140k – $220k+ | 13 |
| 06 · My Phase | Your custom goals (unlimited) | — | — |

---

## Role Filters

Filter the roadmap to show only skills relevant to your target role:

| Role | Key Skills Highlighted |
|------|----------------------|
| Sysadmin / IT | A+, N+, Linux, Windows Server, AD, PowerShell |
| SOC Analyst | Splunk, SIEM, MITRE ATT&CK, Detection Engineering, CySA+ |
| Cloud Security | AZ-500, SC-200, Sentinel, Entra, Defender, KQL |
| Security Engineer | CISSP, Architecture Review, Zero Trust, Vuln Mgmt |
| Critical Infra | NERC CIP, IEC 62443, SCADA, pfSense, Segmentation |
| DoD / GRC | RMF, DISA STIG, DoD 8570, NIST 800-53, CySA+ |
| AI Security | NIST AI RMF, LLM Security, Air-Gap, TPM, IMA |
| Incident Responder | PICERL, GCIH, Volatility, Autopsy, MITRE D3FEND |
| Malware Analyst | Volatility, Autopsy, Zeek, MITRE ATT&CK, Kali |
| GRC Analyst | ISO 27001, SOC 2, PCI-DSS, NERC CIP, CISSP |
| DevSecOps Engineer | DevSecOps, OWASP, Docker, Terraform, Supply Chain |
| Network Security | N+, Cisco IOS, pfSense, Wireshark, Nmap, Zero Trust |
| ⭐ Priority | Your personally starred items |

---

## XP Levels

| Level | Title | XP Required |
|-------|-------|------------|
| 1 | Iron | 0 |
| 2 | Bronze | 500 |
| 3 | Silver | 1,200 |
| 4 | Steel | 2,200 |
| 5 | Gold | 3,500 |
| 6 | Platinum | 5,200 |
| 7 | Titanium | 7,500 |
| 8 | Diamond | 10,500 |
| 9 | Obsidian | 14,500 |
| 10 | Phantom | 19,500 |

XP per item: CERT 150 · FRAMEWORK 120 · SKILL 100 · TRAINING 90 · TOOL 80

---

## How to Log Lab Hours

1. Open any phase and tap the **···** button on any item
2. Use **−** / **+** or type directly into the hours field
3. Tap **SAVE**

Total logged hours appear in the LAB TIME stat card. Hours also show inline on the item row once logged.

---

## Install as PWA

**Mobile (iOS/Android):** Open in Safari or Chrome → Share → Add to Home Screen

**Desktop (Chrome/Edge):** Click the install icon in the address bar

---

## File Structure

```
/
├── index.html      — Full app, single file, no build step
├── manifest.json   — PWA manifest
├── sw.js           — Service worker for offline support
├── icon-192.png    — PWA icon 192×192
├── icon-512.png    — PWA icon 512×512
└── README.md       — This file
```

---

## Tech Stack

- **React 18** via CDN, no build step required
- **Babel Standalone** for JSX transpilation in the browser
- **IBM Plex Sans + IBM Plex Mono** via Google Fonts
- **localStorage** for all data persistence
- **Service Worker** for offline PWA support
- Zero npm dependencies — open `index.html` and it works

---

## Local Development

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .

# Then open http://localhost:8080
```

PWA features (service worker, install prompt) require HTTPS or localhost.

---

## License

© 2026 Connor Gibson — [staticcore.io](https://staticcore.io)

Free to use for personal, educational, and non-commercial purposes.
Commercial use, resale, or redistribution for profit requires written permission.
Credit must be kept intact in all copies or derivatives.
