# DingConnect MCP Server

## Overview
DingConnect MCP Server provides a Machine Connection Protocol (MCP) interface to DingConnect’s international mobile top-up platform, enabling programmatic mobile recharge and top-up operations.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Telecom top-ups, payment/recharge workflows, integrating international mobile recharge into apps and automation.

## Features
- **MCP Server for DingConnect**
  - Exposes DingConnect’s international mobile top-up capabilities through the MCP protocol.
  - Designed to be added as a server to compatible chat or MCP-enabled applications.

- **International Mobile Top-Up Integration**
  - Connects to DingConnect’s global mobile recharge platform.
  - Suitable for building workflows that programmatically recharge or top up mobile accounts.

- **Static MCP Endpoint**
  - Single static server URL for all clients: `https://mcp.pipedream.net/v2`.
  - No per-client URL changes required.

- **Authentication at Client Configuration**
  - Authentication handled when adding the server to your own application/client (credentials not embedded in the URL).

- **Client-Agnostic Setup**
  - Can be added to various MCP-compatible chat clients or applications.
  - Configuration guidance available via a central configuration page (general MCP server setup, not DingConnect-specific logic described).

- **Operated via Pipedream Connect**
  - Hosted and managed by Pipedream’s Connect infrastructure.
  - Benefits from Pipedream’s standardized MCP server hosting environment.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Setup Steps (high level):**
  - Add the above MCP server URL to your MCP-compatible app or chat client.
  - Configure authentication within your client when prompted.
  - Optionally refer to the generic MCP server configuration documentation (not specific to DingConnect) for client-specific steps.

## Pricing
The provided content does not list any pricing information or plans for the DingConnect MCP Server.