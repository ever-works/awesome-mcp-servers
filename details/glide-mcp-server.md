# Glide MCP Server

## Overview
Glide MCP Server is an MCP (Model Context Protocol) server provided by Pipedream that lets you connect Pipedream workflows to Glide, so you can build and interact with no‑code business apps created on Glide directly from compatible MCP clients.

- **Category:** Business & Commerce – MCP Servers  
- **Vendor / Brand:** Pipedream  
- **Primary use case:** Integrate Glide no‑code apps into workflows and chat-based tools via MCP.

## Features
- **MCP-compatible endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL works across all supported MCP clients.

- **Glide integration**  
  - Connect a Glide account through Pipedream.  
  - Use the MCP server to interact with Glide-based no‑code business apps from your MCP client (e.g., chat interfaces that support MCP).

- **Client-agnostic configuration**  
  - Add the same MCP server URL to different clients.  
  - Per-client setup instructions are available from Pipedream’s configuration flow.

- **Authentication handled at client add-time**  
  - Authentication is performed when you add the server to your application/client, not per-URL.

- **Tool discovery**  
  - MCP server exposes available tools/actions associated with Glide and Pipedream workflows (listed dynamically as “available tools”).

## Configuration
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup flow:**  
  1. Connect your Pipedream/Glide account in the Pipedream UI.  
  2. Copy the MCP server URL.  
  3. Add the MCP server to your chosen MCP-compatible client.  
  4. Authenticate when prompted by the client.

## Pricing
The provided content does not include any pricing or plan information for Glide MCP Server.