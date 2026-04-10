# TechCorp SA Post-Breach Cyber Resilience Assessment
## NIST CSF 2.0 | ISO 27001:2022 | Based on Real SA FinTech Breach Pattern

![Status](https://img.shields.io/badge/Status-Live-brightgreen)
![NIST CSF](https://img.shields.io/badge/NIST-CSF%202.0-blue)
![ISO 27001](https://img.shields.io/badge/ISO-27001:2022-teal)

## 🟢 Live Dashboard

**[scottie222.github.io/TechCorp-Resilience-Assessment](https://scottie222.github.io/TechCorp-Resilience-Assessment/)**

No install. No login. Click the link — full interactive dashboard loads instantly.

---

## What This Project Is

A post-breach cyber resilience assessment dashboard built around a
real SA FinTech ransomware incident scenario. A targeted ransomware
attack encrypted TechCorp's core financial and customer systems —
this dashboard presents the full post-breach gap assessment, NIST
CSF 2.0 maturity scoring, 20 control findings, live financial
impact modeller and 90-day remediation roadmap.

Grounded in real SA breach statistics R53.1 million average SA
data breach cost (IBM 2024).

---

## Dashboard Features

| Tab | What It Shows |
|---|---|
| **Overview** | Incident timeline, NIST CSF maturity before vs target, root cause analysis |
| **NIST CSF 2.0** | Full maturity scoring across all 6 functions — GV, ID, PR, DE, RS, RC |
| **Findings** | 20 control findings with NIST reference, ISO 27001 clause, severity and status |
| **Cost Impact** | Live financial modeller — adjust sliders to calculate total exposure |
| **Roadmap** | 3-phase 90-day remediation plan with maturity targets |

---

## The Incident

A targeted ransomware attack on TechCorp SA FinTech:

- **02:17**  Finance employee clicks phishing email, credentials harvested
- **06:45**  Lateral movement across flat network to core ERP system
- **09:23**  Ransomware deployed, 847 files encrypted, R2.1M ransom demanded
- **Day 1**  External forensics engaged, SAPS cybercrime notified
- **Day 3**  POPIA Section 22 notification submitted, 14,200 records exposed
- **Day 14** Systems restored from clean backups. Ransom NOT paid.

**Root causes:** No MFA on VPN · Flat network (no segmentation) · No EDR deployed

---

## Key Findings

| Finding | Severity | NIST CSF | ISO 27001 |
|---|---|---|---|
| No MFA on VPN and critical systems | Critical | PR.AC | A.8.5 |
| Flat network no segmentation | Critical | PR.PT | A.8.22 |
| No EDR deployed | Critical | DE.CM | A.8.7 |
| No SIEM or centralised logging | Critical | DE.AE | A.8.15 |
| No tested incident response plan | Critical | RS.RP | A.5.24 |
| No security awareness training | Critical | PR.AT | A.6.3 |
| Backups untested 14-day recovery | Critical | RC.RP | A.8.13 |

---

## NIST CSF 2.0 Maturity

| Function | Pre-Breach | 90-Day Target |
|---|---|---|
| GV — Govern | 1.0 | 3.0 |
| ID — Identify | 1.5 | 2.5 |
| PR — Protect | 1.0 | 3.5 |
| DE — Detect | 0.5 | 3.0 |
| RS — Respond | 1.0 | 2.5 |
| RC — Recover | 0.5 | 2.5 |

---

## Related GRC Portfolio Projects

| Project | Description |
|---|---|
| [StandardBank-Risk-Assessment](https://github.com/Scottie222/StandardBank-Risk-Assessment) | ISO 27001 Risk Assessment Live dashboard |
| [RetailCo-Security-Awareness](https://github.com/Scottie222/RetailCo-Security-Awareness) | Security Awareness + AI Detector Live dashboard |
| [CloudSec-Assessment-SA](https://github.com/Scottie222/CloudSec-Assessment-SA) | Cloud Security CIS Benchmarks AWS & Azure |
| [LifeHealthcare-BCP](https://github.com/Scottie222/LifeHealthcare-BCP) | BCP/DR — Life Healthcare ransomware 2020 |
| [VendorRisk-SA](https://github.com/Scottie222/VendorRisk-SA) | Third-Party Vendor Risk — ISO 27001 A.5.19 |

---

*Built by Bakithi Scott Ngcampalala | Junior Security Administrator @ Open Vantage*
*LinkedIn: https://www.linkedin.com/in/bakithi-scott-ngcampalala-0051a4105*