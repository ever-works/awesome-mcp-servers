# Yelp Fusion MCP Server

**Category:** Search & Discovery MCP Servers  
**Brand:** Yelp  
**Slug:** yelp-fusion-mcp-server

## Overview
Yelp Fusion MCP Server is an MCP (Model Context Protocol) server that connects MCP-compatible clients to Yelp Fusion. It provides structured access to Yelp’s local business and review data so applications can search, discover, and analyze local businesses directly through the MCP interface.

MCP clients authenticate against a static server URL and can then query Yelp Fusion data as part of their workflows or chat-based tools.

## Features
- **Yelp Fusion integration**: Interfaces directly with Yelp Fusion to surface local business and review data.
- **Structured local business data**: Access machine-readable information about local businesses (e.g., listings, categories, locations) via MCP.
- **Review access**: Retrieve Yelp reviews in a structured format suitable for analysis or downstream automation.
- **Static MCP endpoint**: Single server URL for all MCP clients: `https://mcp.pipedream.net/v2`.
- **Client-agnostic**: Designed to work with any MCP-compatible chat or agent client.
- **Authentication at client setup**: Authentication is performed when adding the server to the client application.
- **Central configuration**: Can be managed via the broader Pipedream Connect configuration flow and documentation.

## Technical Details
- **Protocol**: Model Context Protocol (MCP) server.
- **Base URL**: `https://mcp.pipedream.net/v2`
- **Auth model**: Auth is handled during server addition in the client (details depend on the client and Yelp Fusion requirements).
- **Hosting**: Provided as a managed MCP server by Pipedream.

## Usage
1. Use the static MCP server URL: `https://mcp.pipedream.net/v2` in your MCP-compatible client.  
2. Authenticate when prompted by the client during server setup.  
3. Start issuing MCP tools/commands (as supported by your client) to query Yelp Fusion local business and review data.

## Pricing
The provided content does not include any pricing or plan information for the Yelp Fusion MCP Server.