# RunPod MCP Server

An MCP server that connects MCP-compatible clients to RunPod’s AI-focused cloud compute and GPU pods via Pipedream.

## Overview
- **Type**: MCP server / cloud integration
- **Provider**: RunPod (via Pipedream Connect)
- **Category**: Cloud & DevOps MCP Servers
- **Use case**: Provision and use RunPod’s AI compute resources and pods directly from MCP-enabled clients.

## MCP Server URL
- **Static MCP endpoint** (works for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is performed when adding the server in your MCP-compatible application.

## Features
- **Unified MCP endpoint**
  - Single static URL for all supported MCP clients.
- **RunPod integration**
  - Connects MCP clients to RunPod’s AI-oriented cloud compute and GPU pods.
- **Client-agnostic usage**
  - Same server URL can be reused across different MCP-enabled chat or developer clients.
- **Pipedream Connect backing**
  - Integration is powered by Pipedream’s infrastructure and configuration system.
- **Configurable via clients**
  - Add the server to your preferred MCP-compatible app or chat client using its configuration settings.

## Configuration & Setup
- Add the MCP server to your MCP-compatible app using:
  - **Server URL**: `https://mcp.pipedream.net/v2`
  - Complete any authentication flow required by your client.
- Further configuration details are available via the platform’s **Configuration** page (linked from the app).

## Pricing
- Not specified in the provided content.