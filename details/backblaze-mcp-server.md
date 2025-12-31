# Backblaze MCP Server

**Category:** File Management MCP Servers  
**Brand:** Backblaze  
**Source:** https://mcp.pipedream.com/app/backblaze

## Overview
Backblaze MCP Server is an integration that exposes Backblaze’s S3-compatible cloud storage to MCP tools and clients, enabling low-cost object storage workflows via a unified MCP server endpoint.

## Features
- **S3-compatible cloud storage access**: Integrates Backblaze’s S3-compatible object storage into MCP-compatible applications and tools.
- **Static MCP server endpoint**: Uses a single server URL for all supported MCP clients:
  - MCP Server URL: `https://mcp.pipedream.net/v2`
- **Client-agnostic configuration**: The same server URL works across different MCP chat clients; authentication is handled when adding the server to each application.
- **MCP tools integration**: Designed to be consumed as an MCP server, making Backblaze storage available to tools that support the Model Context Protocol.
- **Low-cost storage workflows**: Built around Backblaze’s low-cost object storage, suitable for budget-conscious storage workflows.
- **Hosted by Pipedream Connect**: Provisioned and operated through Pipedream’s MCP infrastructure.
- **Configuration guidance**: Documentation and examples for adding the server to supported clients are available via the configuration page (referenced from the source site).

## Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your compatible chat client or MCP host.
- Authenticate within your application when prompted to connect to Backblaze storage.

## Pricing
- No explicit pricing details or plans are provided in the available content. Pricing for storage and any related service usage would need to be checked on Backblaze and/or Pipedream directly.