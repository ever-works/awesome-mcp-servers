# Adalo MCP Server

No-code app development platform integration

## Overview
The Adalo MCP Server is an MCP (Model Context Protocol) server that enables tools and agents to interact programmatically with Adalo, a no-code app development platform. It is provided via Pipedream Connect and can be used by any compatible MCP client through a single static URL.

- **Category:** Development Tools – MCP Servers
- **Use Case:** Programmatic access to Adalo apps and resources from MCP-compatible chat clients and tools
- **Provider:** Pipedream (integrating with Adalo)

## Features
- **MCP-compatible server for Adalo**
  - Exposes Adalo functionality through the Model Context Protocol.
  - Designed for integration with MCP-aware chat clients and agents.

- **Static server endpoint**
  - Single URL for all clients: `https://mcp.pipedream.net/v2`.
  - Works across different applications without needing per-client endpoints.

- **Authentication at client setup**
  - Authentication is handled when adding the server to your MCP-compatible application.
  - Supports secure connection to your Adalo-related resources via Pipedream.

- **Client-agnostic setup**
  - Can be added to various chat clients that support MCP.
  - Configuration guidance available through a dedicated configuration page (not client-specific in this summary).

- **Hosted by Pipedream Connect**
  - Managed infrastructure hosted by Pipedream.
  - Terms, privacy, and cookies managed under Pipedream’s policies.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Setup flow (high level):**
  1. Add the above MCP server URL to your MCP-compatible chat client or tool.
  2. Complete authentication when prompted by the client.
  3. Start using Adalo-related tools / resources via the MCP integration.

## Pricing
The provided content does not specify any pricing or plans for the Adalo MCP Server. For current pricing (if any), refer to Pipedream’s or Adalo’s official documentation or billing pages.