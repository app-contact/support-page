# Security Policy - Stale Page Finder for Confluence

**Last updated: February 2026**

## Overview

Stale Page Finder for Confluence ("the App") is a Confluence Cloud application built on Atlassian Forge. This Security Policy describes how we protect your data.

## Architecture & Infrastructure

The App is built entirely on **Atlassian Forge**, running within Atlassian's cloud infrastructure with no external servers or third-party services. The App has zero egress — it makes no outbound network requests outside of Atlassian's environment.

## Data Protection

- **Encryption**: Data in Forge Storage is encrypted at rest (AES-256). All communications use TLS 1.2+
- **Data Isolation**: Data is namespaced per site installation and never shared between customers
- **Data Minimization**: The App does not store Confluence content. Search results are fetched in real-time and not cached. CSV exports are generated in the user's browser. The only persisted data is app configuration stored in Forge Storage

## Access Control

- Users can only access content they have permission to view
- Write operations (labels, comments) are verified via the Forge `authorize` API before execution
- The App never handles user credentials directly

## Permissions

The App requests only the minimum scopes necessary for stale page detection, label/comment writing, and app configuration storage. See [Atlassian's Forge documentation](https://developer.atlassian.com/platform/forge/manifest-reference/permissions/) for details.

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
- See our [Privacy Policy](https://app-contact.github.io/support-page/stale-page-finder/privacy) for details

## Third-Party Audits & Certifications

The App runs on Atlassian's Forge platform, which is SOC 2 Type II attested and ISO 27001 certified. For details, refer to [Atlassian's Trust Center](https://www.atlassian.com/trust).

## Changes to This Policy

We may update this Security Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

**middlecore** — Email: contact@middle-core.com

---

*This security policy is effective as of February 2026.*