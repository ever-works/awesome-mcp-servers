# WildApricot MCP Server

Cloud-based MCP server integration for WildApricot’s membership and event management platform.

## Overview
The WildApricot MCP Server connects MCP-compatible clients (such as chat-based tools) to WildApricot, enabling interaction with its cloud-based membership and event management capabilities through a standardized MCP server endpoint.

## Features
- **MCP-compatible server endpoint**: Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) that works across supported MCP clients.
- **WildApricot integration**: Bridges MCP clients with WildApricot’s cloud-based membership and event management platform.
- **Account-based authentication**: Requires authentication when adding the MCP server to an application, ensuring secure access to WildApricot data and actions.
- **Client-agnostic configuration**: Designed to be used with multiple chat or MCP clients; the same server URL applies to all, with per-client configuration handled in the app.
- **Central configuration documentation**: Setup details and client-specific steps are available via a dedicated configuration page on Pipedream.

## Technical Details
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Deployment**: Hosted and managed by Pipedream.
- **Integration scope**: Intended to expose WildApricot’s membership and event management capabilities as tools/actions via MCP (specific tools are loaded dynamically in the interface).

## Pricing
No specific pricing information is provided in the supplied content. Use of this MCP server may be subject to Pipedream’s and/or WildApricot’s standard pricing or subscription terms.