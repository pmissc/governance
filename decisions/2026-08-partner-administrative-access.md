# Partner Administrative Access to Microsoft 365

**Date opened:** August 7, 2026  
**Status:** Proposed — Board decision required  
**Decision owner:** Board of Directors  
**Implementation owner:** Technology Administrator  
**Review cycle after decision:** Quarterly and at contract renewal

## Context

A prior handover packet reported that the chapter's Microsoft licensing reseller held standing Global Administrator access to the Microsoft 365 tenant. The packet did not include sufficient live evidence or contractual terms to approve or revoke that relationship solely from the documents.

Standing third-party Global Administrator access creates a broad and persistent path into chapter identities, mail, files, and configuration. [Microsoft granular delegated admin privileges](https://learn.microsoft.com/en-us/partner-center/customers/gdap-introduction) can provide narrower and time-bound partner access when continuing administration is required.

## Decision question

What access, if any, does the chapter authorize its reseller or support partner to retain in the Microsoft 365 tenant?

## Options

### Option A — No standing partner administration

The partner provides licensing and support without persistent tenant access. A chapter administrator performs changes or grants temporary access for a specific support case.

**Advantages:** Smallest standing attack surface and clearest chapter control.  
**Tradeoff:** Chapter administrators must be available for support and changes.

### Option B — Granular delegated admin privileges

The chapter grants only the roles required for defined support services, for a fixed duration, using Microsoft's granular delegated admin privilege model.

**Advantages:** Least-privileged, attributable, reviewable, and time-bound.  
**Tradeoff:** Requires partner cooperation and periodic renewal/review.

### Option C — Standing Global Administrator

The partner retains permanent Global Administrator.

**Advantages:** Maximum partner convenience.  
**Tradeoff:** Broad, persistent access that exceeds ordinary least-privilege needs and is difficult to justify for licensing alone.

## Recommendation pending Board approval

Use Option B when a contractually defined support need requires partner administration; otherwise use Option A. Do not continue Option C unless the Board records a specific necessity, compensating controls, accountable owner, and expiration date.

## Evidence required before decision

- Current live-tenant role and delegated-admin relationship details.
- Partner legal name and applicable contract or reseller agreement.
- Services that require tenant administration.
- Roles and workloads actually used during the previous 12 months.
- Available GDAP roles and proposed duration.
- Partner authentication, monitoring, breach-notification, and offboarding terms.
- Chapter escalation path when partner access is unavailable.

Store this evidence in the restricted records repository, not in Git.

## Proposed implementation after approval

1. Confirm the live relationship and remove any obsolete or duplicate partner access.
2. Obtain the partner's least-privileged role request and business justification.
3. Approve only the required roles and a defined term.
4. Test the support workflow without granting a chapter user account to the partner.
5. Remove standing Global Administrator after successful migration unless the Board approved a documented exception.
6. Record the relationship in the License and Access Register.
7. Review access quarterly, at contract renewal, and after any security incident.

## Decision record

| Field | Board determination |
|---|---|
| Selected option | Pending |
| Approved roles | Pending |
| Duration/expiration | Pending |
| Approving authority and date | Pending |
| Required conditions | Pending |
