# StreamWish MCP Server

An MCP server for StreamWish that lets MCP-enabled tools upload and share videos through the StreamWish monetization platform.

---

## Overview
- **Name:** StreamWish MCP Server
- **Category:** Media Processing MCP Servers
- **Brand:** StreamWish
- **Website:** https://mcp.pipedream.com/app/streamwish
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

This server integrates StreamWish with MCP-compatible clients so users can upload and share videos via the StreamWish platform directly from their MCP-enabled tools.

---

## Features
- **MCP-compatible video integration**
  - Exposes StreamWish functionality as an MCP server endpoint.
  - Uses a static server URL (`https://mcp.pipedream.net/v2`) that works across supported MCP clients.

- **Video upload and sharing**
  - Supports uploading videos to StreamWish from MCP-enabled applications.
  - Enables sharing videos through the StreamWish platform once uploaded.

- **Monetization platform access**
  - Connects to StreamWish’s monetization features so uploaded videos can generate revenue (details handled within StreamWish platform).

- **Account connection flow**
  - Users connect their StreamWish account through the Pipedream-hosted configuration.
  - After connection, tools and actions become available inside supported clients (listed dynamically as “Available tools”).

- **Client-agnostic MCP endpoint**
  - Same MCP server URL for all supported chat / MCP clients.
  - Authentication handled when adding the server within each client’s configuration.

---

## Configuration
- Go to the StreamWish MCP Server page on Pipedream.
- Connect your StreamWish account.
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add this server URL to your MCP-enabled app or chat client.
- Follow client-specific steps as described in the app’s configuration or the general Configuration page.

---

## Tags
- video
- media-management
- content-hosting

---

## Pricing
No pricing information is provided in the available content.