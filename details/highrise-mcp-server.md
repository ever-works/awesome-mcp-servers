# Highrise MCP Server

Simple CRM software MCP server for exposing Highrise contact and task management to MCP-compatible clients.

## Overview
The Highrise MCP Server provides access to basic CRM capabilities from Highrise via the Model Context Protocol (MCP). It is delivered as a static MCP endpoint that can be added to any supported MCP client, where you then authenticate to your own Highrise / Pipedream account.

- **Item type:** MCP server / integration
- **Category:** Business & Commerce MCP Servers
- **Brand:** Highrise (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Use case:** Work with CRM contacts and tasks from chat or other MCP-enabled applications

## Features
- **MCP-compatible CRM server**
  - Exposes Highrise CRM functionality through the Model Context Protocol.
  - Designed to be used from MCP-capable chat clients and tools.

- **Static server URL**
  - Uses a single, client-agnostic MCP endpoint: `https://mcp.pipedream.net/v2`.
  - Same URL works across different MCP clients; configuration is handled client-side.

- **Authentication at setup time**
  - You authenticate to the server when adding it to your application/client.
  - Keeps the public endpoint static while securing access per user.

- **Simple CRM focus (contacts & tasks)**
  - Intended to expose simple CRM contact management.
  - Intended to expose simple CRM task management.

- **Cross-client setup support**
  - Can be added to multiple chat clients that support MCP.
  - Configuration guidance available via the associated configuration page (external to this summary).

- **Pipedream Connect integration**
  - Powered by Pipedream Connect’s infrastructure for MCP servers.
  - Benefits from Pipedream’s hosted platform for connectivity and management (no local hosting details provided in the content).

## Pricing
The provided content does not list any pricing or plans for the Highrise MCP Server.

## Usage
1. Configure your MCP-compatible client to use the server URL `https://mcp.pipedream.net/v2`.
2. During setup, authenticate as directed by your client or Pipedream/Highrise integration flow.
3. Once connected, use your client’s MCP features to interact with Highrise CRM contacts and tasks.