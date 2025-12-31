# Pro Ledger MCP Server

## Overview
Pro Ledger MCP Server exposes Pro Ledger’s small-business bookkeeping capabilities to MCP-compatible tools and chat clients. It allows you to connect a Pro Ledger account, select a client, and access bookkeeping and business management actions programmatically.

- **Category:** Business & Commerce – MCP Servers
- **Use case:** Small-business bookkeeping and business management via MCP
- **MCP endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server**
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) usable across all clients.
  - Authentication occurs when adding the server to your MCP-compatible application.

- **Pro Ledger account integration**
  - Connect a Pro Ledger account directly through the MCP server.
  - Select a specific small-business client within your account to operate on.

- **Bookkeeping for small businesses**
  - Exposes Pro Ledger’s bookkeeping functions through MCP (e.g., for accounting and business management workflows; specific tools/actions are loaded dynamically).

- **Tool-based actions**
  - Surfaces “available tools” (actions) for bookkeeping and business management once connected.
  - Tools are loaded dynamically from the Pro Ledger MCP Server for use in compatible chat clients and applications.

- **Multi-client support via a single URL**
  - The same MCP URL works for every client; context is set by the authenticated account and selected client.

- **Configuration resources**
  - Guidance available via a dedicated configuration page for adding the server to different chat clients and MCP-compatible applications.

## Integration & Setup
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server URL to your MCP-compatible chat client or application.
- Authenticate with your Pro Ledger account during setup.
- Select the target client entity (small business) to manage via the server.

## Pricing
- Not specified in the provided content.