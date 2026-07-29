# Scimly Access Review Report

**Organization:** Your Organization
**Generated:** 22/7/2026, 7:28:14 pm
**Review date:** 2026-07-21

## Executive Summary

- **Overall readiness:** 🟡 47/100 (Needs attention)
- **Users analyzed:** 125000
- **Critical findings:** 🔴 28364 high risk · 🟠 63814 medium risk · 🟢 32822 low risk
- **Estimated monthly savings:** $29,11,387
- **Estimated annual savings:** $3,49,36,644

**Top risks**

- 🟠 63430 Stale user accounts
- 🔴 48402 Paid inactive accounts
- 🔴 31779 Stale admin accounts
- 🔴 27904 Admins without MFA
- 🟠 18815 Missing managers
- 🟠 12362 Missing SCIM IDs
- 🟢 6473 Missing department info
- 🟠 1015 Duplicate email addresses

## Coverage & Composition

| Metric | Value |
|---|---|
| MFA coverage (admins) | 33% (13903 of 41807) |
| SCIM ID coverage | 90% |
| Active vs inactive | 62365 active / 62635 inactive |
| Users by role (normalized) | Editor: 41332, Viewer: 41861, Admin: 41807 |

_Role values above are normalized for readability (e.g. "EDITOR" / "Ad min" both roll up into their canonical bucket). Raw source values are preserved in the per-user table and CSV export._

## Findings

| Severity | Finding | Count | Business impact |
|---|---|---|---|
| 🟠 Medium | Stale user accounts | 63430 | Dormant account risk |
| 🔴 Critical | Paid inactive accounts | 48402 | License waste |
| 🔴 Critical | Stale admin accounts | 31779 | Elevated dormant-admin risk |
| 🔴 Critical | Admins without MFA | 27904 | Account compromise risk |
| 🟠 Medium | Missing managers | 18815 | Workflow / approval failures |
| 🟠 Medium | Missing SCIM IDs | 12362 | Provisioning / offboarding gaps |
| 🟢 Low | Missing department info | 6473 | Reporting / cost-allocation gaps |
| 🟠 Medium | Duplicate email addresses | 1015 | Possible orphaned or misprovisioned accounts |

## Action Plan

**Immediate**
- [ ] Enable MFA for 27904 admins

**This Week**
- [ ] Reclaim licenses from 48402 inactive accounts
- [ ] Review or disable 31779 stale admin accounts

**This Month**
- [ ] Investigate 1015 duplicate email addresses
- [ ] Review missing SCIM IDs and complete provisioning where applicable for 12362 accounts
- [ ] Review 63430 stale user accounts for deactivation, reactivation, or access validation

**This Quarter**
- [ ] Assign a manager to 18815 accounts
- [ ] Assign a department to 6473 accounts

## Expected Outcome

- Estimated annual license savings: $3,49,36,644
- Improved MFA coverage on administrator accounts
- Reduced privileged account risk
- Better SCIM provisioning compliance
- Improved identity governance and audit readiness

## Department Breakdown

| Department | Users | High risk | Est. monthly waste |
|---|---|---|---|
| People | 12044 | 2757 | $2,81,275 |
| Sales | 11986 | 2662 | $2,79,533 |
| Engineering | 11979 | 2634 | $2,74,742 |
| Design | 11924 | 2625 | $2,78,025 |
| Product | 11903 | 2616 | $2,76,312 |
| Legal | 11798 | 2666 | $2,80,968 |
| Support | 11791 | 2540 | $2,83,178 |
| Marketing | 11788 | 2588 | $2,65,732 |
| Finance | 11703 | 2554 | $2,68,583 |
| Ops | 11611 | 2566 | $2,69,340 |

## High-Risk Users — Top 20 of 125000

| Email | Role | Status | Risk | Flags |
|---|---|---|---|---|
| hayden.nguyen2160@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| sawyer.lee8002@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Missing SCIM ID; Paid inactive user |
| emerson.robinson7190@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| logan.moore7639@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Missing manager; Paid inactive user |
| cam.thomas9127@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Missing manager; Paid inactive user |
| elliot.clark3648@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| alex.carter3894@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| chris.carter5294@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| hayden.johnson6109@mockcorp.example | Admin | active | 100 | Stale admin; Admin no MFA; Missing SCIM ID; Missing manager |
| dakota.sanchez5436@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| elliot.adams8784@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| drew.brown7849@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| riley.gonzalez1347@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Missing manager; Paid inactive user |
| kendall.nelson1520@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Missing SCIM ID; Paid inactive user |
| blair.jackson1779@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Missing SCIM ID; Paid inactive user |
| pat.allen954@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |
| skyler.jackson4026@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Missing SCIM ID; Missing department; Paid inactive user |
| harper.walker6313@mockcorp.example | Admin | inactive | 100 | Stale admin; Admin no MFA; Missing SCIM ID; Paid inactive user |
| casey.sanchez6853@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Missing manager; Paid inactive user |
| morgan.sanchez8462@mockcorp.example | Ad min | inactive | 100 | Stale admin; Admin no MFA; Paid inactive user |

_Full dataset (125000 users) is available via the Export CSV button, or by choosing "All users" in the Top High-Risk Users section._

## Overall Assessment

Your Organization has an overall readiness score of 47/100 (Needs attention). The highest priorities are reviewing stale user accounts, reclaiming licenses from inactive accounts, and reviewing or disabling stale administrator accounts. Addressing these items could reduce estimated annual license waste by $3,49,36,644, while improving security posture and identity governance.
