# Microsoft 365 Administrator Transition Procedure

**Owner:** Technology Administrator  
**Version:** 1.0  
**Status:** Proposed  
**Effective date:** To be approved  
**Review cycle:** Annually and after every administrator transition  
**Related policy:** [Microsoft 365 Email, Identity, and License Policy](../../policies/information-security/ms-office/README.md)

## 1. Purpose

This procedure transfers Microsoft 365 administrative responsibility without sharing credentials, orphaning resources, losing records, or leaving unnecessary privileged access in place.

## 2. Prerequisites

- The Board or an authorized officer has identified the incoming and outgoing administrators and the effective transition date.
- A transition record has been opened in the restricted records repository.
- The authoritative officer and volunteer roster is current.
- At least one administrator other than the departing person can perform identity and role administration.
- Emergency-access accounts have been validated within the last 90 days.

## 3. Mandatory safeguards

- Every administrator uses an individual named identity and a separate privileged account.
- Credentials are never transferred from one person to another.
- New access is tested before old access is removed.
- Global Administrator is reserved for emergency access and tasks that cannot be completed with a narrower role.
- A resource must have a confirmed owner and backup before the departing owner is removed.
- Initial passwords, recovery codes, and other authentication secrets are never stored in Git or ordinary transition documents.
- Live inventories and evidence are stored in the restricted records repository.

## 4. Open the transition record

Record:

- authorizing officer and approval date;
- incoming and outgoing administrators;
- transition date and planned overlap;
- current chapter role for each person;
- systems and vendors in scope;
- evidence location; and
- the person accountable for closing the transition.

Use the [Technology Handover Checklist](../../templates/technology-handover-checklist.md) as the working checklist.

## 5. Inventory current access and ownership

Review the live tenant and record the results in the restricted transition record:

- Microsoft Entra administrative roles and eligible role assignments;
- Exchange administrative roles and mailbox delegation;
- Microsoft 365 Groups, Teams, SharePoint sites, distribution lists, and security groups owned by the departing accounts;
- application registrations, enterprise applications, service principals, certificates, and secrets;
- partner or reseller delegated administration;
- billing, domain, DNS, website, registration, finance, and other vendor administrator access;
- licenses assigned to the departing person;
- OneDrive and mailbox records requiring preservation; and
- approval workflows, notification addresses, and recovery contacts.

Do not rely solely on a prior spreadsheet or handover document. Query the current service and date the evidence.

## 6. Prepare incoming administrators

1. Create or confirm the incoming person's named account.
2. Create a separate cloud-only administrative account using the approved naming standard.
3. Do not assign a routine mailbox or license unless the administrative duties require one.
4. Require MFA registration. Use phishing-resistant authentication wherever supported.
5. Assign only the roles needed for the documented duties.
6. Hide the administrative identity from ordinary address lists when supported and appropriate.
7. Confirm the account is not used for routine email, web browsing, or collaboration.

Emergency-access accounts are organizational recovery controls and must not be assigned to an incoming administrator as a personal account.

## 7. Verify acceptance before removing access

The incoming administrator must independently:

- sign in with the privileged account;
- complete MFA;
- open the appropriate administration centers;
- perform one approved, reversible administrative task;
- confirm access to the restricted operating records; and
- confirm how to invoke and report an emergency-access procedure without learning or copying emergency credentials into the transition record.

Record the test, result, tester, and date. A created account is not accepted merely because it appears in the directory.

## 8. Transfer ownership and operational access

For every resource in the inventory:

1. Add the incoming owner or appropriate durable owner group.
2. Add a qualified backup owner where the service supports multiple owners.
3. Verify the new owner can administer the resource.
4. Update notification, recovery, billing, and escalation contacts.
5. Remove the departing owner only after the verification succeeds.

Do not delete an apparently obsolete group, mailbox, application, domain, or vendor account until its dependencies and records obligations have been checked.

## 9. Preserve records and licenses

- Move official files from the departing person's OneDrive into the approved SharePoint location.
- Identify mailbox records that must be preserved before removing an Exchange license.
- Convert a mailbox only when the [Shared Mailbox and Role Handoff Procedure](shared-mailbox-handoff.md) applies and its acceptance checks pass.
- Reassign licenses only after data preservation and successor access are confirmed.
- Apply the records-retention schedule and any legal or audit hold before deletion.

## 10. Remove obsolete privileged access

On or immediately after the effective transition date:

1. Remove administrative roles that are no longer required.
2. Remove obsolete group, mailbox, application, and vendor access.
3. Revoke active sessions and refresh tokens when the person has no continuing authorized assignment.
4. Block sign-in when the account no longer has an approved use.
5. Preserve required records before license removal or account deletion.
6. Remove the predecessor's role-mailbox delegation within five business days unless a short, documented extension is approved.

Do not use a fixed waiting period as a substitute for a retention decision. Account deletion occurs only after the records owner and Technology Administrator confirm that preservation, dependency, and approval requirements are satisfied.

## 11. Review external and partner access

Confirm each partner relationship against the live tenant and current contract. Continuing access must be:

- explicitly approved;
- limited to the least-privileged roles required;
- time-bound when the platform supports it;
- attributable to the partner relationship;
- reviewed at least quarterly; and
- removed when the service ends.

Prefer Microsoft granular delegated admin privileges over standing Global Administrator access when partner administration is required.

## 12. Close and attest

The transition owner and an authorized officer confirm that:

- successor access was tested;
- every in-scope resource has a current owner and backup where supported;
- obsolete privileged access was removed;
- sessions were revoked or sign-in blocked where required;
- records and licenses were handled correctly;
- emergency-access controls remain valid;
- the License and Access Register was updated; and
- evidence is stored in the restricted records repository.

Record exceptions with an owner, approval, expiration date, and follow-up review date.

## 13. Unexpected departure

When no planned overlap is possible:

1. Use an existing authorized administrator or validated emergency-access process.
2. Block the departing person's privileged and routine sign-ins as risk requires.
3. Revoke sessions and reset vendor recovery contacts.
4. Inventory ownership from the live services.
5. Preserve records before removing licenses or deleting accounts.
6. Record every emergency action and obtain retrospective officer review.

