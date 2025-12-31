# Outline MCP Server

Integration: Product (MCP Server / Developer Tool)

## Overview
The Outline MCP Server is a Model Context Protocol (MCP) integration that connects AI clients to Outline, a team knowledge base and wiki. It is provided and hosted by Pipedream, exposing a static MCP server endpoint that clients can use to access organizational documentation in a structured way.

- **Category:** Document Management MCP Server
- **Use case:** Give AI agents structured access to a team knowledge base / wiki stored in Outline
- **Brand:** Outline
- **Host / Provider:** Pipedream

## Features
- **Static MCP server endpoint**  
  - Single, static URL for all supported MCP clients:  
    - `https://mcp.pipedream.net/v2`
  - Same endpoint reused across clients; authentication handled per-application.

- **Outline integration**  
  - Connects to an existing Outline account.  
  - Targets Outline as a **team knowledge base & wiki** and **file storage** backend.

- **Client-agnostic setup**  
  - Designed to work with multiple “chat clients” / AI frontends that support MCP.  
  - Instructions are provided per client type (via the “Select your chat client” flow).

- **Authentication flow**  
  - You connect your Outline account through Pipedream.  
  - Authentication occurs when adding the MCP server to your client application (not embedded in the URL).

- **Configuration support page**  
  - Dedicated configuration documentation is referenced: a full **Configuration page** for more detailed setup steps.

- **Tooling exposure (MCP tools)**  
  - Exposes “Available tools” to clients once configured (listed dynamically as “Loading actions / available tools” in the UI).  
  - These tools are the MCP actions through which AI agents interact with Outline content.

## Setup / How It Works (from available info)
1. **Connect your Outline account** in the Pipedream Outline MCP Server interface.  
2. **Copy the MCP server URL:** `https://mcp.pipedream.net/v2`.  
3. **Add the server URL to your MCP-compatible chat client** and follow that client’s instructions.  
4. **Authenticate** during client setup to authorize access to your Outline workspace.  
5. The client then discovers and uses the **Available tools** exposed by the server for interacting with Outline.

## Pricing
The provided content does not list any pricing or plans for the Outline MCP Server. No pricing information is available in the source.

## Links
- Outline MCP Server page: https://mcp.pipedream.com/app/outline
- MCP server URL: `https://mcp.pipedream.net/v2`
- Configuration page: linked as “Configuration page” from the app UI
- Provider (Pipedream): https://pipedream.com
- Outline (brand): https://www.getoutline.com