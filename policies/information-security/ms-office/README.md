# PMISSC Microsoft 365 Email, Identity, and License Policy

**Organization:** Project Management Institute Silver Spring Chapter (PMISSC)  
**Policy owner:** Board of Directors; administration delegated to the Technology Administrator  
**Version:** 1.0  
**Status:** Proposed for Board adoption  
**Effective date:** To be approved  
**Review cycle:** Annually, before officer transitions, and whenever Microsoft licensing materially changes  
**Last source review:** August 7, 2026

> Microsoft now uses the name **Microsoft 365** for the services historically called Office 365. This policy uses “Microsoft 365” throughout.

## 1. Purpose

This policy establishes how PMISSC will create, name, assign, publish, transfer, retain, and retire Microsoft 365 accounts and email addresses. It is designed for a volunteer-led chapter with:

- a limited pool of paid or donated licenses;
- elected and appointed roles that change regularly;
- a need to preserve chapter correspondence and institutional knowledge;
- volunteers who may need collaboration access but not a PMISSC mailbox; and
- a need for secure, auditable access without sharing passwords.

The central policy decision is:

> **People receive individual identities when their work requires them; offices and functions receive permanent role-based addresses. Licenses follow current duties, not status, tenure, attendance, or past service.**

This follows the security principle of least privilege: access should be limited to the minimum needed to perform assigned work. See the [NIST definition of least privilege](https://csrc.nist.gov/glossary/term/least_privilege) and [Microsoft's role-management best practices](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/best-practices).

## 2. Scope

This policy applies to:

- elected officers and directors;
- appointed committee and program leads;
- volunteers, contractors, and temporary collaborators;
- Microsoft 365 administrators;
- all `@pmissc.org` addresses, mailboxes, aliases, groups, Teams, SharePoint sites, and related accounts; and
- PMISSC records created or received through those services.

## 3. Policy decisions at a glance

| Question | PMISSC policy |
|---|---|
| Should every elected person automatically receive a mailbox? | **No.** Election alone does not create a license entitlement. A person receives a licensed named account only when their duties require Microsoft 365 email or other licensed services. |
| Should an address be earned after a period of service or attendance? | **No.** Tenure and attendance are not access-control criteria. Access begins when an approved duty begins and ends when that need ends. |
| Should PMISSC use addresses such as `president@pmissc.org`? | **Yes.** Stable public-facing offices and functions should use permanent role-based addresses. |
| Should `president@pmissc.org` be an alias on the incumbent's personal mailbox? | **No.** It should normally be a shared mailbox with delegated access. This preserves its inbox, sent mail, calendar, and address for the successor. |
| Does a shared mailbox consume a license? | Usually **no**, while it remains within Microsoft's unlicensed shared-mailbox limits and does not use features that require a license. However, every delegate who opens it must have a licensed Exchange Online mailbox. See [Microsoft's shared-mailbox requirements](https://learn.microsoft.com/en-us/microsoft-365/admin/email/about-shared-mailboxes?view=o365-worldwide). |
| Can an unlicensed volunteer open a shared mailbox through a personal Gmail or other external account? | **No.** Microsoft states that shared-mailbox delegates must be internal users with licensed Exchange Online mailboxes. External volunteers should use guest collaboration or work through a licensed role owner. |
| Does a former officer keep a PMISSC address? | **Not by default.** The address and license are chapter resources, not personal benefits. Access continues only if the person moves into another approved role that requires it. |
| What should be published on the website? | Publish the person's name, title, and the permanent role/function address. Do not ordinarily publish the individual's named PMISSC address or personal email. |
| How does the next officeholder receive the history? | Add the successor as a delegate to the same shared mailbox, permit a short overlap, complete a documented handoff, and then remove the predecessor's access. |

## 4. Account and address model

PMISSC will use the following object types deliberately. An email address is not automatically a separate account or mailbox.

| Need | Correct Microsoft 365 object | Example | License treatment |
|---|---|---|---|
| A human needs an accountable sign-in, personal mailbox, and licensed services | Individual user account | `jane.doe@pmissc.org` | License required for the services assigned |
| A changing office or small team needs a permanent inbox and the ability to send from that address | Shared mailbox | `president@pmissc.org` | Mailbox usually unlicensed within Microsoft limits; each delegate must have a licensed Exchange mailbox |
| A group needs Teams, SharePoint, Planner, group conversations, or guest participation | Microsoft 365 Group | `board@pmissc.org` or a committee workspace | Owners/members licensed as required; external participants can be guests where permitted |
| One message must be distributed to many recipients, with no working inbox required | Distribution list | `announcements@pmissc.org` | No separate mailbox; recipients use their own accounts |
| An alternate or legacy address must deliver to an existing mailbox | Alias | `events@pmissc.org` routing to `programs@pmissc.org` | No separate mailbox, history, permissions, or identity |
| An outside volunteer needs files, meetings, or Teams collaboration but no PMISSC mailbox | Guest account | The volunteer's existing email identity | No PMISSC mailbox; guest-access terms apply |
| A technical administrator needs elevated privileges | Separate administrative account | `adm-jane.doe@pmissc.onmicrosoft.com` | No routine mailbox; assign only the least-privileged admin role needed |

Microsoft explains that Teams guest access does not require an additional Microsoft 365 license, subject to Microsoft's external-identity terms and service limits. See [Guest access in Microsoft Teams](https://learn.microsoft.com/en-us/microsoftteams/guest-access), [SharePoint external sharing](https://learn.microsoft.com/en-us/sharepoint/external-sharing-overview), and [Microsoft 365 guest users](https://learn.microsoft.com/en-us/microsoft-365/admin/add-users/about-guest-users?view=o365-worldwide).

## 5. License allocation

### 5.1 Licenses are operational resources

A license will be assigned only when the Board, Chapter Administrator, or authorized committee owner confirms a current business need. Licenses will not be assigned as recognition, a membership benefit, or an automatic privilege of election.

The Technology Administrator will maintain a **License and Access Register** containing:

- person's name and current chapter role;
- account type and primary address;
- assigned license and services;
- business justification;
- role and functional mailboxes delegated to the person;
- Teams, SharePoint, and administrative roles;
- start date, expected end date, and last review date; and
- accountable sponsor or committee owner.

### 5.2 Priority order when licenses are scarce

1. **Core operators:** current officers and operational leads who must read or send chapter email, administer financial or governance work, or access role shared mailboxes.
2. **Regular internal collaborators:** people who need sustained access to restricted chapter workspaces or licensed tools.
3. **Occasional collaborators:** guests using their existing identity for Teams, meetings, and SharePoint.
4. **Distribution-only recipients:** people receiving approved messages at an existing personal or business address; they do not receive a PMISSC sign-in.

If demand exceeds supply, the Board or its delegate will prioritize documented duties and risk. It will not resolve the shortage by sharing credentials or forwarding sensitive chapter mail to personal accounts.

### 5.3 Minimum necessary license

PMISSC will assign the lowest-cost license that supports the approved duties. A person who only needs web email and shared-mailbox delegation should not automatically receive desktop Office applications or premium services.

License availability and Microsoft nonprofit eligibility will be reviewed at least annually. Product names, grants, pricing, storage, and compliance entitlements may change; the Technology Administrator must verify current Microsoft terms before relying on a feature.

## 6. Naming conventions

All addresses will be lowercase, short, pronounceable, and free of election years or individual names when the address represents an office or function.

### 6.1 Individual user accounts

- Standard: `preferredfirstname.lastname@pmissc.org`
- Duplicate names: `preferredfirstname.middleinitial.lastname@pmissc.org`
- Avoid: nicknames that are not the person's established professional name, titles, years, committee names, and unexplained numbers.
- A legal or preferred-name change may retain the former address as a temporary alias for up to 12 months.
- Display name: `Preferred Firstname Lastname`

Examples:

- `jane.doe@pmissc.org`
- `jane.q.doe@pmissc.org`

### 6.2 Elected role addresses

Use a permanent shared mailbox when the office receives external correspondence, makes decisions, manages a calendar, or must pass history to successors.

Recommended examples:

- `president@pmissc.org`
- `presidentelect@pmissc.org`
- `secretary@pmissc.org`
- `treasurer@pmissc.org`

Do not create addresses such as `president2027@pmissc.org` or `jane-president@pmissc.org`.

### 6.3 Functional addresses

Use function names when the activity is more stable than a chapter title:

- `info@pmissc.org`
- `membership@pmissc.org`
- `programs@pmissc.org`
- `communications@pmissc.org`
- `sponsorship@pmissc.org`
- `technology@pmissc.org`

Create only addresses with a named owner, a backup owner, and a real operating need. Similar functions should be consolidated where practical.

### 6.4 Groups and lists

Use clear audience names such as:

- `board@pmissc.org`
- `committee-programs@pmissc.org`
- `volunteers@pmissc.org`
- `announcements@pmissc.org`

The sender restrictions and membership visibility of each list must be documented. Publicly writable distribution lists are prohibited unless spam and moderation controls are approved.

### 6.5 Administrative and emergency accounts

Administrative accounts will use the tenant's `pmissc.onmicrosoft.com` domain where practical and will not be advertised or used for routine email. Microsoft recommends separate cloud-only accounts for privileged work rather than using ordinary email accounts for administration. See [Microsoft's secure administrative access guidance](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/security-planning).

