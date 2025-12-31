# Meetup MCP Server

**Category:** Web Search MCP Servers  
**Slug:** meetup-mcp-server  
**Brand:** Meetup

## Description
The Meetup MCP Server is an MCP-compatible service that integrates with the Meetup platform, enabling discovery and retrieval of Meetup event and group data via the Model Context Protocol (MCP) interface. It is provided via Pipedream Connect and can be used by any MCP-capable client through a static server URL.

## Features
- **Meetup integration via MCP**: Connects MCP clients to the Meetup platform to work with Meetup events and groups.
- **Event and group data access**: Designed to support discovery and retrieval of Meetup event and group information through MCP tools (specific tools are not detailed on the page).
- **Static server URL**: Uses a single static endpoint that works across compatible clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic usage**: The same server URL can be added to different MCP-enabled chat clients.
- **Authentication at configuration time**: Authentication is handled when adding the MCP server to an application (details not specified on the page).
- **Configuration documentation**: A general configuration page is available to guide adding this and other MCP servers to supported clients.
- **Pipedream Connect integration**: Hosted and powered via Pipedream Connect’s MCP infrastructure.

## How to Use
1. Add the MCP server to your MCP-capable app or chat client using:
   - `https://mcp.pipedream.net/v2`
2. Complete authentication when prompted by your client.  
3. Follow your client’s MCP configuration instructions (as referenced on the Configuration page) to enable tools that interact with Meetup data.

## Pricing
Pricing information is not provided on the referenced content. Users may need to refer to Pipedream’s or Meetup’s official sites for any applicable pricing or usage limits.
