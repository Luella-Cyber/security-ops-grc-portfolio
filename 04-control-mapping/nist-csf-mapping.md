# Control Mapping: Risks and Policies to NIST CSF 2.0

This maps each risk in [02-risk-assessment/risk-register.md](../02-risk-assessment/risk-register.md) to a NIST Cybersecurity Framework 2.0 function and category, and to the policy that addresses it. It is a portfolio exercise and does not describe any real organization.

## CSF 2.0 functions used

| Function | Purpose |
|---|---|
| Govern (GV) | Set and oversee cybersecurity risk strategy, roles, policy, and supply chain risk |
| Identify (ID) | Understand assets and risks |
| Protect (PR) | Put safeguards in place |
| Detect (DE) | Find possible attacks and compromises |
| Respond (RS) | Act on detected incidents |
| Recover (RC) | Restore normal operations |

## Mapping

| Risk | Risk summary | CSF function | CSF category | Addressed by | Coverage |
|---|---|---|---|---|---|
| R01 | Shared or weak credentials | Protect | PR.AA Identity Management, Authentication, and Access Control | Access Control Policy (sections 3.1, 3.2, 3.4) | Covered |
| R02 | Vendor remote access misused | Govern, Protect | GV.SC Supply Chain Risk Management; PR.AA | Access Control Policy (section 3.6); Incident Response Policy (section 4.7) | Covered |
| R03 | Phishing of SOC staff | Protect, Detect | PR.AT Awareness and Training; DE.AE Adverse Event Analysis | Incident Response Policy (sections 4.1, 4.2) | Partial: reporting is covered, awareness training is not |
| R04 | Unpatched device firmware | Identify, Protect | ID.AM Asset Management; PR.PS Platform Security | None yet | Gap |
| R05 | Offline camera or alarm endpoint | Detect | DE.CM Continuous Monitoring | Incident Response Policy (severity table, section 4.4) | Covered |
| R06 | Missed handoff, incident not escalated | Respond | RS.MA Incident Management; RS.CO Incident Response Reporting and Communication | Incident Response Policy (sections 4.2, 4.4, 4.6) | Covered |
| R07 | Outdated or untested procedures | Respond, Identify | RS.MA; ID.IM Improvement | Incident Response Policy (sections 4.8, 4.9) | Covered |
| R08 | Access control platform failure, no fallback | Protect, Recover | PR.IR Technology Infrastructure Resilience; RC.RP Incident Recovery Plan Execution | None yet | Gap |
| R09 | Video footage disclosed or kept too long | Protect, Govern | PR.DS Data Security; GV.PO Policy | Access Control Policy (section 3.8) | Partial: exports are controlled, retention is not |
| R10 | Insider misuse of badge or video data | Protect, Detect | PR.AA; DE.CM | Access Control Policy (sections 3.7, 3.8) | Covered |

## Coverage summary

- Covered: 6 risks (R01, R02, R05, R06, R07, R10)
- Partial: 2 risks (R03, R09)
- Gap: 2 risks (R04, R08)

## Gaps and next steps

1. **Patch and firmware management (R04):** write a policy covering device inventory, patch schedules, and network segmentation.
2. **Resilience and recovery (R08):** document a manual fallback procedure and a backup testing schedule.
3. **Awareness training (R03):** add a phishing awareness training requirement.
4. **Data retention (R09):** define how long video footage and badge records are kept, and how they are disposed of.
