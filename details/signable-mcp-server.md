# Signable MCP Server

## Overview
The Signable MCP Server is an integration that exposes Signable’s e‑signature capabilities through the Model Context Protocol (MCP). It lets applications (such as AI chat or MCP-compatible clients) send, sign, and organize documents securely via a standardized MCP server endpoint.

- **Type:** MCP Server / Integration
- **Category:** Business & Commerce – MCP Servers
- **Brand:** Signable
- **Slug:** `signable-mcp-server`
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features

### E‑signature workflows
- Send documents for electronic signature via Signable.
- Support secure, legally compliant e‑signing flows (as provided by Signable’s platform).
- Organize and manage documents after they’ve been sent and signed.

### MCP integration
- Exposes Signable’s functionality as an MCP Server, allowing AI agents and MCP-compatible clients to:
  - Connect to a single static MCP URL (`https://mcp.pipedream.net/v2`).
  - Authenticate per client/app when the server is added.
- Centralized, static server URL that works for every client; authentication is handled during client configuration.

### Account configuration
- Connect a Signable account through the configuration flow.
- Select a specific client (e.g., chat client or app) after connecting your account to start using tools.
- Automatic account checking/verification step during setup.

### Tools and actions
- Provides a set of MCP “tools” (actions) that can be called by compatible applications to interact with Signable (e.g., sending documents, handling signatures, organizing documents). 
- Tools are dynamically loaded by the MCP client (indicated by “Loading actions…/Loading available tools…” in the UI).

### Client integration guidance
- Instructions available per chat client or app on how to add the MCP server.
- Links to more detailed configuration documentation via a dedicated Configuration page.

## Pricing
Pricing details are not provided in the available content. Use of Signable via this MCP server will typically follow Signable’s and/or Pipedream’s underlying pricing, which must be checked on their respective sites.