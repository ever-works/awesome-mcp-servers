# FreeAgent MCP Server

Accounting software integration for small businesses

**Source:** https://mcp.pipedream.com/app/freeagent  
**Category:** Finance & Market Data MCP Servers  
**Tags:** accounting, small-business, bookkeeping

---

## Overview
FreeAgent MCP Server integrates FreeAgent’s small business accounting capabilities with MCP-compatible applications, enabling automated bookkeeping and accounting workflows via a unified MCP server endpoint.

---

## Features
- **MCP-compatible accounting server**: Exposes FreeAgent’s small business accounting functionality through the Model Context Protocol (MCP).
- **Static MCP endpoint**: Uses a single static URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: Same server URL can be used across different MCP-enabled chat or agent clients.
- **Authentication at client setup**: Authentication is handled when adding the server to your application, rather than using client-specific URLs.
- **Configuration guidance**: Documentation available via a configuration page to assist with adding and managing the server in various clients.
- **Pipedream-based infrastructure**: Hosted and operated via Pipedream Connect, inheriting its platform infrastructure and policies.

> Note: The underlying accounting feature set is that of FreeAgent (small business accounting and bookkeeping), but the page only specifies the MCP integration layer and endpoint, not detailed accounting modules.

---

## Setup
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`
- Add the server in your MCP-compatible app or chat client.
- Complete authentication during the add/server configuration step.
- Optional: Refer to the full configuration documentation on the linked configuration page.

---

## Pricing
The provided content does not list any pricing details or plans for the FreeAgent MCP Server or its usage via Pipedream. Pricing, if any, would need to be obtained from the linked service providers (FreeAgent and/or Pipedream).