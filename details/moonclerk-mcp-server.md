# MoonClerk MCP Server

MoonClerk MCP Server integrates MoonClerk’s web-based payment platform with MCP-compatible chat or agent clients, enabling recurring and one-time payment workflows through the MCP framework.

## Overview
- **Product type:** MCP server / integration
- **Purpose:** Enable recurring and one-time payment transaction workflows with MoonClerk via MCP
- **Provider / Infra:** Runs on Pipedream Connect
- **Static MCP server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Recurring payments support**
  - Designed to facilitate recurring payment transactions through MoonClerk.
- **One-time payments support**
  - Handles one-time payment transactions without additional overhead.
- **MCP-compatible server**
  - Exposes MoonClerk payment capabilities via the MCP framework.
  - Uses a single static server URL for all clients.
- **Static server endpoint**
  - Uniform endpoint: `https://mcp.pipedream.net/v2` works for every client.
  - Authentication is handled when adding the server to your MCP-capable application / chat client.
- **Multi-client usage**
  - Can be added to different MCP-enabled chat clients or applications using the same static URL.
- **Hosted by Pipedream**
  - Server is powered by Pipedream Connect infrastructure.

## Integration & Setup
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-enabled chat client or application.
- Authenticate as prompted by your client during server setup.
- Additional configuration details are available on the provider’s configuration page (referenced as “Configuration page” in the source content).

## Pricing
- No pricing information is provided in the available content.
