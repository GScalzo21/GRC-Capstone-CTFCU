<p align="center">
  <img src="./assets/hero-banner.png" alt="Cumberland Trust Federal Credit Union — GRC Program Capstone" width="100%">
</p>

<h1 align="center">A Complete Governance, Risk & Compliance Program</h1>

<p align="center">
  <em>A GRC engagement built end-to-end for a $2B regional credit union — aligned to NIST CSF 2.0, ISO/IEC 27001:2022, FFIEC, and GLBA.</em>
</p>

<p align="center">
  <strong>Author:</strong>&nbsp;Giuseppe Scalzo&nbsp;·&nbsp;ISO 27001 Lead Auditor&nbsp;·&nbsp;B.S. Cybersecurity <em>(Summa Cum Laude)</em><br>
  <a href="https://linkedin.com/in/giuseppe-scalzo-">LinkedIn</a>&nbsp;·&nbsp;<a href="https://github.com/GScalzo21">GitHub</a>&nbsp;·&nbsp;GScalzo21@gmail.com
</p>

---

## The Engagement

In **Q1 2026**, Cumberland Trust Federal Credit Union (CTFCU) — a $2B regional credit union serving 85,000 members across Tennessee, Kentucky, and Alabama — experienced a phishing incident that resulted in one compromised employee account. The account was disabled within four hours and no member data was exfiltrated, but the incident surfaced during the credit union's annual **NCUA examination** and triggered findings around cybersecurity governance, third-party risk oversight, and incident response maturity.

In response, the CTFCU Board of Directors authorized an **18-month engagement** to design and deliver a formal Information Security Management System (ISMS), aligned to **NIST CSF 2.0** and **ISO/IEC 27001:2022**, with the goal of pursuing ISO 27001 certification by September 2027.

I was engaged as the **fractional GRC consultant** responsible for designing the program: charter, scope, risk methodology and register, control framework mapping, third-party risk model, physical security integration, incident response plan, and a phased implementation roadmap.

---

## What Sets This Engagement Apart

Most credit union security programs treat cyber risk and physical risk as separate disciplines. They sit in different departments, report to different executives, and never converge. The CTFCU program treats them as **one converged risk function** — because real incidents (phishing leading to insider exfiltration, branch-level workplace violence, third-party compromise) don't respect those silos.

<p align="center">
  <img src="./assets/two-worlds.png" alt="Two Worlds of Risk - Cyber and Physical Convergence" width="80%">
</p>

This convergence is the engagement's defining choice. It reflects how modern enterprise risk actually works — and it's why CTFCU's program includes a **Behavioral Threat Assessment Team** chaired by HR, a **workplace violence prevention** annex aligned to NIOSH and NTAC, and a **branch security** framework alongside the standard cyber GRC stack.

---

## Risk Posture — Top 11 Residual Risks

The full risk assessment identified 15 risks across cyber, physical, behavioral, regulatory, and operational categories. After controls are applied, the residual risk profile looks like this:

<p align="center">
  <img src="./assets/risk-heatmap.png" alt="CTFCU Risk Heatmap" width="90%">
</p>

The two highest residual risks — **Ransomware (R1)** and **Phishing Credential Compromise (R4)** — drive the Phase 2 control sequence: SIEM deployment, MFA on all administrative systems, immutable backup tier, and phishing-resistant authentication.

| Rank | Risk | Residual | Owner |
|---|---|---|---|
| 1 | **R1** · Ransomware on production systems | Critical (20) | CIO |
| 2 | **R4** · Phishing credential compromise | Critical (20) | InfoSec Manager |
| 3 | **R7** · Critical third-party compromise | Very High (16) | CRO |
| 4 | **R2** · Insider privileged user abuse | High (12) | CIO + HR |
| 5 | **R8** · Unpatched critical vulnerabilities | High (12) | IT Ops Manager |
| 6 | **R15** · Workplace violence at branch or HQ | High (10) | HR + Physical Security |

📊 **Full quantitative register:** [`CTFCU-Risk-Register.xlsx`](./CTFCU-Risk-Register.xlsx) — 15 risks, full likelihood × impact scoring, treatment plan, $893K capital and $387K annual operating roll-up.

---

## Frameworks Applied

The program is designed against five overlapping frameworks chosen for the credit union sector:

| Framework | Purpose |
|---|---|
| **NIST Cybersecurity Framework 2.0** | Strategic outcome model — Govern, Identify, Protect, Detect, Respond, Recover |
| **ISO/IEC 27001:2022** | Formal ISMS design with all 93 Annex A controls assessed |
| **FFIEC Cybersecurity Assessment Tool** | Financial-sector maturity model |
| **GLBA Safeguards Rule** | Federal financial privacy compliance (16 CFR Part 314) |
| **NCUA Cybersecurity Expectations** | Credit union–specific federal oversight |

