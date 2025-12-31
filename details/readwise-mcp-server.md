# Readwise MCP Server

**Category:** Document Management MCP Servers  
**Brand:** Readwise  
**Source:** https://mcp.pipedream.com/app/readwise

## Overview
Readwise MCP Server is an MCP-compatible integration that connects MCP agents and chat clients (such as ChatGPT) to your Readwise account. It allows agents to access, search, and work with ebook and article highlights stored in Readwise through standardized tools.

## Features

- **MCP-compatible server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for all supported MCP clients.  
  - Authentication occurs when adding the server to your application.

- **Readwise account integration**  
  - Connects directly to your Readwise account.  
  - Enables access to stored ebook and article highlights via MCP tools.

- **Available MCP tools**  
  - **List Highlights**  
    - Returns a list of highlights from your Readwise library.  
    - Includes pagination metadata.  
    - Rate limit: 20 requests per minute.  
    - Each request returns up to 1000 highlight items.  
    - Intended for bulk retrieval or incremental syncing of highlights.  
  - **Get Highlight Details**  
    - Retrieves detailed information for a specific highlight.  
    - Useful for agents that need full context or metadata for a given highlight.

- **Client setup guidance**  
  - Instructions available for adding the server to supported chat clients (e.g., ChatGPT/OpenAI).  
  - Additional configuration details available on the Pipedream MCP configuration page.

## Technical Details

- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Protocol:** MCP (Model Context Protocol) compatible.  
- **Authentication:** Per-application authentication when adding the server.  
- **Rate Limits (List Highlights):** 20 requests/minute, 1000 items per request.

## Pricing

The provided content does not list any pricing or plans for the Readwise MCP Server. Pricing, if applicable, would need to be obtained from Pipedream or Readwise directly.