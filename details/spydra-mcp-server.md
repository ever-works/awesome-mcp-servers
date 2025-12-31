# Spydra MCP Server

## Overview
Spydra MCP Server is an MCP (Model Context Protocol) server for the Spydra asset tokenization platform. It provides AI tools and compatible applications with programmatic access to tokenization and blockchain asset operations through a static MCP endpoint.

- **Category:** Blockchain / Crypto MCP Servers
- **Use Cases:** Asset tokenization, blockchain asset management, integrating tokenization workflows into AI/chat clients

## Features
- **MCP-compatible server**
  - Exposes Spydra asset tokenization and blockchain asset operations via the MCP standard.
  - Designed to be added as a server to MCP-compatible chat clients and AI tools.

- **Static server URL**
  - Single, static MCP endpoint used across all clients:
    - `https://mcp.pipedream.net/v2`
  - Same URL works for every client; authentication is handled when adding the server to the application.

- **Account-based configuration**
  - Connect a Spydra account to configure and access the MCP server.
  - Client selection workflow once the account is connected (e.g., “Connect your account and select your client”).

- **Tool/action discovery**
  - Supports listing and loading available tools/actions associated with Spydra’s asset tokenization and blockchain operations (shown as “Available tools / Loading actions... / Loading available tools...” in the interface).

- **Client integration guidance**
  - UI guidance for adding the MCP server to different chat clients.
  - References to a full configuration page for more detailed setup instructions.

## Integration Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the MCP server to your MCP-compatible application or chat client.
- **Host Platform:** Provided via Pipedream’s MCP infrastructure.

## Pricing
No pricing information is provided in the available content.