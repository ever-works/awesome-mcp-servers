# New York Times MCP Server

**Category:** Web Search MCP Servers  
**Brand:** The New York Times  
**Slug:** `new-york-times-mcp-server`

## Description
The New York Times MCP Server exposes the New York Times APIs via the Model Context Protocol (MCP), allowing compatible MCP clients and chat applications to programmatically search and retrieve New York Times articles and related metadata across sections such as politics, technology, and opinion.

## Features
- **MCP-compatible endpoint**: Provides a static MCP server URL that works with any MCP-compatible client:  
  `https://mcp.pipedream.net/v2`
- **NYT article search and retrieval**: Enables MCP clients to search New York Times content and retrieve articles programmatically.
- **Access to article metadata**: Exposes metadata associated with New York Times articles (e.g., for filtering, organizing, or displaying structured information in clients).
- **Multi-section coverage**: Supports content across many New York Times sections, including politics, technology, and opinion.
- **Client-agnostic integration**: Designed to be added to various chat or MCP clients via configuration, using the same static server URL.
- **Authentication at client setup**: Authentication is handled when adding the server to your application, keeping the endpoint itself static.

## Configuration
- MCP server base URL: `https://mcp.pipedream.net/v2`
- Added to clients via each client’s MCP/server configuration flow (see the provider’s configuration documentation for detailed steps).

## Pricing
- Not specified in the provided content.