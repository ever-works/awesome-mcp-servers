# Alphamoon MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Brand:** Alphamoon  
**Slug:** `alphamoon-mcp-server`

## Overview
Alphamoon MCP Server is a Model Context Protocol (MCP) server that connects Alphamoon’s AI-based document automation and data extraction services to MCP-compatible agents and chat clients. It enables applications to call Alphamoon’s document processing and OCR capabilities through a standard MCP endpoint.

## Features
- **MCP-compatible server**: Exposes Alphamoon’s document automation and data extraction via the Model Context Protocol for integration with MCP-capable agents and chat clients.
- **Static MCP endpoint**: Uses a single MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Account-based access**: Requires connecting an Alphamoon/Pipedream account and selecting a client before use.
- **Authentication at client setup**: Authentication occurs when adding the server to an application, rather than per-URL customization.
- **Configurable per chat client**: Can be added to supported chat clients, with client-specific configuration instructions available.
- **Tool-based interaction**: Exposes Alphamoon’s capabilities as “tools” or actions that MCP agents can call (listed as available tools/actions once loaded).

> Note: The page references “Loading actions / Loading available tools…” without enumerating them, so individual tool names and functions are not specified in the provided content.

## Usage
1. Connect your account in the Pipedream interface.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add the server to your MCP-compatible app or chat client following the client-specific instructions.  
4. Use the exposed tools/actions for AI-based document automation and data extraction.

## Pricing
The provided content does not list any pricing or plan information for Alphamoon MCP Server.