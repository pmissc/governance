# License and Access Register Template

**Template owner:** Technology Administrator  
**Version:** 1.0  
**Status:** Proposed  
**Intended location when populated:** Restricted chapter records repository  
**Related policy:** [Microsoft 365 Email, Identity, and License Policy](../policies/information-security/ms-office/README.md)

> Do not commit a populated register to Git. It contains security-sensitive identity and access information.

## Register metadata

| Field | Value |
|---|---|
| Review period |  |
| Register owner |  |
| Reviewing officer |  |
| Evidence date |  |
| Previous review date |  |
| Next review date |  |
| Restricted record location |  |

## Individual identity and license records

Create one row per human identity. Use the live tenant as the evidence source.

| Person | Current chapter role | Named account | Account state | License/plan | Business justification | Start date | Expected end date | Sponsor | Last verified |
|---|---|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |  |  |

## Privileged access

Create one row per privileged assignment, including partner access. Do not record passwords, recovery methods, or private credential details.

| Identity or relationship | Privileged account/object | Role | Scope | Assignment type | MFA/phishing-resistant status | Approval | Start | Expiration | Last used/reviewed | Action |
|---|---|---|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |  |  |  |

## Role and functional mailbox delegation

| Mailbox | Purpose | Business owner | Backup | Delegate | Full Access | Send As | Send on Behalf | Direct sign-in blocked | Sent Items copying enabled | Last verified |
|---|---|---|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |  |  |  |

## Groups, Teams, SharePoint, and applications

| Resource | Object type | Purpose | Primary owner | Backup owner | Access source | Guests present | Review date | Exception/action |
|---|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |  |

## Review checks

- [ ] Every person has a current sponsor and business justification.
- [ ] Licenses match current duties and inactive assignments were reviewed.
- [ ] Every privileged role is least-privileged, approved, and time-bound where supported.
- [ ] Fewer than five people hold Global Administrator and every assignment is justified.
- [ ] Emergency-access accounts were validated within 90 days without copying credential details into this register.
- [ ] Every shared mailbox has an owner, backup, approved delegates, blocked direct sign-in, and Sent Items copying.
- [ ] Every operational group, Team, SharePoint site, and application has a current owner and backup where supported.
- [ ] Guest and partner access was reviewed.
- [ ] Departed people and expired exceptions have no remaining access.
- [ ] Required records were preserved before licenses or accounts were removed.

## Review attestation

| Role | Name | Decision | Date |
|---|---|---|---|
| Technology Administrator |  | Complete / Exceptions recorded |  |
| Secretary or authorized officer |  | Accepted / Returned for correction |  |

List exceptions in the restricted review record with an owner, approval, due date, and expiration date.
