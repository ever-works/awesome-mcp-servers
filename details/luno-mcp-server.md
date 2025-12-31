# Luno MCP Server

An MCP (Model Context Protocol) server that integrates with Luno, enabling MCP-compatible clients to interact with Luno’s crypto buying, saving, and management services in a structured and secure way.

- **Website / Source**: https://mcp.pipedream.com/app/luno
- **Category**: Blockchain & Crypto MCP Servers
- **Tags**: crypto, wallet-management, trading
- **Provider**: Pipedream (via Pipedream Connect)

## Features

- **Luno Integration**
  - Connects MCP clients to Luno’s platform for crypto-related operations.
  - Designed to support buying, saving, and managing cryptocurrency via Luno.

- **Standard MCP Server Endpoint**
  - Uses a single static MCP server URL that works for all supported MCP clients:
    - `https://mcp.pipedream.net/v2`
  - Authentication is handled when adding the server to your client/application.

- **Client-Agnostic Setup**
  - Same server URL for every client; no client-specific endpoints required.
  - Configuration instructions available via the general MCP configuration documentation ("Configuration" page on Pipedream Connect).

- **Hosted by Pipedream**
  - Infrastructure and MCP server hosting are managed by Pipedream.
  - Governed by Pipedream’s Terms and Privacy Policy.

## Usage

1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this URL as an MCP server in your compatible chat client or application.
3. Authenticate when prompted by your client to connect to Luno via the server.

## Pricing

Pricing information is not provided in the available content. Refer to the source page or provider documentation for current pricing details, if any.