Supporting references include NIST SP 800-30 (risk methodology), ISO/IEC 27005 (risk management process), NTAC behavioral threat assessment, MITRE ATT&CK, and CISA Cross-Sector Cybersecurity Performance Goals.

---

## Implementation — 18 Months in Three Phases

<p align="center">
  <img src="./assets/roadmap.png" alt="18-Month Implementation Roadmap" width="95%">
</p>

**Phase 1 — Foundation** (Apr–Sep 2026) · Governance, risk methodology, register, and six core policies. The "Plan" half of the ISO 27001 PDCA cycle.

**Phase 2 — Controls Buildout** (Jul 2026–May 2027) · Statement of Applicability across all 93 Annex A controls, SIEM and IAM deployment, third-party risk program, physical security and workplace violence prevention program, IR plan with tabletop exercises.

**Phase 3 — Audit & Certification** (Apr–Sep 2027) · Internal audit cycle, management review, ISO 27001 Stage 1, remediation, Stage 2 audit and certification.

**Total program cost:** ~$893K capital expense + ~$387K annual operating, including SIEM platform, IAM/PAM tooling, immutable backups, ATM anti-skim retrofit, branch hardening, training, cyber insurance, and external audit fees.

---

## How Success Is Measured

The program is built to be measurable. Key metrics reported quarterly to the Board:

| Metric | Baseline | Month 18 Target |
|---|---|---|
| FFIEC cybersecurity maturity | Evolving | Advanced |
| ISO 27001 Annex A controls implemented | 24 of 93 (26%) | 82 of 93 (88%) |
| MFA coverage on administrative systems | ~30% | 100% |
| Phishing simulation click rate | Not measured | < 5% |
| Patch SLA compliance (Critical / 14-day) | Not measured | ≥ 95% |
| Third-party vendors with current SOC 2 / ISO evidence | 0% | 100% of Tier 1–2 |
| Mean time to detect (Tier 1 systems) | Not measured | < 4 hours |
| Annual tabletop exercises conducted | 0 | ≥ 2 |

---

## Lessons Learned

A few things this engagement reinforced that don't always show up in framework documentation:

- **Frameworks are scaffolding, not the building.** ISO 27001 tells you *what* an ISMS needs. It doesn't tell you how to actually get a credit union with 340 employees and 60+ vendors to operate it. The implementation roadmap matters more than the SoA.
- **Physical risk belongs on the same risk register as cyber risk.** Separating them creates governance gaps that real incidents will exploit. Workplace violence, branch robbery, and ATM tampering are information security risks too.
- **Vendor risk is the loudest underestimated risk.** CTFCU has 66 third parties. Six are critical. None had formal risk tiering at engagement start. This is the most common gap in regional financial institutions, and the hardest to fix retroactively because contracts are already signed.
- **Sustainability matters more than ambition.** The cleanest ISMS in the world is useless if it requires the consultant to operate it. Every deliverable in this engagement was built to be owned by internal CTFCU staff by Month 18.

---

## Beyond Month 18

ISO 27001 certification is not the finish line — it's the baseline. The program is designed to continue under CTFCU's own ownership through the annual ISO surveillance audit cycle, the quarterly Information Security Steering Committee, and the ongoing Plan-Do-Check-Act cycle defined in ISO 27001 Clause 10. Continuous improvement is the point of the framework, not a side effect.

---

## About the Author

I built this capstone to demonstrate end-to-end GRC delivery — not just framework knowledge. The methodology applies across industries; the artifacts here would work substantially the same way for a hospital system, a SaaS company, or a manufacturing firm. I chose a credit union because the regulatory stack is rich and the convergence of cyber + physical risk is real.

My background sits on two sides of the risk house that rarely appear on the same résumé: **eleven years of investigations** — five years as a Detective in the NYPD's Domestic Violence Unit, currently a School Resource Officer in the Metro Nashville Police Department's School Safety Division — paired with **modern GRC and security operations work** as an **ISO 27001 Lead Auditor**, a B.S. in Cybersecurity *summa cum laude*, a recent Cybersecurity Internship in Vulnerability Management & GRC at Log(N) Pacific, and a 2nd place finish at the **Counterattack Cyber Solutions** incident response tabletop competition.

That dual background is why this capstone treats physical security and workplace violence prevention as first-class GRC concerns, not afterthoughts.

I'm available for **remote part-time, contract, and fractional GRC, risk, threat management, and compliance engagements**. Reach me at **GScalzo21@gmail.com** or via [LinkedIn](https://linkedin.com/in/giuseppe-scalzo-).

---

<p align="center"><em>Cumberland Trust Federal Credit Union is a fictional entity created for this engagement. All frameworks, controls, methodologies, costs, and risk treatments are real and current as of 2026.</em></p>
