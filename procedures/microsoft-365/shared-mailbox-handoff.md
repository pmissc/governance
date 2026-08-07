# Shared Mailbox and Role Handoff Procedure

**Owner:** Technology Administrator  
**Version:** 1.0  
**Status:** Proposed  
**Effective date:** To be approved  
**Review cycle:** Annually and after material Microsoft Exchange changes  
**Related policy:** [Microsoft 365 Email, Identity, and License Policy](../../policies/information-security/ms-office/README.md)

## 1. Purpose

This procedure preserves a permanent chapter role or function address while transferring responsibility between people. It also governs conversion of an eligible user mailbox into a shared mailbox before license removal.

## 2. Use this procedure when

- a stable office or function address must survive a change in personnel;
- a role mailbox is being separated from a person's named sign-in identity; or
- an eligible user mailbox must be converted to a shared mailbox so its chapter records and address remain available.

Do not use a shared mailbox as a substitute for an accountable human identity, a broad collaboration workspace, or an archive without an approved retention plan.

## 3. Prerequisites

- The role or function has a named business owner and backup.
- The incoming delegate has an individual licensed Exchange mailbox.
- The mailbox purpose, records owner, retention requirements, delegates, and public-listing status are documented.
- Current mailbox size, archive use, holds, compliance features, forwarding, inbox rules, aliases, and application dependencies have been checked.
- The change and rollback owner are identified.

## 4. Choose the permission model

Use direct, named delegation by default:

- **Full Access** for people who must read and manage mailbox contents; and
- **Send As** only for people authorized to represent the role or function.

Direct named delegation supports individual accountability and normal Outlook automapping behavior. If a security group is used instead, document the reason, expected Outlook behavior, group owners, membership-review process, and how access will be removed. Do not maintain both group-based and direct access for the same person unless a documented decision explains the need and the removal procedure tests both paths.

Use a Microsoft 365 Group or another collaboration workspace when participation is broad or when Teams, SharePoint, Planner, or guest collaboration is the primary need.

## 5. Pre-change capture

Record in the restricted change record:

- mailbox type, primary address, aliases, size, and license;
- owner, backup, and current delegates;
- Full Access, Send As, and Send on Behalf permissions;
- forwarding, inbox rules, automatic replies, and connected applications;
- retention, archive, hold, and compliance settings;
- Sent Items copy settings; and
- the acceptance test and rollback plan.

Do not export mailbox content or delegate lists into Git.

## 6. Convert an eligible user mailbox

If conversion is required:

1. Confirm the mailbox is within Microsoft's current unlicensed shared-mailbox limits and does not use a feature requiring a license.
2. Confirm required records are preserved and no hold, archive, or application dependency will be broken.
3. Convert the mailbox to shared.
4. Wait for the service to report the mailbox as shared.
5. Block direct sign-in for the shared-mailbox account.
6. Preserve its primary address and required aliases.
7. Do not remove the license yet.

## 7. Configure continuity controls

- Assign the incoming delegate and backup using the approved permission model.
- Grant only the required sending permission.
- Enable copying of sent-as and sent-on-behalf messages into the shared mailbox's Sent Items folder.
- Review forwarding and inbox rules; remove any unapproved external forwarding.
- Update public directories, signatures, website listings, group ownership, workflows, and recovery contacts.
- Provide a simple folder, category, or handoff convention appropriate to the role.

## 8. Acceptance test

The incoming delegate must verify, using their own named account, that they can:

- open the shared mailbox;
- read an approved test message;
- send an approved test message using the correct From address;
- confirm the sent message appears in the shared mailbox's Sent Items;
- access any required shared calendar; and
- locate the handoff information and current commitments.

The outgoing delegate or change owner confirms that messages are not being duplicated or misrouted.

## 9. Remove the license and predecessor access

Only after conversion and acceptance succeed:

1. Reconfirm mailbox type, size, retention, archive, and hold status.
2. Remove the license if the mailbox remains eligible to operate unlicensed.
3. Verify the mailbox is still accessible and mail flow succeeds.
4. Remove predecessor delegation within five business days unless an approved overlap is still active.
5. Revoke sessions or block the predecessor's named account when required by the administrator-transition procedure.
6. Update the License and Access Register.

License removal by itself is never a records-preservation method.

## 10. Rollback

If conversion, delegation, mail flow, records access, or a required application fails:

- stop further license or account changes;
- restore the previous mailbox type or license when appropriate;
- restore the captured permissions and settings;
- verify mail flow and records access; and
- record the failure, corrective action, and revised plan.

Do not delete the mailbox while a rollback or records question remains open.

## 11. Completion evidence

The restricted change record must show:

- approval and change date;
- pre-change capture;
- successful acceptance test;
- final owners and delegates;
- final mailbox type and license state;
- predecessor-access removal date;
- records and retention confirmation; and
- any exception, owner, and expiration date.

