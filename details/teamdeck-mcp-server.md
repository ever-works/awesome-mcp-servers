# Teamdeck MCP Server

Teamdeck MCP Server integrates Teamdeck’s resource management, scheduling, and time-tracking capabilities into MCP-aware applications.

## Overview
- **Type:** MCP Server integration
- **Platform:** Pipedream Connect
- **Purpose:** Bring Teamdeck’s employee-focused resource management features (scheduling, time tracking, vacation tracking) into chat clients or other MCP-compatible tools.

## Features
- **MCP Integration**
  - Exposes Teamdeck functionality through the Model Context Protocol (MCP).
  - Works with any MCP-compatible client via a single static server URL.

- **Static MCP Server Endpoint**
  - Universal MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL for all supported clients; authentication is handled when adding the server to each application.

- **Resource Management (via Teamdeck)**
  - Employee-focused resource planning for agencies and software houses.
  - Centralized management of team allocations and availability.

- **Scheduling**
  - Tools to schedule teams across projects and time periods.

- **Time Tracking**
  - Track working hours across team members and projects.

- **Vacation / Leave Tracking**
  - Track vacations and time off in the same system as scheduling and time tracking.

- **Client Setup Guidance**
  - Instructions available (via the configuration page) for adding the MCP server to different chat clients.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Setup:** Add the server URL to your MCP-compatible client and authenticate during the add process.
- **Additional Docs:** Full configuration details are available on the referenced configuration page within Pipedream Connect.

## Pricing
- Not specified in the provided content.