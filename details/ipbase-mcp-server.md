# ipbase MCP Server

**Category:** Data Access & Integration – MCP Servers  
**Brand:** ipbase  
**Slug:** `ipbase-mcp-server`

## Overview
The ipbase MCP Server exposes the ipbase IP geolocation API through the Model Context Protocol (MCP) interface. It provides programmatic access to global IP geolocation data from compatible MCP clients.

## Features
- **MCP-compatible server**: Accessible via a static MCP server URL that can be added to any supported MCP client or chat application.
- **Global IP geolocation**: Connects to ipbase’s IP geolocation API, designed to cover IP addresses worldwide.
- **Single static endpoint**: Uses a unified server URL:  
  `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: The same URL works for all MCP-enabled clients; configuration happens within the client.
- **Authentication at configuration time**: Authentication is performed when adding the server to your application, rather than requiring per-request setup in this description.
- **Hosted by Pipedream Connect**: The MCP server is operated via Pipedream’s infrastructure, abstracting hosting and runtime management from the user.
- **Configuration docs available**: A separate configuration page (not included here) provides step-by-step instructions for connecting various chat or MCP clients.

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible chat client or application.
- Authenticate when prompted during the server setup flow within your client.

## Pricing
Pricing details are not provided in the available content.