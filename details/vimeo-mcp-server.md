# Vimeo MCP Server

## Overview
The Vimeo MCP Server is an MCP-compatible endpoint that allows MCP-enabled tools and chat clients to interact with Vimeo’s video platform for uploading, managing, and accessing video content. It is hosted by Pipedream and accessed via a static MCP server URL.

- **Item type:** MCP Server / integration
- **Provider:** Pipedream
- **Platform:** Vimeo
- **Category:** Media processing / video management

## Features
- **MCP-compatible server endpoint**  
  - Exposes Vimeo functionality through the Model Context Protocol (MCP).  
  - Usable from multiple MCP clients via a single static URL.

- **Static server URL**  
  - Server endpoint: `https://mcp.pipedream.net/v2`  
  - Same URL works for every supported MCP client.  
  - Authentication occurs when adding the server to an MCP-enabled application.

- **Vimeo account integration**  
  - Connects to a Vimeo account for managing video assets.  
  - Uses Vimeo’s capabilities for HD video hosting and tools such as uploading, screen recording, live streaming, editing, collaboration, sharing, and video management (as exposed through Pipedream’s MCP tools).

- **Client configuration support**  
  - Designed to be added to different chat / MCP clients.  
  - Configuration guidance available via a central configuration page (outside the provided content).

- **Tool-based interaction**  
  - Provides MCP “tools” or “actions” for interacting with Vimeo (exact tools not listed in the provided content, but surfaced as “available tools” within the integration UI).

## Setup
1. Connect your Vimeo account within the Pipedream Vimeo MCP Server page.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this server URL to your MCP-compatible app or chat client.  
4. Authenticate when prompted in your application.

## Pricing
The provided content does not list any pricing or plan details for the Vimeo MCP Server. Pricing information is not available from the supplied text.