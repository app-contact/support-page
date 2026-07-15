# Security Policy - Inkwell for Confluence

**Last updated: July 2026**

## Overview

Inkwell for Confluence ("the App") is a Confluence Cloud application built on Atlassian Forge. This Security Policy describes how we protect your data.

## Architecture & Infrastructure

The App is built entirely on **Atlassian Forge**, running within Atlassian's cloud infrastructure with no external servers or third-party services. The App has zero egress — it makes no outbound network requests outside of Atlassian's environment.

## Data Protection

- **Encryption**: Data in Forge Storage is encrypted at rest (AES-256). All communications use TLS 1.2+
- **Data Isolation**: Data is namespaced per site installation and never shared between customers
- **Data Minimization**: The App stores only section tracking data (titles, instructions, statuses, due dates, assignee/reviewer references, and cached display names). It does not store Confluence page body content
- **Data Lifecycle**: All app data is automatically deleted by the Forge platform 28 days after uninstallation. Personal data of closed Atlassian accounts is erased via Atlassian's personal data reporting cycle

## Access Control

- Users can only see sections on pages they have permission to view
- Confluence page edit permission is a prerequisite for adding sections and participating in the workflow
- Workflow actions (start, submit, approve, request changes) are additionally verified server-side against the user's role (page owner, section creator, assignee, reviewer) — the UI is not the security boundary
- Status transitions are only possible through dedicated, validated endpoints; approved sections are locked from editing
- The App never handles user credentials directly

## Permissions

The App requests only the minimum scopes necessary for section tracking: reading page, space, and user information; writing reminder comments; and app storage. See [Atlassian's Forge documentation](https://developer.atlassian.com/platform/forge/manifest-reference/permissions/) for details.

## Vulnerability Management

- Dependencies are regularly reviewed and updated
- The App has completed Atlassian's Marketplace security review process
- The Forge platform manages infrastructure-level security and patching

## Incident Response

In the event of a security incident:

1. We will investigate and assess the scope and impact promptly
2. Corrective measures will be implemented and verified
3. A post-incident review will be conducted to prevent recurrence

## Compliance

- The App is designed to support **GDPR** and **CCPA** compliance requirements
- No personal data leaves Atlassian's infrastructure
- The App implements Atlassian's personal data reporting requirements for Forge apps
- See our [Privacy Policy](https://app-contact.github.io/support-page/inkwell/privacy) for details

## Third-Party Audits & Certifications

The App runs on Atlassian's Forge platform, which is SOC 2 Type II attested and ISO 27001 certified. For details, refer to [Atlassian's Trust Center](https://www.atlassian.com/trust).

## Changes to This Policy

We may update this Security Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

**middlecore** — Email: contact@middle-core.com

---

*This security policy is effective as of July 2026.*
