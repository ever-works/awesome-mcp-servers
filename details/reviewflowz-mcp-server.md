# Reviewflowz MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** reviewflowz  
**Source:** <https://mcp.pipedream.com/app/reviewflowz>

## Overview
Reviewflowz MCP Server integrates the Reviewflowz review software with MCP-compatible chat or agent clients. It enables applications to connect to Reviewflowz via a common MCP endpoint operated by Pipedream.

## Features
- **MCP-compatible endpoint**: Exposes Reviewflowz functionality through a standard MCP server interface.
- **Static server URL**: Uses a single shared endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client authentication**: Authentication is handled when adding the server to each client, allowing multiple applications to use the same base URL securely.
- **Client-agnostic integration**: Can be added to different MCP-capable chat clients or tools; setup is guided per client.
- **Central configuration resources**: Additional setup and configuration details are available via a dedicated configuration page on the host platform (Pipedream Connect).

## Usage
1. Configure `https://mcp.pipedream.net/v2` as an MCP server in your MCP-compatible client.
2. Authenticate within your client when prompted.
3. Follow client-specific instructions from the configuration resources to complete integration.

## Pricing
No pricing information is provided in the available content.