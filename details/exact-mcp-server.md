# Exact MCP Server

Cloud business software integration for SMEs and their accountants via an MCP server.

## Overview

The Exact MCP Server connects Exact’s cloud business software to MCP-compatible chat or agent clients using a static MCP endpoint. Authentication is handled when the server is added to the client application.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Accounting workflows, SME business management, automated interactions with Exact cloud services

## MCP Server URL

Use this URL when configuring the MCP server in your MCP-compatible client:

```text
https://mcp.pipedream.net/v2
```

This is a static URL and works for all clients; authentication is completed during setup in your application.

## Features

- **Static MCP endpoint**
  - Single, fixed MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
  - Simplifies configuration across different tools and environments.

- **Client-initiated authentication**
  - Authentication is performed when adding the server to your chat or agent application.
  - Allows per-client or per-user auth handling.

- **Chat client integration**
  - Designed to be added directly to MCP-compatible chat clients.
  - Supports instruction-based use (e.g., "add Exact MCP Server") following each client’s standard MCP configuration flow.

- **Configuration documentation**
  - Full configuration guidance available via a dedicated configuration page (referenced as “Configuration page”).

- **Pipedream Connect platform**
  - MCP server is powered by Pipedream Connect, providing hosted infrastructure and endpoint management.

> Note: The underlying website content does not list specific API methods or detailed accounting/business features exposed by this MCP server, only that it integrates with Exact’s cloud business software for SMEs and accountants.

## Pricing

The provided content does not include any pricing or plan information for the Exact MCP Server or its usage via Pipedream Connect.