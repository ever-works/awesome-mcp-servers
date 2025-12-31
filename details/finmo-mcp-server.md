# Finmo MCP Server

**Category:** Finance & Market Data MCP Servers  
**Brand:** Finmo  
**Source:** https://mcp.pipedream.com/app/finmo

## Description
Finmo MCP Server is an MCP server integration that lets MCP-compatible tools and chat clients interact with Finmo’s payment and transaction capabilities. It provides a single, static MCP server URL that applications can add and authenticate against to access Finmo-powered payment functions.

## Features
- **MCP server integration for Finmo**
  - Exposes Finmo’s payments and transactions functionality to MCP-aware tools and chat clients.
- **Static MCP server URL**
  - Uses a single, static endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when adding the server to your application, rather than per-client URLs.
- **Account connection and configuration**
  - Connect a Finmo account and select a client within the configuration flow.
  - Basic status feedback while connecting (e.g., “Checking your account…”).
- **Client-agnostic integration**
  - Designed to be added to various chat clients; documentation is organized by client type.
  - Links to a full configuration page for detailed setup instructions.
- **Tooling exposure**
  - Intended to surface “available tools” (actions) that operate on Finmo payments and transactions via MCP (tool list is dynamically loaded in the UI).

## Use Cases
- Enabling chat-based tools or agents to initiate and manage Finmo payment flows.
- Allowing MCP-compatible applications to query or interact with Finmo transaction data.

## Pricing
No pricing details are provided in the available content.