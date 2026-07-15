# Inkwell - Documentation

## Overview

Inkwell is a section completion tracker for Confluence pages. Assign each section of a structured page (postmortems, PRDs, RFCs, onboarding docs) to a teammate, track who's writing what, and see "3 of 7 sections complete · 43%" right at the top of the page.

## Getting Started

1. Edit a Confluence page and insert the **Inkwell — Section Completion** macro
2. Click **Add Section** to define the sections of your page
3. Assign an **Assignee** (and optionally a **Reviewer** and due date) to each section
4. Teammates update section status as they write — progress is always visible at the top of the page

## Features

### Page-Top Progress Bar
See overall completion at a glance: "3 of 7 sections complete (43%)" displayed right on the page.

### Section Assignments
Assign each section to a teammate, with separate **Assignee** and **Reviewer** roles.

### Status Workflow
Each section moves through a clear workflow:

**Not Started** → **In Progress** → **In Review** → **Approved**

Reviewers can **Request Changes**, sending the section back to the assignee for resubmission. Sections without a reviewer can be marked complete directly.

### Due Dates & Overdue Reminders
Set due dates on sections. Overdue sections are surfaced automatically — the app posts a reminder comment on the page (with @mentions of assignees) at most once per day per page.

### My Sections Dashboard
A global dashboard listing all sections assigned to you across every page, sorted by priority and due date.

### Permission-Aware
Inkwell respects Confluence permissions: only users who can view a page can see its sections, and workflow actions are verified server-side based on each user's role (page owner, section creator, assignee, reviewer).

## Requirements

- Confluence Cloud
- Page edit permission is required to add sections and participate in the workflow

## Service Level Agreement (SLA)

### Support Response Time

| Item | Details |
|------|---------|
| **Target Response Time** | 2 business days (48 hours) |
| **Time Zone** | Asia/Tokyo (JST / UTC+9) |
| **Hours of Operation** | 9:00 AM - 6:00 PM JST |
| **Days of Operation** | Monday - Friday (excluding Japanese national holidays) |

### Support Contact

- **Email**: contact@middle-core.com

### Scope of Support

- Bug reports and technical issues
- Installation and configuration assistance

### Out of Scope

- Custom development requests
- Third-party integration issues not related to the App
- Confluence platform issues (please contact Atlassian Support)

### SLA Disclaimer

**The response times stated above are targets and not guarantees.** We will make commercially reasonable efforts to respond within the stated timeframes, but actual response times may vary due to support volume, complexity of issues, or circumstances beyond our control. Failure to meet these targets does not entitle users to any refund, credit, or other compensation.

## Support

For questions or issues, contact: contact@middle-core.com

## Terms of Service

This app is governed by the Bonterms Standard Agreement for Marketplace Transactions, available on the Atlassian Marketplace listing page, together with the additional terms below.

### Disclaimer of Warranties

THE APP IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, OR THAT THE APP WILL BE UNINTERRUPTED, ERROR-FREE, OR FREE OF HARMFUL COMPONENTS.

We do not warrant that:
- The App will meet your specific requirements
- The App will be available at all times or at any particular time
- The results obtained from using the App will be accurate or reliable
- Any errors in the App will be corrected

### Limitation of Liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL MIDDLECORE, ITS AFFILIATES, OFFICERS, DIRECTORS, EMPLOYEES, OR AGENTS BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES, INCLUDING BUT NOT LIMITED TO LOSS OF PROFITS, DATA, USE, GOODWILL, OR OTHER INTANGIBLE LOSSES, RESULTING FROM:

- Your use or inability to use the App
- Any unauthorized access to or alteration of your data
- Any third-party conduct related to the App
- Any other matter relating to the App

IN ANY CASE, OUR TOTAL AGGREGATE LIABILITY SHALL NOT EXCEED THE AMOUNT YOU PAID FOR THE APP IN THE TWELVE (12) MONTHS PRECEDING THE CLAIM, OR ONE HUNDRED US DOLLARS (USD $100), WHICHEVER IS GREATER.

### Indemnification

You agree to indemnify, defend, and hold harmless middlecore and its officers, directors, employees, and agents from and against any and all claims, liabilities, damages, losses, costs, and expenses (including reasonable attorneys' fees) arising out of or relating to:

- Your use of the App
- Your violation of these Terms
- Your violation of any third-party rights
- Any content or data you process using the App

### Service Modifications and Discontinuation

We reserve the right to:
- Modify, suspend, or discontinue the App (or any part thereof) at any time with or without notice
- Change features, functionality, or pricing with reasonable notice
- Limit certain features or restrict access to parts or all of the App

We shall not be liable to you or any third party for any modification, suspension, or discontinuation of the App.

### Force Majeure

We shall not be liable for any failure or delay in performance due to causes beyond our reasonable control, including but not limited to: acts of God, natural disasters, war, terrorism, riots, embargoes, acts of civil or military authorities, fire, floods, accidents, strikes, shortages of transportation, facilities, fuel, energy, labor, materials, or communications or information technology infrastructure failures.

### Governing Law and Jurisdiction

These Terms shall be governed by and construed in accordance with the laws of Japan, without regard to its conflict of law provisions. Any disputes arising from or relating to these Terms or the App shall be subject to the exclusive jurisdiction of the courts of Tokyo, Japan.

### Severability

If any provision of these Terms is found to be unenforceable or invalid, that provision shall be limited or eliminated to the minimum extent necessary so that these Terms shall otherwise remain in full force and effect.

### Entire Agreement

These Terms, together with the Bonterms Standard Agreement and our Privacy Policy, constitute the entire agreement between you and middlecore regarding the App.

## Privacy Policy

See our [Privacy Policy](privacy.md) for details on how we handle data.

## FAQ

**Q: Does the app store any data?**  
A: Yes. Section data (titles, instructions, statuses, due dates, assignees, reviewers) is stored in Atlassian Forge hosted storage, entirely within Atlassian's cloud infrastructure. No data leaves Atlassian's environment. See our [Privacy Policy](privacy.md) for details.

**Q: Does the app modify my page content?**  
A: The app does not rewrite your page body. It displays sections through a macro you insert, and posts reminder comments on pages that have overdue sections.

**Q: What happens to my data if I uninstall the app?**  
A: All app data is automatically deleted by the Forge platform 28 days after uninstallation.

**Q: Who can change a section's status?**  
A: Workflow actions are role-based: assignees can start work and submit for review, reviewers can approve or request changes, and page owners can manage all sections. Approved sections are locked from further editing.

**Q: How do I report a bug or request a feature?**  
A: Please contact us at contact@middle-core.com with details of the issue or suggestion.

**Q: Can I get a refund?**  
A: Refunds are subject to Atlassian's Marketplace refund policies. Please contact Atlassian support for refund requests.

---

*Last updated: July 2026*
