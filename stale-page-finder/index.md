# Stale Page Finder - Documentation

## Overview

Stale Page Finder helps Confluence admins find stale and outdated pages quickly using real-time CQL search.

## Getting Started

1. Navigate to **Apps** → **Stale Page Finder** in Confluence
2. Select a time threshold (90, 180, or 365 days)
3. Optionally filter by space
4. Click **Search** to find stale pages

## Features

### Search
Find pages that haven't been updated within your specified time period.

### Filter by Space
Narrow results to a specific Confluence space.

### Sort Results
Sort by:
- Last updated date (oldest/newest first)
- Page title (A-Z / Z-A)

### Export to CSV
Download search results for offline review or sharing with your team.

### Bulk Labeling
Select multiple pages and add labels for easy tracking and follow-up.

### Request Review
Send review requests to page owners with @mention notifications.

## Requirements

- Confluence Cloud
- Admin or space admin permissions

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

**Q: How accurate is the last modified date?**  
A: We use Confluence's native CQL `lastmodified` field, which reflects the most recent edit to the page content. Accuracy depends on Confluence's data.

**Q: Does this app store any data?**  
A: No. All searches are performed in real-time using Confluence's API. No page data is stored outside of Confluence.

**Q: How do I report a bug or request a feature?**  
A: Please contact us at contact@middle-core.com with details of the issue or suggestion.

**Q: What permissions does the app require?**  
A: The app requires read access to Confluence pages and spaces, and write access for the bulk labeling feature.

**Q: Can I get a refund?**  
A: Refunds are subject to Atlassian's Marketplace refund policies. Please contact Atlassian support for refund requests.

---

*Last updated: January 2025*