# Patreon MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** Patreon  
**Source:** https://mcp.pipedream.com/app/patreon

## Description
The Patreon MCP Server integrates Patreon with the Model Context Protocol (MCP), allowing AI agents and MCP-compatible applications to interact with Patreon creator memberships, patrons, and related subscription data via a standardized server endpoint.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Designed to work with any compatible chat client or MCP-enabled application.

- **Patreon account integration**  
  - Connects a Patreon account to enable access to creator membership and patron data.  
  - Uses account authentication when the server is added to an application.

- **Client-agnostic configuration**  
  - One static URL for all supported MCP clients.  
  - Per-client setup instructions available via a configuration page.

- **Tooling support (actions)**  
  - Exposes Patreon-related tools/actions through the MCP server (exact actions are dynamically loaded in the UI).  
  - Intended for operations around memberships, patrons, and subscriptions within MCP agents.

- **Configuration guidance**  
  - Step-by-step setup for adding the server to chat clients.  
  - Central configuration page for additional details and options.

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Protocol:** Model Context Protocol (MCP)  
- **Integration type:** Remote MCP server hosted by Pipedream

## Pricing
Pricing information is not provided in the available content.