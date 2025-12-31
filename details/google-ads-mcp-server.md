# Google Ads MCP Server

## Overview
The Google Ads MCP Server is an MCP-compatible service that lets agents and chat-based applications interact with Google Ads accounts, campaigns, and performance data via a standardized MCP endpoint.

- **Category:** Business & Commerce MCP Server
- **Brand:** Google (via Pipedream integration)
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Single static MCP server URL works for all clients.
- Authentication handled when adding the server to your MCP-compatible application.
- Usable from various chat clients or agent frameworks that support MCP.

### Account & Configuration
- Connect a Google Ads account through Pipedream.
- Select a specific client/account to work with after authentication.
- Configure access to manage and analyze Google Ads data via tools/actions.

### Available Tools / Actions
**1. Send Offline Conversion**
- Send offline conversion events to Google Ads.
- Enables tracking of conversions that occur outside online channels (e.g., phone, in-store).
- Uses the Google Ads API via Pipedream’s `send-offline-conversion` action.

**2. Generate Keyword Ideas**
- Generate keyword ideas using the Google Ads API.
- Useful for campaign planning, expansion, and optimization.
- Implemented via `generate-keyword-ideas` action.

**3. Create Report**
- Generate reports from Google Ads data.
- Access performance metrics and analytics across campaigns, ad groups, and other entities (as supported by the underlying action).
- Implemented via `create-report` action.

**4. Create Customer List**
- Create new customer lists in Google Ads.
- Supports building audience lists for remarketing and targeting.
- Implemented via `create-customer-list` action.

**5. Add Contact to Customer List by Email**
- Add individual contacts to a specified customer list using their email address.
- Lists typically update within 6–12 hours after the operation.
- Implemented via `add-contact-to-list-by-email` action.

## Use Cases
- Automating offline conversion uploads from internal systems or CRMs.
- Programmatically generating keyword ideas from within an MCP-enabled chat or agent.
- Creating and retrieving performance reports on demand.
- Managing customer lists and audiences (creation and incremental updates).

## Pricing
The provided content does not list any pricing or plans for the Google Ads MCP Server. Pricing, if any, would need to be obtained directly from Pipedream or the hosting platform.