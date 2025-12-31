# Dub MCP Server

**Website:** https://mcp.pipedream.com/app/dub  
**Category:** Business & Commerce – MCP Servers  
**Tags:** open-source, links, analytics

## Overview
Dub MCP Server is an MCP server integration for Dub, an open-source link management infrastructure. It exposes Dub’s link management, tracking, and analytics capabilities through the Model Context Protocol (MCP), allowing compatible chat or agent clients to create and manage links and access analytics programmatically.

## Features
- **MCP-accessible tools for Dub**  
  - Access Dub functionality via the MCP standard.  
  - Integrate Dub capabilities directly into MCP-compatible chat or agent applications.

- **Open-source link management infrastructure**  
  - Built around Dub’s open-source link management stack.  
  - Suitable for managing short links and redirect infrastructure in an open and extensible way.

- **Link creation and management**  
  - Create new links via MCP.  
  - Manage existing links (e.g., update destinations or configurations) through tools exposed by the server (inferred from “link management infrastructure such as link creation”).

- **Tracking and analytics**  
  - Access tracking data for managed links.  
  - Retrieve analytics related to link usage (e.g., clicks and related metrics, as supported by Dub) through MCP tools.

- **Standard MCP endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2` (works for all supported clients).  
  - Authentication occurs when adding the server to an MCP-compatible application.

- **Client-agnostic integration**  
  - Designed to be used from multiple chat clients or agent runtimes that support MCP.  
  - Configuration guidance available via a central configuration page on Pipedream.

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Hosting / infrastructure:** Powered by Pipedream Connect.  
- **Brand / provider:** Dub integration hosted and surfaced via Pipedream.

## Pricing
No pricing information is provided in the available content.