# NovaCrest Financial Services Ltd — ISO 27001:2022 ISMS Portfolio

> **Personal portfolio project demonstrating end-to-end ISO 27001:2022 ISMS design, implementation, internal audit and continual improvement for a simulated UK financial services organisation.**

---

## About This Project

This repository documents a complete Information Security Management System (ISMS) built from the ground up for **NovaCrest Financial Services Ltd** — a fictional mid-sized UK financial services firm providing retail banking, wealth management and payment processing to approximately 85,000 customers.

The project was completed independently to demonstrate practical ability to **develop, implement, audit and maintain** an ISMS across the full ISO 27001:2022 lifecycle — the core competency required in GRC Analyst and Information Security Analyst roles.

**Regulatory context simulated:** ISO 27001:2022 | PCI DSS v4.0 | UK GDPR | FCA Consumer Duty | NIS Regulations 2018

---

## What This Covers

| Phase | Activity | Deliverable |
|-------|----------|-------------|
| **Develop** | Defined ISMS scope, context and interested parties | ISMS Scope & Context Document |
| **Develop** | Assessed current state against ISO 27001:2022 | Gap Analysis Report |
| **Develop** | Identified, scored and treated 22 information security risks | Risk Register (22 risks, likelihood × impact scoring) |
| **Develop** | Assessed applicability of all 93 Annex A controls | Statement of Applicability |
| **Develop** | Wrote core governance policies | Information Security Policy, Incident Response Policy, Data Classification Policy |
| **Implement** | Mapped controls to business context and assigned owners | SoA with implementation status tracking |
| **Audit** | Conducted simulated internal audit against clauses 4–10 | Internal Audit Findings Report |
| **Maintain** | Identified corrective actions and improvement priorities | Prioritised recommendations with owners and target dates |

---

## Documents in This Repository

```
NovaCrest-ISMS-Portfolio/
│
├── 01_ISMS_Scope_and_Context.docx          ← Clause 4 — scope, context, interested parties
├── 02_Gap_Analysis_Report.docx             ← Current state vs ISO 27001:2022 clauses 4–10
├── 03_Risk_Register.xlsx                   ← 22 risks, scored, treated, colour-coded by level
├── 04_Statement_of_Applicability.xlsx      ← All 93 Annex A controls assessed
├── 05_Information_Security_Policy.docx     ← Clause 5.2 — board-approved IS policy
├── 06_Incident_Response_Policy.docx        ← Annex A 5.24–5.28 — P1–P4 classification + FCA notification
├── 07_Data_Classification_Policy.docx      ← Annex A 5.12–5.13 — 4-tier classification scheme
└── 08_Internal_Audit_Findings_Report.docx  ← Clause 9.2 — full internal audit, 12 findings
```

---

## Key Findings from the Internal Audit

The internal audit identified **12 findings** across the ISMS:

- **2 Major Non-Conformances:** Absence of a documented risk assessment methodology (Clause 6.1); no established internal audit programme prior to this audit (Clause 9.2)
- **5 Minor Non-Conformances:** Control ownership gaps in SoA (5.3); no competence framework (7.2); security awareness completion not evidenced (7.3); no document register (7.5); no formal change management process (8.1)
- **5 Observations:** Board ISMS reporting cadence (5.1); improvement tracking mechanism (10.1); management review not yet scheduled (9.3); ISMS KPI framework (9.1); supplier review process (8.2)

**Overall maturity assessment:** DEVELOPING — strong governance foundations in place; focused remediation required before certification readiness.

---

## Risk Register Summary

22 risks identified and scored across the following categories:

| Risk Category | Risks | Highest Inherent Level |
|---------------|-------|----------------------|
| Third-party / supply chain | 4 | CRITICAL |
| Cloud infrastructure (Azure) | 3 | HIGH |
| Customer data / GDPR | 3 | CRITICAL |
| Payment processing / PCI DSS | 2 | CRITICAL |
| Insider threat | 2 | HIGH |
| Business continuity / DR | 2 | HIGH |
| Identity & access management | 2 | HIGH |
| Physical / endpoint security | 2 | HIGH |
| Regulatory compliance (FCA) | 2 | HIGH |

Scoring methodology: **Likelihood (1–5) × Impact (1–5)** | CRITICAL ≥16 | HIGH ≥10 | MEDIUM ≥5 | LOW <5

---

## What I Learned

Working through this project gave me practical experience in:

- Scoping an ISMS for a complex, regulated organisation and identifying all relevant interested parties under ISO 27001 Clause 4
- Applying the ISO 27001:2022 risk methodology — defining criteria, scoring consistently, and producing defensible risk treatment decisions
- Mapping all 93 Annex A controls to a real business context and justifying inclusion/exclusion decisions
- Writing professional governance policies that meet both ISO 27001 control requirements and UK regulatory obligations (GDPR, FCA, PCI DSS)
- Conducting a structured internal audit — formulating findings, classifying conformances and non-conformances, and producing recommendations that drive genuine improvement

---

## Frameworks & Standards Applied

- **ISO 27001:2022** — primary standard
- **ISO 27002:2022** — control guidance for Annex A
- **UK GDPR / Data Protection Act 2018** — data classification and breach notification
- **FCA Operational Resilience Framework** — incident response notification timescales
- **PCI DSS v4.0** — payment card data protection requirements
- **NCSC CAF** — supplementary control guidance for network and system security

---

## About Me

**Afrid Shaik** — Cyber GRC & Compliance Analyst

1.5+ years professional experience across GRC Analyst and Information Security Analyst roles. MSc Cybersecurity (Advanced Research, 2:1) — University of Hertfordshire. Certifications: CompTIA Security+, CEH, OneTrust TPRM Expert. ISO 27001 Lead Implementer in progress.

- LinkedIn: [www.linkedin.com/in/afridshaik-grcuk]
- GitHub: [github.com/Afridi4u14]
- Email: cafridi4u@gmail.com

---

*This is an independent portfolio project. NovaCrest Financial Services Ltd is a fictional organisation created solely for the purpose of demonstrating GRC competency. All scenarios, risks and findings are simulated.*
