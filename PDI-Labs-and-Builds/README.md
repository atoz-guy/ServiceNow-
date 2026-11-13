# 🛠️ PDI Labs and Builds

**The goal:** prove what the certs say. Each build is done in my ServiceNow Personal Developer Instance (PDI) and written up with screenshots.

Where I can, each build uses work from my other labs, so it's a real scenario, not a made-up one.

---

## Planned builds

| # | Build | Cert | What it shows | Uses |
|---|---|---|---|---|
| 01 | **Risk register entry** | CIS-RC | Log a real risk, score it, link it to the control that should stop it | The phishing finding from my [Lab 002](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/blob/main/GRC-Labs/Analysis-After-It-Happens/Lab-002-Phishing-Investigation.md) (score 16, HIGH) |
| 02 | **Policy to control mapping** | CIS-RC | Connect a policy to the NIST 800-53 controls behind it | IA-2(1) MFA, AT-2 training |
| 03 | **Automated control evidence** | CIS-RC | A control that gets its pass or fail from a check, not by hand | My [GRC Playground](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/GRC-Labs/Engineering-Before-It-Happens) labs |
| 04 | **CMDB cleanup** | CIS-DF | Find duplicate assets and missing owners, and fix them | My SQL and pandas data cleaning skills |
| 05 | **Phishing incident as a SIR case** | CIS-SIR | Open, triage, contain and close a security incident with a playbook | The email from my [Challenge 1](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/SOC-Defensive-Labs/challenge1-phishing-emails) |
| 06 | **Vulnerability prioritization** | CIS-VR | Rank findings by how important the affected asset is, not just severity | Asset data from build 04 |

Status for all: 🔲 Planned

---

## What each write-up will include

- **Goal:** what I'm building and why
- **Steps:** what I configured, with screenshots
- **Result:** what it looks like working
- **What I learned:** in my own words
- **The GRC angle:** which control or risk it supports

📸 *Screenshot habit: hide the bookmarks bar (Ctrl+Shift+B) or crop to the ServiceNow window before capturing.*
