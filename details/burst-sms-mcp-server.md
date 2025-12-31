# Burst SMS MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Burst SMS  
**Slug:** `burst-sms-mcp-server`

## Overview
The Burst SMS MCP Server is a Model Context Protocol (MCP) server that connects applications to the Burst SMS online SMS platform. It is designed to support smart messaging workflows by exposing Burst SMS functionality as MCP tools that can be used from compatible chat or AI clients.

## Features
- **MCP-compatible SMS integration**: Exposes Burst SMS capabilities via a static MCP server endpoint usable by multiple clients.
- **Single static server URL**: All clients connect using the same endpoint:  
  `https://mcp.pipedream.net/v2`
- **Per-client authentication**: Authentication is handled when adding the MCP server to a specific application or chat client, allowing secure, client-specific access.
- **Multi-client support**: Can be added to different MCP-compatible chat or AI clients; each client can be configured separately.
- **Configuration guidance**: Integration instructions are available through a configuration page linked from the server description.
- **Smart messaging workflows** (via Burst SMS platform): Optimized for building and automating SMS messaging workflows such as notifications, marketing campaigns, and other programmatic SMS use cases.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Integration pattern:** Add as an MCP server in your chat/AI client, then authenticate with your Burst SMS / Pipedream-connected account.

## Pricing
No pricing or plan information is provided in the available content.