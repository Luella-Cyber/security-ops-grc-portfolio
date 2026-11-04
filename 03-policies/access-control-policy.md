# Access Control Policy

| | |
|---|---|
| Document owner | Security Manager |
| Version | 1.0 |
| Effective date | November 3, 2026 |
| Review cycle | Annual |
| Related risks | R01, R02, R10 (see 02-risk-assessment/risk-register.md) |
| Framework reference | NIST CSF 2.0: PR.AA (Identity Management, Authentication, and Access Control) |

This is a sample policy written for a portfolio case study. It does not describe any real organization's policy.

## 1. Purpose

To make sure only authorized people can reach monitoring, video, alarm, and access control systems, and that their access matches what their job requires.

## 2. Scope

This policy covers all employees, contractors, and vendors who use SOC monitoring systems, video platforms, alarm software, access control platforms, and the accounts and devices that connect to them.

## 3. Policy statements

1. **Unique accounts.** Every user has their own account. Shared or generic accounts are not allowed.
2. **Strong authentication.** Multi-factor authentication is required for remote access and for administrator accounts.
3. **Least privilege.** Users receive the minimum access needed for their role. Access is granted through a documented request and manager approval.
4. **Access reviews.** Managers review user access to monitoring and access control systems every quarter. Access that is no longer needed is removed within 5 business days of the review.
5. **Joiners, movers, and leavers.** Access is created when a person starts, updated when their role changes, and removed on or before their last day.
6. **Vendor access.** Vendor accounts are time-limited, approved before each use, and logged. Vendor sessions are reviewed after the work is done.
7. **Privileged activity.** Administrator actions are logged, and logs are reviewed monthly.
8. **Badge and video data.** Exporting video or badge records requires a documented business reason and supervisor approval.

## 4. Roles and responsibilities

| Role | Responsibility |
|---|---|
| Security Manager | Owns this policy and approves exceptions |
| Managers | Approve access requests and complete quarterly reviews |
| IT Security | Configures authentication, monitors logs, and removes access |
| Employees and vendors | Protect their credentials and report suspected misuse |

## 5. Exceptions

Exceptions need written approval from the Security Manager, a stated reason, and an end date. Approved exceptions are recorded and reviewed at each quarterly access review.

## 6. Enforcement

Violations may lead to loss of access and disciplinary action, up to and including termination of employment or contract.

## 7. Review

The Security Manager reviews this policy once a year and after any significant incident or system change.
