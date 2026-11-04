# Risk Register: SOC and Monitoring Environment

Scope and assumptions are in [01-organization-profile/scope-and-assumptions.md](../01-organization-profile/scope-and-assumptions.md). All ratings are illustrative.

## Rating method

- Likelihood: 1 (rare) to 5 (almost certain)
- Impact: 1 (minor) to 5 (severe)
- Score: likelihood x impact. 1-6 Low, 7-12 Medium, 13-25 High
- Method follows the approach in NIST SP 800-30

## Register

| ID | Risk | Asset | Likelihood | Impact | Score | Rating | Treatment | Owner |
|----|------|-------|-----------:|-------:|------:|--------|-----------|-------|
| R01 | Shared or weak credentials let an unauthorized person into video or access control systems | Monitoring platforms | 4 | 4 | 16 | High | Unique accounts, MFA, quarterly access reviews | SOC Manager |
| R02 | Vendor remote access is misused or goes unmonitored | Vendor accounts | 3 | 5 | 15 | High | Time-limited vendor accounts, session logging, approval before each use | IT Security |
| R03 | Phishing of SOC staff leads to stolen credentials | Staff accounts | 4 | 4 | 16 | High | Phishing awareness training, email filtering, MFA | IT Security |
| R04 | Unpatched camera, recorder, or network device firmware is exploited | Cameras and recorders | 4 | 4 | 16 | High | Patch schedule, inventory of device firmware, network segmentation | IT Operations |
| R05 | A camera or alarm endpoint goes offline and nobody notices | Surveillance and alarm endpoints | 3 | 4 | 12 | Medium | Automated health alerts, daily endpoint check | SOC Supervisor |
| R06 | An incident is not logged or escalated correctly because of a missed handoff | Incident records | 4 | 3 | 12 | Medium | Standard handoff template, supervisor review of shift logs | SOC Supervisor |
| R07 | Incident response and continuity procedures are outdated or untested | Procedures | 3 | 4 | 12 | Medium | Annual review, tabletop exercise | Security Manager |
| R08 | The access control platform fails with no fallback procedure | Access control platform | 2 | 5 | 10 | Medium | Documented manual fallback, tested backups | IT Operations |
| R09 | Sensitive video footage is disclosed or kept longer than allowed | Video recordings | 2 | 4 | 8 | Medium | Retention schedule, access limits on exports | Compliance Lead |
| R10 | An insider misuses badge or video data | Badge and video data | 2 | 4 | 8 | Medium | Role-based access, audit logs reviewed monthly | Compliance Lead |

## Summary

- High: 4 risks (R01 to R04)
- Medium: 6 risks (R05 to R10)
- Low: none at this stage
