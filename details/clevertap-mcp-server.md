# CleverTap MCP Server

## Overview
The CleverTap MCP Server connects CleverTap’s customer engagement and analytics platform to any MCP‑compatible client via a single static endpoint. It enables tools that support the Model Context Protocol (MCP) to interact with CleverTap for automated engagement and analytics workflows.

- **Type:** MCP server (integration endpoint)
- **Category:** Business & Commerce – MCP Servers
- **Provider/Brand:** CleverTap (via Pipedream Connect)
- **Slug:** `clevertap-mcp-server`
- **Primary Use Cases:**
  - Integrating CleverTap with MCP‑compatible chat or agent clients
  - Enabling automated customer engagement workflows
  - Surfacing customer analytics data into MCP‑based tools

## Features

Given the available information, the following capabilities are explicitly supported or implied:

1. **MCP-Compatible Server Endpoint**
   - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`.
   - Designed to plug into any MCP‑compatible client or application.

2. **CleverTap Platform Integration**
   - Exposes CleverTap’s customer engagement and analytics capabilities through MCP.
   - Intended to support automated engagement workflows that leverage CleverTap data and actions.

3. **Centralized Configuration**
   - Uses a single static URL for all clients; authentication is handled when adding the server in each client.
   - Additional configuration details are available via a dedicated configuration page (not included here).

4. **Pipedream Connect Infrastructure**
   - The MCP server is powered by Pipedream Connect, meaning the connectivity, hosting, and protocol handling are managed by Pipedream.

> Note: The source content does not list specific MCP tools (e.g., schemas, methods) or detailed CleverTap operations (e.g., send campaign, fetch events). Only the general integration purpose and connection details are provided.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Per‑client, performed when adding the MCP server to your application (no further details provided in the source content).

## Pricing
The provided content does not include any pricing or plan information for the CleverTap MCP Server or associated services.