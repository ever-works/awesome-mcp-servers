# Listen Notes MCP Server

## Overview
Listen Notes MCP Server is a Model Context Protocol (MCP) server that exposes Listen Notes podcast search and discovery capabilities for use inside MCP-compatible applications and workflows.

- **Type:** MCP server / integration
- **Category:** Podcast search and discovery
- **Provider:** Listen Notes (hosted via Pipedream)
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **Podcast search and discovery API access**  
  Access Listen Notes’ podcast search and discovery functionality programmatically through the MCP server to use within compatible chat or automation clients.

- **Static MCP server URL**  
  Uses a single static MCP endpoint (`https://mcp.pipedream.net/v2`) that works for all supported MCP clients.

- **Account-based authentication**  
  Authentication occurs when adding the server to an MCP-compatible application, allowing secure access to Listen Notes features.

- **Multi-client support**  
  Can be added to different chat/MCP clients; configuration instructions are provided per client via the Pipedream configuration UI.

- **Central configuration page**  
  A dedicated configuration page (on Pipedream) guides setup, connection of your account, and client selection.

## Usage
1. Connect your Listen Notes (via Pipedream) account.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add the server URL to your MCP-compatible client and complete authentication.  
4. Use the exposed tools/actions to perform podcast search and discovery inside your workflows.

## Pricing
The provided content does not list any pricing or plans for the Listen Notes MCP Server. Consult the Pipedream or Listen Notes site directly for current pricing details.