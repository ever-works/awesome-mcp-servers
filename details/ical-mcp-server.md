# iCal MCP Server

## Overview
The iCal MCP Server is an MCP server that connects MCP tools and clients to iCalendar-compatible calendars via the iCal open standard. It allows reading and managing calendar and scheduling information using the iCalendar (RFC 5545) format.

- **Name:** iCal MCP Server  
- **Category:** Project management MCP servers  
- **Brand:** icalendar-standard  
- **Slug:** `ical-mcp-server`  
- **Source URL:** https://mcp.pipedream.com/app/ical

## Features
- **iCalendar standard support**  
  - Uses the iCalendar (iCal) open standard for exchanging calendar and scheduling data.  
  - Compatible with iCalendar-capable clients and services.

- **MCP server endpoint**  
  - Static MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Same URL can be used across different MCP-compatible chat or agent clients.

- **Calendar and scheduling access**  
  - Enables MCP tools and applications to read calendar information.  
  - Enables MCP tools and applications to manage scheduling information (e.g., events) via the iCal standard.

- **Client-agnostic integration**  
  - Designed to be added to multiple chat or agent clients.  
  - Configuration guidance available via a central configuration page.

- **Authentication at client setup**  
  - Authentication is performed when adding the server to an application or chat client, while the server URL remains static.

## Integration & Configuration
- **Server URL:** `https://mcp.pipedream.net/v2` (used for all supported clients).  
- **Setup flow:**  
  - Add the server URL to an MCP-compatible chat or agent client.  
  - Authenticate during the add/connect process.  
  - Optionally refer to the configuration documentation provided by the host platform.

## Pricing
The provided content does not list any pricing information or plans for the iCal MCP Server.