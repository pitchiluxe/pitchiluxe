# **Erick Omari** 👋

**Professional** | Building intelligent software ecosystems, AI agents, cybersecurity training labs, and developer-first web applications.

---

## 🔐 Cybersecurity Labs & Projects

Hands-on, portfolio-grade lab environments demonstrating real-world security, networking, and cloud skills:

| Project | Description |
|---------|-------------|
| [🛡️ Cybersecurity Academy](https://github.com/pitchiluxe/cybersecurity-academy) | AI-powered IT support training lab with live ticket queue, 16 certification courses, interactive 3D wiring & FortiGate labs, simulated VMs, and rubric grading |
| [🎯 PhishForge](https://github.com/pitchiluxe/phishforge) | Cybersecurity awareness and phishing simulation platform |

## 💼 Professional Projects

| Project | Status | Description |
|---------|--------|-------------|
| [🔑 IAM Range](https://github.com/pitchiluxe/iam-range) | ![Shipped](https://img.shields.io/badge/-shipped-4ec9b0?style=flat-square) | A downloadable Windows-like workstation for identity engineering — Active Directory, PIM, Okta/Entra hybrid sync, access certification and break-glass recovery, with an AI supervisor that refuses to close work you have not done |
| [🧭 IAM & SSO 3D Lab](https://github.com/pitchiluxe/iam-sso-3d-lab) | ![Shipped](https://img.shields.io/badge/-shipped-4ec9b0?style=flat-square) | A 3D identity operations floor you walk through — 13 labs across directory, SSO, MFA, access reviews and incident response, with a help-desk queue whose tickets only close when the directory and the audit log show the work was done |
| [🛡️ CyberGuard AI](https://github.com/pitchiluxe/CyberGuard-AI) | ![Shipped](https://img.shields.io/badge/-shipped-4ec9b0?style=flat-square) | AI-Powered SOC Monitoring for Windows — real Event Log + Sysmon data, classified by a local LLM |
|| [🌐 CompTIA Security+ / Network+ Zero-to-Hero 3D Lab](https://github.com/pitchiluxe/CompTIA-SecurityPlus-Zero-to-Hero-3D-Lab) | ![In progress](https://img.shields.io/badge/-in%20progress-9e9e9e?style=flat-square) | Interactive 3D cybersecurity training platform — from networking fundamentals to Security+ and junior SOC/IAM readiness, with animated landing page and safe simulations |
| [📡 CCNA Certification](https://github.com/pitchiluxe/ccna-certification) | ![In progress](https://img.shields.io/badge/-in%20progress-9e9e9e?style=flat-square) | Comprehensive training resources for Cisco CCNA networking certification |
| [☁️ Cloud Engineer Real World Lab Workflows](https://github.com/pitchiluxe/Cloud_Engineer_Real_World_Lab_Workflows) | ![In progress](https://img.shields.io/badge/-in%20progress-9e9e9e?style=flat-square) | Real-world cloud engineering lab workflows and exercises |
| [💻 Amazon IT Support Engineer I Lab Workflows](https://github.com/pitchiluxe/Amazon_IT_Support_Engineer_I_Lab_Workflows) | ![In progress](https://img.shields.io/badge/-in%20progress-9e9e9e?style=flat-square) | Hands-on lab workflows for Amazon IT Support Engineer I certification prep |

---

### 🔑 IAM Range — what it is, and what it taught me

[**IAM Range**](https://github.com/pitchiluxe/iam-range) is a standalone workstation you install and sign into: a simulated Windows desktop with Active Directory Users and Computers, a PowerShell terminal, a ticket queue, Okta and Entra tenants, and the reporting tools an identity engineer actually works in. It ships one administrator account and an empty domain — the same thing you would find on a freshly promoted domain controller — and everything after that is built by hand.

**Skills it demonstrates**

- **Directory design.** Building an OU structure for delegation rather than for the org chart, and a group model where entitlement is legible and revocable.
- **Joiner, mover, leaver.** Onboarding an account that can actually sign in; transferring somebody by *adding and removing*; offboarding through every route — on-premises, tenant, sessions, and inside the applications.
- **Privileged access management.** Finding standing privilege, replacing it with eligibility, activating a role for a change window, and approving somebody else's request.
- **Hybrid identity.** Working out which side is authoritative, explaining sync latency, closing the leaver gap with SCIM, and resolving duplicate identities from a failed soft match.
- **Access certification.** Running a review campaign end to end — scope, decide, complete — where revocations only apply on completion.
- **Emergency access.** Standing up break-glass accounts, excluding them from conditional access, alerting on them, then breaking MFA tenant-wide and recovering with them.
- **Investigation and evidence.** Querying the audit log with `field:value` terms, exporting to a spreadsheet, redacting what should not travel, and producing a portfolio pack backed by log entries.

**How the scenarios come from real incidents**

Every lesson is built around a failure that happens in production, not an exercise invented to be gradeable:

| The scenario | Why it is in the lab |
|---|---|
| A transfer where access was added and never removed | How privilege quietly accumulates until somebody has everything they have ever done |
| "I disabled them and they can still sign in" | Directory sync latency and live sessions — the question a service desk is asked and usually cannot answer |
| A leaver still working inside a SaaS application | Deprovisioning stops at the identity provider unless SCIM is switched on. The most common finding in a leaver audit |
| A review where every reviewer decided and nobody completed the campaign | The commonest way certification removes no access at all |
| Permanent Global Admin used twice a year | Standing privilege is a permanent risk for an occasional convenience |
| The identity provider rejecting every MFA challenge | Emergency access nobody has exercised is a belief, not a control |
| One person with two cloud objects | A failed soft match, and what it costs to clean up afterwards |

**The part I am most pleased with**

Work cannot be marked complete by saying so. Closing a ticket runs a set of checks against the directory, and a ticket where the work was not done **stays open** with the reasons listed. Progress through the course is derived the same way — from the estate you built, the audit log, the PIM assignments and the tenants — never from a checkbox. That constraint changed how I work: it is the difference between *"I disabled the account"* and *"here is the account, the sessions I revoked, the application it was deprovisioned from, and the log entries for each"*.

That is also what comes out of it — an evidence pack listing the tasks completed, the audit entries behind each claim, and **what is still outstanding**, because a document that only lists successes is a brochure.

---

## 🎯 Career Focus

Transitioning into **cybersecurity** with a deep specialization in **identity and access management** and **cloud engineering**.

## 🛠️ Skills & Technologies

`Identity & Access Management` · `Active Directory` · `Entra ID` · `Okta` · `SAML / OIDC` · `SCIM` · `PIM` · `Access Certification` · `Cybersecurity` · `SOC Operations` · `Cloud Engineering` · `AWS` · `Azure` · `Python` · `TypeScript` · `React` · `FastAPI` · `LLM Integration` · `MITRE ATT&CK` · `Sysmon` · `Windows Event Logging` · `Networking` · `CCNA`

## 📬 Let's Connect

- [GitHub](https://github.com/pitchiluxe)
- [LinkedIn](https://www.linkedin.com/in/erickomari/)
- [Website](https://technobiztrader.net)
