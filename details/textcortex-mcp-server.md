# TextCortex MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** TextCortex  
**Slug:** textcortex-mcp-server

## Description
TextCortex MCP Server integrates the TextCortex AI assistant platform into the Model Context Protocol (MCP). It allows compatible clients and tools to access TextCortex’s content generation and productivity capabilities through a standardized MCP server endpoint.

## Features
- **MCP-compatible server**: Exposes TextCortex AI assistant functionality via an MCP server that can be added to any supported MCP client.
- **Static server URL**: Uses a single static endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: The same MCP server URL works across different chat clients and applications that support MCP.
- **Authentication at setup**: Authentication is performed when adding the MCP server to your application, rather than using per-client URLs.
- **Configuration guidance**: Can be configured using client-specific instructions or via a general configuration page (through Pipedream Connect).
- **Pipedream Connect integration**: Hosted and provided via Pipedream Connect infrastructure.

## Technical Details
- **MCP Endpoint**: `https://mcp.pipedream.net/v2`
- **Integration Model**: Add-as-server within any MCP-capable chat client or tool.

## Pricing
Pricing information is not provided in the available content.