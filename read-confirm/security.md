# Security Policy - Read Confirm

**Last updated: February 2026**

## Overview

Read Confirm ("the App") is a Confluence Cloud application built on Atlassian Forge. This Security Policy describes the security measures and architecture that protect your data.

## Architecture & Infrastructure

Read Confirm is built entirely on **Atlassian Forge**, a serverless platform that runs within Atlassian's own cloud infrastructure. This architecture provides significant security advantages:

- **Backend (Resolvers)**: All server-side code executes within Atlassian's serverless environment — no external servers are involved
- **Frontend**: Runs in a sandboxed iframe within the Confluence interface, isolated from other content
- **Data Storage**: All data is stored in Forge Storage, managed and encrypted by Atlassian
- **No External Services**: The App does not make any outbound network requests to external servers or third-party services

## Data Protection

### Encryption

- **At Rest**: All data stored in Forge Storage is encrypted at rest by Atlassian's infrastructure
- **In Transit**: All communications are encrypted using TLS/HTTPS

### Data Isolation

- Data is scoped to each Confluence site installation
- No data is shared between different customer installations
- No data leaves Atlassian's infrastructure

### Data Minimization

We collect only the minimum data required for confirmation tracking:

- User account IDs (for tracking who confirmed)
- Confirmation timestamps
- Request metadata (deadlines, messages, target settings)

## Access Control

- Any Confluence user with page editing permissions can create confirmation requests
- Users can view confirmation status for requests associated with pages they have access to
- All access is governed by Confluence's existing permission model
- The App requests only the minimum permission scopes necessary for its functionality

## Permissions

The App requests only the minimum permissions necessary for its functionality, including reading page and user information for confirmation tracking and storing data via Forge Storage. For details on how Forge manages app permissions and scopes, refer to [Atlassian's Forge documentation](https://developer.atlassian.com/platform/forge/manifest-reference/permissions/).

## Vulnerability Management

- The App follows secure coding practices
- Dependencies are regularly reviewed and updated
- The Forge platform handles underlying infrastructure security, patching, and updates

## Incident Response

In the event of a security incident:

1. We will investigate and assess the scope and impact promptly
2. Affected customers will be notified as soon as reasonably possible
3. Corrective measures will be implemented and verified
4. A post-incident review will be conducted to prevent recurrence


## Compliance

- The App is designed to support **GDPR** and **CCPA** compliance requirements
- No personal data is transferred outside of Atlassian's infrastructure
- See our [Privacy Policy](https://app-contact.github.io/support-page/read-confirm/privacy) for details on data handling practices

## Third-Party Audits & Certifications

The App runs entirely within Atlassian's Forge infrastructure, which benefits from Atlassian's own security certifications, including SOC 2 and ISO 27001. For details, refer to [Atlassian's Trust Center](https://www.atlassian.com/trust).

## Changes to This Policy

We may update this Security Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Security Policy, please contact:

**middlecore**
Email: contact@middle-core.com

---

*This security policy is effective as of February 2026.*