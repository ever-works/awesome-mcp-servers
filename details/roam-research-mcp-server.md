# Roam Research MCP Server

**Category:** Document Management MCP Servers  
**Brand:** Roam Research  
**Source:** https://mcp.pipedream.com/app/roamresearch

## Overview
Roam Research MCP Server is an MCP (Model Context Protocol) server that exposes Roam Research’s networked note‑taking and knowledge-graph capabilities to AI agents. It allows applications and chat clients that support MCP to query and manage Roam graphs programmatically.

## Features
- **MCP-compatible server endpoint**  
  - Static server URL for all supported clients: `https://mcp.pipedream.net/v2`  
  - Can be added to any MCP-capable chat client or application.

- **Roam Research integration**  
  - Connects to a user’s Roam Research account.  
  - Enables AI agents and tools to work with Roam’s networked note-taking environment and knowledge graphs.

- **Authentication flow**  
  - Authentication occurs when adding the server to the client/application (no per-client URL needed).

- **Client setup guidance**  
  - Instructions available per chat client on how to add and configure the MCP server.  
  - Links to a configuration page for more detailed setup steps.

- **Tool exposure for agents**  
  - Exposes “available tools” (actions) over MCP for interacting with Roam (listed dynamically in the UI as “Loading actions…/Loading available tools…”).

## Use Cases
- Querying and navigating Roam Research graphs from AI chat clients.  
- Allowing AI agents to read from and manage networked notes and knowledge bases stored in Roam.

## Technical Details
- **Protocol:** Model Context Protocol (MCP) server.  
- **Base URL:** `https://mcp.pipedream.net/v2`  
- **Host platform:** Provided via Pipedream.

## Pricing
No pricing information is provided in the available content.