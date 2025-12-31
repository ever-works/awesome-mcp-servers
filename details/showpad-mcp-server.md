# Showpad MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Showpad  
**Slug:** `showpad-mcp-server`

## Overview
Showpad MCP Server is an MCP-compatible integration that connects AI agents and chat clients to Showpad’s sales enablement and marketing platform. It allows applications using the MCP protocol to access sales content and related resources stored in Showpad via a unified MCP server endpoint.

## Features
- **MCP-compatible server**
  - Exposes Showpad functionality as tools/actions through the Model Context Protocol (MCP).
  - Provides a single static MCP server URL that works for all clients.

- **Showpad platform integration**
  - Interfaces with Showpad’s sales enablement and marketing platform.
  - Enables AI agents to access sales content and related resources managed in Showpad.

- **Static server endpoint**
  - MCP server URL: `https://mcp.pipedream.net/v2`
  - Same URL can be used across different chat clients and applications.

- **Client-agnostic usage**
  - Can be added to multiple MCP-compatible chat clients.
  - Guided setup available per client type (via the configuration page on Pipedream).

- **Authentication at application level**
  - Authentication occurs when adding the server to your app, allowing secure access to your Showpad account.

- **Configuration guidance (via Pipedream)**
  - Step-by-step instructions for connecting a Showpad account and selecting a client.
  - Central configuration page to review and manage settings.

> Note: The web page references “Available tools” and “Loading actions…”, indicating that multiple Showpad-related MCP tools/actions are exposed, but the specific tools are not listed in the provided content.

## Integration & Setup
- Connect your Showpad account through the Pipedream-hosted Showpad MCP configuration flow.
- Copy the static MCP server URL (`https://mcp.pipedream.net/v2`).
- Add the server to your MCP-compatible chat client or application and authenticate.
- Optionally, consult the full configuration page on Pipedream for client-specific setup instructions.

## Pricing
Pricing or plan details are not provided in the available content.