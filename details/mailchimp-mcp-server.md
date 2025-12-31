# Mailchimp MCP Server

**Category:** Business & Commerce · MCP Servers  
**Tags:** email-marketing, marketing-automation, crm

Mailchimp MCP Server exposes Mailchimp’s marketing automation and email marketing operations as MCP-compatible tools via Pipedream. It lets MCP-enabled applications work with Mailchimp lists, campaigns, segments, and subscribers through a standardized server URL.

---

## Overview

- **Purpose:** Integrate Mailchimp capabilities (audiences, campaigns, subscriber management, reporting) into MCP-compatible chat or automation clients.
- **Connection model:** Connect a Mailchimp account, then use a single static MCP server URL to access tools.
- **Server URL:**
  - `https://mcp.pipedream.net/v2` (static URL used for all clients; authentication occurs when adding the server to an app).

---

## Features

### MCP Integration
- Static MCP server endpoint that can be reused across different MCP-compatible clients.
- Authentication handled when adding the server to the client/application.
- Configuration docs available via a dedicated configuration page (app/client-specific setup guidance).

### Available Tools (Actions)
There are **26 actions available as tools**. The content lists the following Mailchimp actions:

1. **Update List**  
   - Update an existing audience/list in Mailchimp (e.g., settings, details).

2. **Update Campaign**  
   - Modify properties of an existing Mailchimp campaign.

3. **Unsubscribe Email**  
   - Unsubscribe an email address from a specific audience.

4. **Send a Campaign**  
   - Send a campaign draft to the campaign’s configured audience.

5. **Search Members/Subscribers**  
   - Search for a subscriber (member).  
   - Optionally restrict the search to a specific list or search across all lists in the account.

6. **Search Lists**  
   - Search for Mailchimp lists/audiences.

7. **Search Campaigns**  
   - Search through existing campaigns.

8. **Remove Member From a Segment**  
   - Remove a member from a specified static segment in a list.

9. **List Segment Members**  
   - Retrieve a list of all members in a given segment.

10. **Get List**  
    - Retrieve a list’s details (list/audience metadata).

11. **Get List Member Tags**  
    - Retrieve all tags associated with a particular list member.

12. **Get List Member Activities**  
    - Retrieve the last 50 events of a member’s activity on a specific list.

13. **Get List Activities**  
    - Retrieve up to the previous 180 days of daily, detailed, aggregated activity stats for a list.

14. **Get Campaign**  
    - Retrieve metadata/details of a specific campaign.

15. **Get a Campaign Report**  
    - Retrieve a report for a specific campaign (performance/engagement metrics).

> Note: The page indicates **26 total actions**; only the above listed actions are shown in the provided content. Additional actions may be available in the live integration.

---

## Typical Use Cases

- Manage Mailchimp audiences, segments, and campaigns directly from MCP-enabled chat or automation tools.
- Automate email marketing workflows: searching subscribers, updating lists, sending campaigns.
- Retrieve campaign performance and list activity data for reporting or analytics within MCP-compatible applications.

---

## Pricing

- No pricing information is provided in the supplied content for the Mailchimp MCP Server or its usage via Pipedream. Pricing, if any, would need to be checked on the live Pipedream/Mailchimp pages.