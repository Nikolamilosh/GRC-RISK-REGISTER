# Information Security Risk Register — Miloshevski Health Partners (Sample Project)

A sample enterprise risk register built using a **NIST SP 800-30** aligned methodology, for a fictional mid-size healthcare organization. Built as a portfolio project to demonstrate GRC (Governance, Risk & Compliance) skills: risk identification, qualitative risk scoring, treatment planning, and reporting.

## Scenario

**Miloshevski Health Partners** is a fictional healthcare provider with ~450 employees, 6 clinic locations, a single EHR platform, and a cloud-hosted patient portal. All company details, systems, and risks in this project are fictional and built for demonstration purposes — see the workbook's README tab for the full disclosure.

## Methodology

Risk is scored qualitatively using:

```
Risk Score = Likelihood (1–5) x Impact (1–5)
```

| Score | Risk Level |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–15 | High |
| 16–25 | Critical |

Full definitions for the likelihood and impact scales are documented on the **Methodology** tab of the workbook, based on NIST SP 800-30 Rev. 1 ("Guide for Conducting Risk Assessments").

## What's in this repo

```
risk-register/
├── docs/
│   └── risk_register.xlsx      # The full workbook (README, Methodology, Risk Register, Risk Matrix)
├── templates/                  # (blank version, coming soon)
└── README.md
```

### Workbook contents
- **README** — project overview and assumptions
- **Methodology** — likelihood/impact scales and risk level thresholds
- **Risk Register** — 15 identified risks across technical, physical, insider, third-party, and regulatory categories, each scored with a formula-driven risk score, treatment strategy, owner, and target date
- **Risk Matrix** — a 5x5 heat map visualizing where every risk falls by likelihood and impact

## Key risks identified (sample)

| Risk ID | Threat Event | Risk Level |
|---|---|---|
| R-001 | Ransomware attack encrypts EHR database | Critical |
| R-002 | Phishing leads to credential compromise | Critical |
| R-012 | Account takeover due to lack of MFA on VPN | Critical |
| R-003 | Cloud storage bucket misconfigured to public access | High |
| R-006 | Privilege escalation via weak admin password | High |

Full list of all 15 risks is in the workbook.

## Skills demonstrated

- Qualitative risk assessment (NIST SP 800-30)
- Risk scoring and heat-map visualization
- Risk treatment planning (mitigate / accept / transfer / avoid)
- Healthcare-sector risk context (HIPAA Security Rule considerations)
- Spreadsheet modeling with formulas, conditional formatting, and data validation

## About me

Recent Cybersecurity B.S. graduate building a GRC-focused portfolio. Connect with me on [LinkedIn](https://www.linkedin.com/in/nikola-miloshevski-1a455a243/).

---
*This is a demonstration project. Miloshevski Health Partners is fictional; no real company, system, or incident data was used.*
