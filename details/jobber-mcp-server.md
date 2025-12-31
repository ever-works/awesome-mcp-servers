# Jobber MCP Server

Operations management integration for home service businesses via MCP.

## Overview
The Jobber MCP Server exposes Jobber’s operations management capabilities (used by home service businesses) as MCP tools, enabling scheduling- and job-related workflows to be accessed from compatible chat or MCP-enabled applications.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Provider / Platform:** Pipedream
- **Target users:** Home service and small service-based businesses using Jobber
- **Primary use case:** Managing clients, quotes, and service requests in Jobber through MCP-compatible apps

## Features

### MCP Server & Connectivity
- **Static MCP server URL:**
  - Base URL: `https://mcp.pipedream.net/v2`
  - Same URL for all clients; authentication is handled when adding the server to your application.
- **Account connection:**
  - Connect a Jobber account to the MCP server to manage Jobber data (clients, quotes, service requests) from supported chat/MCP clients.
- **Client selection:**
  - Once connected, you can select the target client in Jobber to run actions against.
- **Multi-client support (via configuration):**
  - Designed to work with multiple chat clients / MCP-enabled applications.
- **Configuration resources:**
  - Guided setup per chat client.
  - Central configuration reference page available.

### Available Tools (Actions)
5 Jobber actions are exposed as MCP tools:

1. **Search Quotes**
   - Search quotes in Jobber using a search term.
   - Useful for quickly locating existing quotes by keyword or other textual criteria.

2. **Filter Quotes**
   - Filter quotes by:
     - Status (e.g., open, won, lost – actual values determined by Jobber)
     - Quote number
     - Cost
   - Supports more precise retrieval of quotes based on business criteria.

3. **Create Service Request**
   - Create a new service request associated with a client’s first property in Jobber.
   - Suitable for initiating new jobs or site visits from within an MCP-enabled interface.

4. **Create Quote**
   - Generate a new quote for a client’s property in Jobber.
   - Enables quote creation workflows directly from chat or other MCP clients.

5. **Create Client**
   - Create a new client record within Jobber.
   - Facilitates onboarding new customers without leaving the MCP-connected app.

## Pricing
No pricing or plan information is provided in the available content. Use of the Jobber MCP Server may be subject to:
- Pipedream platform terms and any associated usage limits or pricing, and
- Jobber account requirements and pricing.

Refer to Pipedream and Jobber directly for up-to-date pricing details.
