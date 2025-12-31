# Little Green Light MCP Server

Donor management software integration for nonprofits, exposed as an MCP (Model Context Protocol) server.

## Overview
The Little Green Light MCP Server provides MCP-compatible access to Little Green Light’s donor management capabilities, allowing chat-based or MCP-enabled clients to interact with donor CRM data used by nonprofits.

- **Type:** MCP server / integration
- **Domain:** Nonprofit donor management, CRM
- **Provider:** Pipedream (powered by Pipedream Connect)
- **Service URL:** `https://mcp.pipedream.net/v2` (static MCP server endpoint)

## Features
- **MCP-compatible endpoint**
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL for all clients; authentication is handled when adding/configuring the server in the client.

- **Little Green Light integration**
  - Connects MCP-enabled applications to Little Green Light’s donor management software.
  - Designed for nonprofit organizations that use Little Green Light as their donor CRM.

- **Client-agnostic setup**
  - Can be added to various MCP-aware chat clients or applications.
  - Configuration instructions are available via the platform’s configuration page (per client).

- **Pipedream Connect infrastructure**
  - Hosted and managed via Pipedream Connect.
  - Governed by Pipedream’s Terms and Privacy Policy.

## Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your compatible chat client or application.
- Complete authentication during setup within your client.
- Once connected, the client can use MCP to interact with Little Green Light donor management capabilities (e.g., CRM-related operations, depending on your client’s tools and permissions).

## Pricing
The provided content does not specify any pricing or plans for the Little Green Light MCP Server or its usage via Pipedream. Refer to the underlying services (Pipedream and Little Green Light) for any applicable pricing details.