PMISSC will maintain at least two securely controlled, cloud-only emergency-access accounts in the tenant's `pmissc.onmicrosoft.com` domain, consistent with [Microsoft's emergency-access guidance](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/security-emergency-access). Each account will hold a permanent active Global Administrator assignment for recovery, must use a phishing-resistant authentication method that is independent of a named administrator's personal device, be monitored for every sign-in, and be tested at least every 90 days. Emergency-access accounts are used only for tenant recovery.

## 7. Role mailboxes, aliases, and continuity

### 7.1 Role addresses will be shared mailboxes

An address such as `president@pmissc.org` will normally be a shared mailbox, not an alias attached to the incumbent's named account.

This is required because a shared mailbox:

- remains under chapter control when the officeholder changes;
- preserves incoming mail, folders, sent mail, and the shared calendar;
- allows the successor and predecessor to overlap without sharing passwords;
- permits PMISSC to assign **Full Access** and **Send As** separately; and
- supports investigation of delegate activity through Microsoft 365 auditing, subject to available licensing and log-retention limits.

Microsoft documents that Full Access permits reading and managing a shared mailbox, while Send As permits messages to appear from the role address. Both permissions are needed for normal role-mailbox operation. See [Shared mailboxes in Exchange Online](https://learn.microsoft.com/en-us/exchange/collaboration-exo/shared-mailboxes) and [Manage mailbox permissions](https://learn.microsoft.com/en-us/exchange/recipients-in-exchange-online/manage-permissions-for-recipients).

### 7.2 Aliases are routing conveniences, not role ownership

An alias only delivers another address into an existing mailbox. It does not create a separate inbox, permission boundary, calendar, retention unit, or transition history. Microsoft also manages aliases as addresses on an existing licensed user or mailbox; see [Add another email alias for a user](https://learn.microsoft.com/en-us/microsoft-365/admin/email/add-another-email-alias-for-a-user?view=o365-worldwide).

Accordingly:

- A permanent chapter role address must not be attached as an alias to one person's mailbox.
- An alias may be used for a prior spelling, common abbreviation, or intentionally consolidated function.
- The alias must point to a chapter-controlled mailbox or group, not an external personal account.
- A legacy alias should be reviewed after 12 months and retired if it no longer receives legitimate mail.

### 7.3 Shared-mailbox configuration standard

Every role or functional shared mailbox must have:

- a primary role owner and at least one backup delegate;
- direct sign-in blocked;
- individual delegate identities—never a shared password;
- Full Access only for people who must manage its contents;
- Send As only for people authorized to represent the function;
- copying of sent-as and sent-on-behalf messages into the shared mailbox's Sent Items folder;
- a documented purpose, public-listing status, delegates, backup, and review date; and
- a mailbox folder structure or categories sufficient for handoff.

Microsoft states that shared mailboxes are not intended for direct sign-in and that delegates must use their own licensed mailboxes. See [About shared mailboxes](https://learn.microsoft.com/en-us/microsoft-365/admin/email/about-shared-mailboxes?view=o365-worldwide). Microsoft also documents the setting needed to [save sent messages in the shared mailbox](https://learn.microsoft.com/en-us/troubleshoot/exchange/user-and-shared-mailboxes/sent-mail-is-not-saved); PMISSC will enable it so successors can see what the chapter sent.

### 7.4 Shared-mailbox limits

An unlicensed shared mailbox is limited to 50 GB. Advanced archiving, larger storage, litigation hold, and some compliance features require additional licensing. See [Microsoft's mailbox conversion and licensing notes](https://learn.microsoft.com/en-us/microsoft-365/admin/email/convert-user-mailbox-to-shared-mailbox?view=o365-worldwide).

No more than 25 people should be assigned to one shared mailbox. Microsoft recommends a Microsoft 365 Group instead when broader participation is needed. External users cannot be delegates to a shared mailbox.

## 8. Public directory and signatures

### 8.1 What PMISSC will publish

The website and public directory should list:

`Person's Name — Chapter Role — role@pmissc.org`

Example:

`Jane Doe — President — president@pmissc.org`

This keeps the public address stable while still identifying the current officeholder. The individual's named PMISSC address should be published only when a role address is inappropriate and the person consents. Personal Gmail, Outlook.com, employer, or other external addresses should not be published as official chapter contact points.

### 8.2 Email signatures

Messages sent from role mailboxes must identify the human sender. The standard signature is:

```text
Preferred Name
Chapter Role | PMI Silver Spring Chapter
role@pmissc.org | https://pmissc.org
```

No one may use a role mailbox anonymously or imply that a personal opinion is an official Board position.

### 8.3 When an address is removed from listings

- Role and functional addresses remain listed while the office or service exists.
- The outgoing person's name must be removed or replaced on the effective transition date.
- A named PMISSC address must be removed when the person's approved assignment ends, normally within one business day.
- Service, attendance, donor status, or past office does not create a right to permanent forwarding or continued listing.

## 9. Annual role transition procedure

The same shared mailbox will remain in place from year to year. The address must not be deleted, renamed for the successor, or moved onto the successor's personal mailbox.

| Timing | Required action | Accountable party |
|---|---|---|
| 30–45 days before transition | Confirm incoming and outgoing roleholders; review the License and Access Register; identify each mailbox, group, Team, SharePoint site, calendar, and vendor account tied to the role. | Secretary and Technology Administrator |
| 10 business days before | Create the successor's individual account if needed; assign the minimum license; require MFA registration; provide role-mailbox Full Access and Send As; add workspace permissions. | Technology Administrator |
| During overlap | Successor reviews mailbox folders, open commitments, recurring calendar items, contacts, rules, and official records with the predecessor. Passwords are not transferred. | Incoming and outgoing roleholders |
| Effective transition date | Update public name listings, signatures, group ownership, approval workflows, Teams/SharePoint owners, billing contacts, and the Access Register. | Secretary, Communications, and Technology Administrator |
| Within 1 business day | Remove any admin role no longer needed. Revoke sessions and block sign-in if the person has no continuing approved assignment. | Technology Administrator |
| Within 5 business days | Remove predecessor's Full Access and Send As rights to the old role mailbox unless the Board approves a short, documented extension. | Technology Administrator |
| Within 30 days | Move chapter records from the departing person's OneDrive into the appropriate chapter SharePoint site; confirm ownership and access. | Successor and Technology Administrator |
| Within 90 days | Retire any temporary named-address routing; remove or reassign the license; close the transition record. | Technology Administrator |

If a former officer's named mailbox contains material chapter correspondence, PMISSC may temporarily convert it to a shared mailbox before removing its license, block the former user's sign-in, and delegate it to the successor. Microsoft explains that conversion retains existing email and calendar content and allows license removal when the mailbox remains eligible. See [Convert a user mailbox to a shared mailbox](https://learn.microsoft.com/en-us/microsoft-365/admin/email/convert-user-mailbox-to-shared-mailbox?view=o365-worldwide).

Removing a license without a preservation plan is not an archival strategy. Microsoft states that email, contacts, and calendar are ordinarily retained for 30 days after license removal and then deleted, while user deletion has separate consequences for OneDrive. See [Remove a former user from Microsoft 365](https://learn.microsoft.com/en-us/microsoft-365/admin/add-users/remove-former-employee?view=o365-worldwide) and [OneDrive retention and deletion](https://learn.microsoft.com/en-us/sharepoint/retention-and-deletion).

## 10. Security and acceptable use

### 10.1 Individual accountability

- Every human user must use their own account.
- Shared usernames and passwords are prohibited.
- Shared-mailbox direct sign-in must remain blocked.
- Credentials may not be transferred during role handoff.
- All users must protect authentication devices and report suspected compromise immediately.

### 10.2 Multifactor authentication

MFA is required for all PMISSC accounts. Security Defaults will remain enabled unless PMISSC implements equivalent or stronger Conditional Access policies. Microsoft describes Security Defaults as the baseline for organizations without custom Conditional Access policies; see [Configure Security Defaults](https://learn.microsoft.com/en-us/entra/fundamentals/security-defaults).

Emergency-access accounts must use phishing-resistant authentication, such as passkeys or FIDO2 security keys, or certificate-based authentication. Named administrators should use phishing-resistant authentication wherever Microsoft 365 supports it; all administrative accounts remain subject to MFA during any migration to stronger methods.

### 10.3 Least privilege and administration

- Global Administrator will not be assigned for routine Exchange, Teams, SharePoint, or user-administration tasks.
- Fewer than five people may hold Global Administrator, consistent with [Microsoft's recommendation](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/best-practices); PMISSC should normally use only its designated administrators and emergency accounts.
- Privileged work must be performed from separate administrative accounts.
- Administrative role assignments and mailbox delegation must be reviewed at least quarterly and at every role transition.

### 10.4 External forwarding

Automatic forwarding from a PMISSC role or functional mailbox to a personal external account is prohibited by default because it removes correspondence from chapter control, weakens transition continuity, and may expose confidential information.

An exception requires written approval from two authorized officers, a documented purpose, a named data owner, a fixed expiration date not exceeding 90 days, and confirmation that no financial, personal, election, disciplinary, or otherwise sensitive information will be forwarded. The preferred solution is a licensed PMISSC account or guest collaboration—not forwarding.

### 10.5 Sensitive information

Email should not be used to store passwords, complete payment-card data, government identifiers, or unnecessary member personal data. Financial instructions and changes to payment details must be verified through a second communication channel.

## 11. Records, retention, and mailbox management

### 11.1 The chapter system of record

Email is a communication channel, not the final repository for official chapter records. Final versions of the following must be stored in the designated PMISSC SharePoint site or approved records repository:

- bylaws, policies, meeting minutes, and Board resolutions;
- contracts, grant or sponsorship agreements, and insurance documents;
- tax, accounting, payment, and audit records;
- election records and official membership reports;
- approved budgets, reports, and program deliverables; and
- material decisions made by email.

Files supporting chapter operations should be created in SharePoint or moved there promptly, rather than kept only in an individual's OneDrive. This reduces loss when licenses are reassigned.

### 11.2 Retention schedule

PMISSC will adopt and maintain a separate records-retention schedule approved by the Board and reviewed for applicable legal, tax, contractual, PMI, and insurance obligations. This policy does not invent a universal legal retention period.

Until that schedule is adopted:

- governance, tax, accounting, contract, election, and material decision records must not be intentionally destroyed;
- routine announcements, duplicates, spam, and purely transitory scheduling messages may be deleted when no longer useful; and
- any known or reasonably anticipated audit, dispute, investigation, or legal hold suspends normal deletion for affected material.

Where licensed, Microsoft Purview retention can apply to user and shared mailboxes. See [Microsoft's Exchange retention documentation](https://learn.microsoft.com/en-us/purview/retention-policies-exchange) and [Data Lifecycle Management overview](https://learn.microsoft.com/en-us/purview/data-lifecycle-management). The Technology Administrator must verify licensing before representing a mailbox as being on hold or subject to a particular retention policy.

### 11.3 Sent mail and auditability

Copies of messages sent from role and functional mailboxes must be retained in that mailbox's Sent Items folder. This lets successors understand prior commitments and reduces dependence on a predecessor's individual mailbox.

When a security, deletion, or accountability issue arises, an authorized administrator may use available Microsoft 365 audit logs. See [Investigate shared-mailbox activities](https://learn.microsoft.com/en-us/purview/audit-log-identify-mailboxes). Audit availability and duration depend on Microsoft licensing and configuration.

## 12. Access reviews and inactivity

The Technology Administrator and Secretary will review the License and Access Register:

- quarterly;
- 30–45 days before annual officer turnover;
- after every resignation, removal, or appointment; and
- after any security incident.

During each review, PMISSC will verify current role, license need, MFA registration, group memberships, shared-mailbox delegation, administrative roles, guest access, and backup ownership.

An account inactive for 45 days will be reviewed with its sponsor. Inactivity alone does not force removal when a seasonal or documented need exists, but unexplained inactivity may result in sign-in being blocked and the license being reclaimed after reasonable notice.

## 13. Exceptions

Exceptions must be:

- documented in the License and Access Register;
- approved by two authorized officers, one of whom should be the President, Secretary, or Treasurer;
- limited to the narrowest access and shortest feasible period;
- assigned an expiration date; and
- reviewed at least monthly until closed.

No exception may authorize password sharing, shared-mailbox direct sign-in, or continued access for a person with no current chapter duty.

## 14. Responsibilities

### Board of Directors

- Approves this policy, license budget, and material exceptions.
- Defines elected and appointed roles and approves the records-retention schedule.

### Secretary

- Maintains the authoritative roster and transition dates.
- Ensures public listings and governance records remain current.

### Treasurer

- Confirms license spending and preserves financial records.
- Participates in approvals affecting financial mailboxes or external forwarding.

### Technology Administrator

- Implements accounts, licenses, MFA, groups, shared mailboxes, permissions, and transitions.
- Maintains the License and Access Register and performs quarterly reviews.
- Uses least-privileged administrative roles and maintains emergency access.

### Role and functional mailbox owners

- Keep the mailbox organized and monitor it at an appropriate frequency.
- Identify the human sender in outgoing messages.
- Move official records to SharePoint and complete handoffs.
- Notify the Technology Administrator promptly of role or access changes.

### All users and guests

- Use only their assigned identity and access.
- Protect credentials, comply with PMISSC confidentiality expectations, and report incidents or incorrect access.

## 15. Recommended initial PMISSC configuration

PMISSC should begin with a small, stable set and add mailboxes only when a named owner and recurring need exist.

| Address | Recommended object | Primary purpose | Delegates/owners |
|---|---|---|---|
| `info@pmissc.org` | Shared mailbox | General public inquiries | Communications lead plus backup |
| `president@pmissc.org` | Shared mailbox | Executive and external chapter correspondence | President plus Secretary or approved backup |
| `secretary@pmissc.org` | Shared mailbox | Governance and Board administration | Secretary plus President or approved backup |
| `treasurer@pmissc.org` | Shared mailbox | Financial correspondence | Treasurer plus President or approved finance backup |
| `membership@pmissc.org` | Shared mailbox | Membership inquiries and administration | Membership lead plus backup |
| `programs@pmissc.org` | Shared mailbox | Events and programs | Programs lead plus backup |
| `communications@pmissc.org` | Shared mailbox | Website, newsletter, and media | Communications lead plus backup |
| `technology@pmissc.org` | Shared mailbox | Non-privileged support contact | Technology lead plus backup; never an admin sign-in |
| `board@pmissc.org` | Microsoft 365 Group or moderated distribution list | Board collaboration and distribution | At least two current Board owners |

The exact list should follow the current bylaws and operating model. Similar functions may be aliases on one stable shared mailbox when a separate inbox and permission boundary are unnecessary.

## 16. Adoption checklist

- [ ] Board approves the policy owner, effective date, and exception approvers.
- [ ] Technology Administrator inventories all current users, aliases, shared mailboxes, groups, guests, licenses, and admin roles.
- [ ] Each permanent role address is moved from any person's mailbox to a chapter-controlled shared mailbox.
- [ ] Direct sign-in is blocked for all shared mailboxes.
- [ ] Full Access and Send As permissions are assigned to named individuals; sent-item copying is enabled.
- [ ] MFA or Security Defaults is verified for all accounts.
- [ ] At least two emergency-access accounts are established and tested.
- [ ] The License and Access Register is created and reviewed with the Secretary.
- [ ] Public pages list stable role addresses rather than personal addresses.
- [ ] Official records are moved from individual OneDrive locations into chapter SharePoint sites.
- [ ] A separate records-retention schedule is assigned for Board approval.
- [ ] The next annual transition review is placed on the Board calendar.

## 17. Authoritative references and reasoning

1. [NIST — Least Privilege](https://csrc.nist.gov/glossary/term/least_privilege): access should be restricted to the minimum needed for assigned tasks.
2. [Microsoft — About shared mailboxes](https://learn.microsoft.com/en-us/microsoft-365/admin/email/about-shared-mailboxes?view=o365-worldwide): access licensing, internal delegate requirement, blocked direct sign-in, capacity, and usage considerations.
3. [Microsoft — Shared mailboxes in Exchange Online](https://learn.microsoft.com/en-us/exchange/collaboration-exo/shared-mailboxes): Full Access, Send As, and shared-mailbox administration.
4. [Microsoft — Add an email alias](https://learn.microsoft.com/en-us/microsoft-365/admin/email/add-another-email-alias-for-a-user?view=o365-worldwide): aliases as additional addresses on an existing user/mailbox.
5. [Microsoft — Convert a user mailbox to a shared mailbox](https://learn.microsoft.com/en-us/microsoft-365/admin/email/convert-user-mailbox-to-shared-mailbox?view=o365-worldwide): content preservation and licensing limits during departure.
6. [Microsoft — Remove a former user](https://learn.microsoft.com/en-us/microsoft-365/admin/add-users/remove-former-employee?view=o365-worldwide): license reassignment, mailbox forwarding/conversion, and data-retention consequences.
7. [Microsoft — Best practices for Microsoft Entra roles](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/best-practices): least privilege, MFA, access reviews, and limits on Global Administrators.
8. [Microsoft — Manage emergency-access accounts](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/security-emergency-access): two cloud-only recovery accounts and periodic testing.
9. [Microsoft — Security Defaults](https://learn.microsoft.com/en-us/entra/fundamentals/security-defaults): baseline identity protection for organizations without custom Conditional Access policies.
10. [Microsoft — Guest access in Teams](https://learn.microsoft.com/en-us/microsoftteams/guest-access) and [SharePoint external sharing](https://learn.microsoft.com/en-us/sharepoint/external-sharing-overview): collaboration with volunteers who do not need a PMISSC mailbox.
11. [Microsoft — Save shared-mailbox sent items](https://learn.microsoft.com/en-us/troubleshoot/exchange/user-and-shared-mailboxes/sent-mail-is-not-saved): preserving outgoing role correspondence in the shared mailbox.
12. [Microsoft — Exchange retention](https://learn.microsoft.com/en-us/purview/retention-policies-exchange): retention capabilities for user and shared mailbox content.

---

**Board approval**

| Name/title | Signature | Date |
|---|---|---|
| President |  |  |
| Secretary |  |  |
| Technology Administrator |  |  |
