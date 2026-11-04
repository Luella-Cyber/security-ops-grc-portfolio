# Incident Response Policy

| | |
|---|---|
| Document owner | Security Manager |
| Version | 1.0 |
| Effective date | November 3, 2026 |
| Review cycle | Annual, plus after any major incident |
| Related risks | R03, R05, R06, R07 (see 02-risk-assessment/risk-register.md) |
| Framework reference | NIST CSF 2.0: DE.AE (Adverse Event Analysis), RS.MA (Incident Management), RS.CO (Incident Response Reporting and Communication) |

This is a sample policy written for a portfolio case study. It does not describe any real organization's policy.

## 1. Purpose

To make sure security incidents affecting monitoring, video, alarm, and access control systems are found quickly, recorded accurately, escalated to the right people, and reviewed so the same problem does not repeat.

## 2. Scope

This policy covers security events and incidents involving SOC systems, the staff who operate them, and any vendors or contractors with access to them.

## 3. Severity levels

| Level | Description | Example | Escalate within |
|---|---|---|---|
| High | Active threat or loss of a critical monitoring function | Compromised administrator account; access control platform down | 15 minutes |
| Medium | Confirmed problem with limited effect | Camera or alarm endpoint offline; repeated failed logins | 1 hour |
| Low | Minor event, no service effect | Single failed login; suspicious email reported and blocked | End of shift |

## 4. Policy statements

1. **Detect and report.** Anyone who sees a possible incident reports it to the SOC supervisor right away. Staff are not penalized for reporting in good faith.
2. **Log every incident.** The first person to notice records the date and time, what was observed, systems affected, and who was told. Records are written in plain language and kept in the incident ticketing tool.
3. **Triage.** The supervisor assigns a severity level using the table above and names an owner for the incident.
4. **Escalate.** Incidents go to the right team within the time shown for their severity level. Escalations are recorded, including who was contacted and when.
5. **Contain and recover.** The incident owner limits the damage first, such as disabling an account or isolating a device, then restores normal service and confirms it works.
6. **Shift handoff.** At every shift change, the outgoing team gives the incoming team a written summary of open incidents, pending actions, and escalation status, using the standard handoff template. The incoming supervisor confirms receipt.
7. **Vendor involvement.** Vendors are contacted through approved channels only. Vendor work is logged and reviewed afterward.
8. **Review.** Every High incident gets a written review within 10 business days that covers what happened, how it was handled, and what will change. Medium incidents are reviewed monthly in a group.
9. **Testing.** This policy and its contact list are tested at least once a year with a tabletop exercise. Findings are tracked until closed.

## 5. Roles and responsibilities

| Role | Responsibility |
|---|---|
| SOC staff | Detect, report, and log events; follow the handoff template |
| SOC supervisor | Triage, assign severity, escalate, and review shift logs |
| Security Manager | Owns this policy, leads High incidents, and approves exceptions |
| IT Security | Investigates and contains technical incidents |
| Vendors | Report problems found during their work and follow approved procedures |

## 6. Exceptions

Exceptions need written approval from the Security Manager, a stated reason, and an end date.

## 7. Enforcement

Failing to report or log a known incident may lead to retraining or disciplinary action.

## 8. Review

The Security Manager reviews this policy once a year and after any High incident.
