# Technology Handover Checklist

**Template owner:** Technology Administrator  
**Version:** 1.0  
**Status:** Proposed  
**Intended location when populated:** Restricted chapter records repository  
**Related procedure:** [Microsoft 365 Administrator Transition](../procedures/microsoft-365/administrator-transition.md)

> Do not place passwords, recovery codes, private keys, initial-password files, or other authentication secrets in this checklist.

## Handover metadata

| Field | Value |
|---|---|
| Outgoing roleholder |  |
| Incoming roleholder |  |
| Authorizing officer |  |
| Effective transition date |  |
| Planned overlap end |  |
| Transition owner |  |
| Restricted evidence location |  |

## Authority and acceptance

- [ ] Appointment or delegation is documented.
- [ ] Incoming person's named identity is confirmed.
- [ ] Separate privileged account is created where required.
- [ ] MFA is registered; phishing-resistant authentication is used where required.
- [ ] Only the necessary administrative roles are assigned.
- [ ] Incoming administrator completed a successful sign-in and approved test task.
- [ ] Initial credentials were rotated and any handoff copies were securely destroyed.

## Ownership inventory

- [ ] Microsoft Entra roles and owned objects reviewed.
- [ ] Microsoft 365 Groups and Teams reviewed.
- [ ] SharePoint sites and OneDrive records reviewed.
- [ ] Shared mailboxes, distribution lists, aliases, and delegation reviewed.
- [ ] Applications, service principals, certificates, secrets, and automation reviewed.
- [ ] Domains, DNS, website, registration, and public contact records reviewed.
- [ ] Finance, payment, event, marketing, membership, and other vendor accounts reviewed.
- [ ] Every continuing resource has a primary owner and backup where supported.

## Security and recovery

- [ ] Emergency-access accounts were validated within the last 90 days.
- [ ] Emergency credentials remain in approved separate secure locations.
- [ ] Security alerts and recovery contacts were updated.
- [ ] External forwarding, inbox rules, and delegated mailbox access were reviewed.
- [ ] Partner/reseller access is approved, least-privileged, and time-bound where supported.
- [ ] Unneeded roles and group memberships were removed.
- [ ] Departing-user sessions were revoked when appropriate.

## Records and continuity

- [ ] Official files were moved from personal OneDrive storage to the approved SharePoint location.
- [ ] Mailbox records were preserved before license removal.
- [ ] Open commitments, contracts, calendars, contacts, workflows, and renewal dates were handed over.
- [ ] Public directory, website, signatures, and notification addresses were updated.
- [ ] Applicable retention, audit, investigation, or legal-hold requirements were checked.
- [ ] No secrets or raw tenant exports were placed in Git.

## Licensing and account closure

- [ ] License need was reviewed against current duties.
- [ ] Role/shared mailbox conversion was verified before any license removal.
- [ ] Predecessor access was removed after successor acceptance.
- [ ] Obsolete privileged accounts were blocked from sign-in.
- [ ] Account deletion, if any, was approved under the records-retention process.
- [ ] License and Access Register was updated.

## Exceptions and follow-up

| Exception | Risk | Owner | Approval | Due date | Expiration | Status |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |

## Acceptance

| Role | Name | Acceptance | Date |
|---|---|---|---|
| Incoming roleholder |  | Accepted / Exceptions noted |  |
| Outgoing roleholder, if available |  | Completed / Exceptions noted |  |
| Technology Administrator |  | Verified |  |
| Authorized officer |  | Approved closure |  |
