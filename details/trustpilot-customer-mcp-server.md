# Trustpilot (Customer) MCP Server

An MCP server that exposes Trustpilot customer functionality, enabling applications to read and manage company reviews via the Model Context Protocol.

- **Category:** Business & Commerce MCP Servers  
- **Tags:** reviews, reputation, customer-feedback  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features

- **Trustpilot review access**
  - Integrates Trustpilot customer-facing capabilities into MCP-compatible clients.
  - Designed to let applications read and manage company reviews (as described in the item metadata).

- **Unified MCP endpoint**
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL works across different MCP clients.

- **Client-agnostic integration**
  - Can be added to any supported MCP/chat client.
  - Configuration is handled at the client level while the server URL stays the same.

- **Authentication at connection time**
  - Authentication is performed when adding the server to an application/client (specific auth details are handled during setup, not in the static URL itself).

- **Configuration documentation**
  - A dedicated configuration page (linked from the product page) describes how to add and use the server with various MCP clients.

## Usage

- Add the MCP server to your MCP-compatible client using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Follow your client’s configuration instructions (or refer to the linked configuration page on the source site) to authenticate and enable Trustpilot review operations.

## Pricing

- No pricing information is provided in the available content.