# MSG91 MCP Server

MSG91 MCP Server provides Model Context Protocol (MCP) access to MSG91’s communication APIs, enabling applications to send and manage multi-channel communications (SMS, voice, video, and authentication) through a unified MCP interface.

---

## Overview
- **Type:** MCP server / integration
- **Provider:** MSG91 (hosted via Pipedream)
- **Category:** Messaging MCP servers
- **Channels:** SMS, voice, video, authentication
- **Use case:** Build multi-channel messaging and verification workflows via MCP-compatible clients.

---

## Features

### Multi-channel communication
- Access MSG91’s **SMS** APIs via MCP.
- Access **voice** communication APIs via MCP.
- Access **video** communication APIs via MCP.
- Access **authentication** (e.g., OTP / verification) APIs via MCP.

### MCP integration
- Exposes MSG91 capabilities as MCP tools/actions for use within MCP-compatible chat or agent clients.
- Uses a **single static MCP server URL** for all clients:
  - `https://mcp.pipedream.net/v2`
- Authentication occurs when adding the server to your MCP-compatible application.

### Configuration & client setup
- Connect an MSG91 account and select a client to begin using the MCP server.
- Configuration is managed through the Pipedream-hosted configuration flow.
- Works with multiple MCP chat clients; each client can use the same server URL.

> Note: The site references “Available tools” being loaded dynamically, but no specific individual tools/actions are listed in the provided content.

---

## Pricing

Pricing details for the MSG91 MCP Server or underlying MSG91 communication APIs are **not provided** in the available content. Refer to MSG91 and/or Pipedream pricing pages for cost information.

---

## Technical details
- **MCP server endpoint:** `https://mcp.pipedream.net/v2`
- **Hosting platform:** Pipedream
- **Integration pattern:** Add as an MCP server in compatible clients; authenticate MSG91 account during setup.