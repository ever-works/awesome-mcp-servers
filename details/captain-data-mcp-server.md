# Captain Data MCP Server

## Overview
Captain Data MCP Server is a data extraction and automation platform endpoint that exposes Captain Data’s capabilities through the Model Context Protocol (MCP). It allows MCP-compatible agents and chat clients to orchestrate workflows using Captain Data via a unified MCP server URL.

- **Type:** MCP server / integration endpoint
- **Category:** Workflow automation MCP servers
- **Provider:** Captain Data, delivered via Pipedream Connect
- **Primary use cases:** Data extraction, automation, RPA-style workflows via MCP-compatible clients

## MCP Server URL
- **Static MCP server URL (for all clients):**
  ```
  https://mcp.pipedream.net/v2
  ```
- Authentication is performed when adding the server to your application / client.

## Features
- **MCP-based integration**
  - Exposes Captain Data as an MCP server for use with MCP-capable agents and chat interfaces.
  - Single static URL usable across different MCP clients.

- **Data extraction capabilities**
  - Designed to support data extraction workflows powered by Captain Data.

- **Automation & RPA workflows**
  - Intended for building and orchestrating automation workflows (RPA-style) through MCP.

- **Client-agnostic configuration**
  - Same MCP endpoint for every client; configuration differences are handled client-side.
  - Guided setup available per chat client via provided documentation.

- **Pipedream Connect integration**
  - Hosted and delivered via Pipedream Connect infrastructure.
  - Governed by Pipedream’s Terms and Privacy Policy.

## Setup & Configuration
- Add the MCP server to any supported MCP-compatible app or chat client using:
  ```
  https://mcp.pipedream.net/v2
  ```
- Authenticate during the "add server" or configuration flow in your client.
- Additional configuration details are available on the platform’s Configuration page (per-client setup instructions).

## Pricing
- Not specified in the provided content.