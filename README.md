# ServiceNow

**Afiz (AJ) Jiwa** | ServiceNow GRC, SecOps and IRM

ServiceNow is the platform that makes GRC real. Most companies already run on it, at least for ticketing, and many use it for much more. I haven't found anything else that covers GRC as completely. This repo holds my ServiceNow certifications, what each one taught me, and the hands-on builds that prove it.

More on how I think about GRC: [How I see it](https://github.com/atoz-guy/GRC-Governance-Risk-Compliance/blob/main/Pathway.md#how-i-see-it)

---

## 📌 Certifications

| Cert | Passed | What it taught me | Folder |
|---|---|---|---|
| ✅ **CSA** Certified System Administrator | June 2026 | Platform fundamentals, tables, data relationships and core workflow automation | [01-ServiceNow-CSA](01-ServiceNow-CSA) |
| ✅ **CIS-RC** Risk and Compliance | July 2026 | Turning messy business risk into a working GRC setup: policies, compliance tracking and risk registers as automated IRM workflows | [02-ServiceNow-CIS-RC](02-ServiceNow-CIS-RC) |
| ✅ **CIS-DF** Data Foundations | Oct 2026 | The CMDB and data model, and keeping platform data clean and trustworthy | [03-ServiceNow-CIS-DF](03-ServiceNow-CIS-DF) |
| ✅ **CIS-SIR** Security Incident Response | Oct 2026 | Incident workflows that detect, track and close security incidents | [04-ServiceNow-CIS-SIR](04-ServiceNow-CIS-SIR) |
| ✅ **CIS-VR** Vulnerability Response | Oct 2026 | Turning scanner findings into prioritized, trackable remediation work | [05-ServiceNow-CIS-VR](05-ServiceNow-CIS-VR) |

**Security Operations (SecOps):** CIS-DF is required before SIR and VR. That makes sense: incident and vulnerability work is only as good as the asset data underneath it.

---

## 🛠️ Hands-on builds

Certs show what I know. These show what I can build. They live in [PDI-Labs-and-Builds](PDI-Labs-and-Builds), one for each cert, done in my Personal Developer Instance.

| Build | Cert | Status |
|---|---|---|
| Risk register entry for a real finding | CIS-RC | 🔲 Planned |
| Mapping NIST controls to a policy | CIS-RC | 🔲 Planned |
| Automated control evidence | CIS-RC | 🔲 Planned |
| CMDB cleanup: duplicates and missing owners | CIS-DF | 🔲 Planned |
| Phishing incident worked as a SIR case | CIS-SIR | 🔲 Planned |
| Vulnerability prioritization by asset importance | CIS-VR | 🔲 Planned |

---

## 🎯 Next milestones

| Milestone | Focus |
|---|---|
| 🔜 **PDI builds** | The table above |
| 🔲 **CAD** Certified Application Developer | Custom scoped apps, server and client scripting, app data models |
| 🔲 **CTA** Certified Technical Architect | Long-term goal: turning business needs into enterprise-scale ServiceNow solutions across security, risk and IT |

---

## 🔗 How it connects to my other work

| Where | Connection |
|---|---|
| [GRC-Labs](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/GRC-Labs) | Policy-as-code results become evidence in ServiceNow |
| [Forward-Deployed-Identity-Security](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/Forward-Deployed-Identity-Security) | CyberArk and Entra connected to ServiceNow access requests and approvals |
| [SOC-Defensive-Labs](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/SOC-Defensive-Labs) | The kind of incidents SIR is built to track |
| [Service-Desk-Labs](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/Service-Desk-Labs) | The ticket lifecycle ServiceNow is built on |

---

## 📚 Learning

- [sn-learn-javascript](sn-learn-javascript): my work through ServiceNow Developer's *Learn JavaScript on the Now Platform* video series, groundwork for CAD
