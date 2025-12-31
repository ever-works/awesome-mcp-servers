# Fitbit MCP Server

An MCP server integration for Fitbit that exposes Fitbit activity and health tracking data to MCP-compatible clients via the Fitbit API.

## Overview
- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Brand:** Fitbit (by Pipedream)
- **Primary function:** Provide MCP clients with access to Fitbit activity tracking and related health data through a standardized MCP endpoint.

## MCP Server URL
- **Base URL:** `https://mcp.pipedream.net/v2`
- Static URL used by all supported MCP clients.
- Authentication is performed when adding/configuring the server in the client.

## Features
- **Fitbit API integration**
  - Connects to Fitbit to retrieve activity tracking and related health data (e.g., steps, workouts, other Fitbit-tracked metrics, as available via the Fitbit API).
- **MCP-compatible endpoint**
  - Exposes Fitbit data through a single MCP server URL usable by multiple MCP clients.
- **Client-agnostic configuration**
  - Same server URL works across different chat or MCP clients.
  - Authentication handled within each client during setup.
- **Pipedream Connect platform**
  - Built and hosted via Pipedream Connect infrastructure.

## Integration & Setup
- Add `https://mcp.pipedream.net/v2` as an MCP server in your chat or MCP client.
- Authenticate with Fitbit when prompted by the client.
- Optionally consult the platform’s Configuration page for client-specific setup instructions.

## Pricing
- No pricing information is provided in the available content.

## Links
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Pipedream Connect:** https://pipedream.com/connect