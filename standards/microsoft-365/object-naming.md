# Microsoft 365 Object Naming and Classification Standard

**Owner:** Technology Administrator  
**Version:** 1.0  
**Status:** Proposed  
**Effective date:** To be approved  
**Review cycle:** Annually and after material Microsoft 365 changes  
**Related policy:** [Microsoft 365 Email, Identity, and License Policy](../../policies/information-security/ms-office/README.md)

## 1. Purpose

This standard makes an object's purpose, ownership, and security meaning clear without encoding unnecessary personal or time-limited information in its name.

## 2. General requirements

- Addresses and aliases use lowercase characters.
- Names are short, pronounceable, and understandable without private context.
- A permanent role or function name does not contain a person's name, election year, or unexplained number.
- Every operational object has a documented purpose, primary owner, backup owner where supported, data classification, and review date.
- Display-name prefixes communicate object type only when the prefix has an enforced meaning.
- A name must not imply a permission, license, or control the object does not actually grant.
- Examples in repository documents use fictional people and do not expose live account identifiers.

## 3. Approved patterns

| Object | Pattern | Example | Notes |
|---|---|---|---|
| Named user | `preferredfirstname.lastname@pmissc.org` | `alex.morgan@pmissc.org` | Use a middle initial to resolve duplicates. |
| Privileged admin | `adm-preferredfirstname.lastname@pmissc.onmicrosoft.com` | `adm-alex.morgan@pmissc.onmicrosoft.com` | Cloud-only, no routine mailbox, not published. |
| Emergency access | Non-obvious cloud-only name in `pmissc.onmicrosoft.com` | Not published | The identifier and credentials remain in restricted records. |
| Elected office mailbox | `<office>@pmissc.org` | `president@pmissc.org` | Normally a shared mailbox with named delegation. |
| Functional mailbox | `<function>@pmissc.org` | `membership@pmissc.org` | Requires a recurring function, owner, and backup. |
| Committee workspace | `Committee - <Name>` | `Committee - Programs` | Use a Microsoft 365 Group when collaboration services are required. |
| Role-membership group | `ROLE-<Role>` | `ROLE-Programs-Director` | Describes who holds an organizational role; does not itself imply resource access. |
| Resource-access group | `ACCESS-<Resource>-<Level>` | `ACCESS-FinanceSite-Edit` | Grants the stated access only; document the target resource. |
| License-assignment group | `LIC-<ProductOrPlan>` | `LIC-BusinessBasic` | Use only when group-based licensing is active and verified. |
| Distribution list | `DL-<AudienceOrPurpose>` | `DL-Board` | Mail distribution only; not a resource-access control. |
| Role-assignable admin group | `ADM-<DirectoryRole>` | `ADM-ExchangeAdministrators` | Permitted only when created as role-assignable and the documented directory role is actually attached. |

Email addresses for groups and lists may use an approved short public alias even when the administrative display name carries a prefix.

## 4. Object-type boundaries

- A role mailbox receives and preserves correspondence for a changing office; it is not a person's sign-in account.
- A named user account identifies one human and must not be reassigned.
- A privileged account is used only for administration and must not receive routine mail.
- A distribution list distributes mail and does not confer SharePoint, application, or mailbox access.
- A role group describes organizational assignment; a separate access group grants access when separation improves reviewability.
- An alias routes mail to an existing object; it does not create a mailbox, identity, history, owner, or permission boundary.

## 5. Administrative-group safeguard

An `ADM-` prefix is prohibited unless the group is role-assignable and has the stated Microsoft Entra role attached. Empty, ordinary, or decorative `ADM-` groups create a false impression of control and must be renamed, rebuilt correctly, or retired after dependency review.

## 6. Legacy objects

Before renaming or retiring a legacy object:

1. Identify its object type, owners, members, mail addresses, permissions, application dependencies, and records value.
2. Confirm whether another object has a duplicate or misspelled name.
3. Select the compliant replacement and migration plan.
4. Preserve a required mail alias or redirect for a documented transition period.
5. Test access and mail flow.
6. Record the change and update the License and Access Register.

Do not infer that an object is unused from its name alone.

## 7. Review

The Technology Administrator reviews naming compliance at least annually and during officer transitions. Exceptions require an owner, business reason, approving officers, and expiration date.

