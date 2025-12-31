# Slybroadcast MCP Server

## Overview
Slybroadcast MCP Server exposes Slybroadcast’s patented direct-to-voicemail delivery technology through the Model Context Protocol (MCP). It enables MCP-compatible agents and applications to orchestrate voicemail campaigns that deliver messages directly to mobile voicemail inboxes without initiating a traditional phone call.

- **Category:** Messaging MCP Servers  
- **Brand:** slybroadcast  
- **Slug:** slybroadcast-mcp-server  
- **Source URL:** https://mcp.pipedream.com/app/slybroadcast

## Features
- **Direct-to-voicemail delivery**: Send voice messages directly to the voicemail boxes of mobile phones, bypassing standard ringing/call flows.
- **MCP integration**: Exposes Slybroadcast capabilities as an MCP server so MCP-compatible agents and tools can programmatically manage voicemail campaigns.
- **Campaign orchestration**: Designed for orchestrating voicemail-based campaigns (e.g., notifications, reminders, announcements) via MCP agents.
- **Static MCP server endpoint**: Uses a single static URL for all clients:  
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic access**: The same MCP server URL is intended to work with multiple chat or agent clients that support MCP.
- **Authentication at client setup**: Authentication is performed when adding/configuring the MCP server in your application or chat client.

## Integration & Setup
- **Server URL**: Add `https://mcp.pipedream.net/v2` as an MCP server in your MCP-capable app or chat client.
- **Configuration guidance**: Additional configuration details are available on the Pipedream MCP Configuration page (linked from the source page).

## Pricing
Pricing information is not provided in the available content.