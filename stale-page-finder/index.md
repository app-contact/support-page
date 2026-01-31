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

## Requirements

- Confluence Cloud
- Admin or space admin permissions

## Support

For questions or issues, contact: contact@middle-core.com

## Terms of Service

This app is governed by the Bonterms Standard Agreement for Marketplace Transactions, 
available on the Atlassian Marketplace listing page.

## FAQ

**Q: How accurate is the last modified date?**
A: We use Confluence's native CQL `lastmodified` field, which reflects the most recent edit to the page content.

**Q: Does this app store any data?**
A: No. All searches are performed in real-time using Confluence's API. No page data is stored outside of Confluence.