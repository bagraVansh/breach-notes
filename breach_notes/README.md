# 🛡️ CTF & SOC Write-Ups

A collection of my write-ups from CTF challenges and SOC/blue team labs. Covers malware analysis, threat hunting, log investigation, and incident response — mostly from platforms like CyberDefender, TryHackMe, and Any.Run.

Not a tutorial blog. Just documenting my process, findings, and the reasoning behind them.

---

## Table of Contents

- [About](#about)
- [Structure](#structure)
- [Write-Ups](#write-ups)
  - [Malware Analysis](#malware-analysis)
- [Tools I Use](#tools-i-use)
- [Author](#author)

---

## About

These write-ups are for my own learning and reference, but if they help someone else — great. Each one walks through the investigation process: what I looked at, what I found, and why it matters. I try to keep them concise and technical without over-explaining the obvious.

---

## Structure

```
📁 repo-root
├── 📁 malware-analysis
│   └── 📁 oski-stealer
│       └── writeup.md
├── 📁 threat-hunting
├── 📁 incident-response
└── README.md
```

---

## Write-Ups

### Malware Analysis

| # | Lab | Platform | Malware Family | Techniques |
|---|-----|----------|----------------|------------|
| 1 | [Oski Stealer](./malware-analysis/oski-stealer/writeup.md) | CyberDefender | Oski / Stealc | T1555, C2 Comms, Self-Deletion |

---

## Tools I Use

- **VirusTotal** — hash lookup, static analysis, network indicators
- **Any.Run** — interactive sandbox, behavior analysis, MITRE mapping
- **MITRE ATT&CK Navigator** — technique mapping
- **CyberChef** — decoding, decryption, data transformation

---

## Author

**Vansh Bagra**  
[GitHub](https://github.com/bagraVansh) · [LinkedIn](https://www.linkedin.com/in/vansh-bagra-a1516b239/)

> If you spot something wrong in a write-up, open an issue or reach out. I'd rather be corrected than confidently wrong.
