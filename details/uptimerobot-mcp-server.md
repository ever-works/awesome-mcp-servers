# UptimeRobot MCP Server

## Overview
UptimeRobot MCP Server is an MCP (Model Context Protocol) server that connects model-context-aware agents and chat clients to UptimeRobot. It enables programmatic access to uptime monitoring, alert configuration, and monitor management for websites and services directly from compatible applications.

- **Category:** Monitoring
- **Brand:** UptimeRobot
- **Integration host:** Pipedream
- **MCP endpoint:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) that works across compatible MCP clients.
- Authentication handled when adding the server to your MCP-enabled application.
- Documentation and configuration guidance available via the Pipedream MCP Configuration page.

### Uptime Monitoring Management
- Connects to your UptimeRobot account to manage uptime monitors and alert contacts.
- Designed for use by agents and chat clients (e.g., ChatGPT with MCP) to perform monitoring tasks via tools/actions.

### Available Tools / Actions
The UptimeRobot MCP Server exposes the following actions as tools:

1. **Update Monitor Status**  
   - Update an existing monitor’s status.  
   - Supports pausing or resuming monitoring for a selected monitor.

2. **Create Monitor**  
   - Create a new uptime monitor in UptimeRobot.  
   - Suitable for adding monitoring for new websites, APIs, or services.

3. **Create Alert Contact**  
   - Create a new alert contact within UptimeRobot.  
   - Enables configuration of who should receive alerts when monitors change status.

### Client Setup
- Can be added to various MCP-compatible chat clients.  
- Specific setup guidance is provided for ChatGPT (OpenAI) via a dedicated guide.

## Pricing
- No pricing information is provided in the available content. Use of this MCP server may depend on your underlying UptimeRobot and/or Pipedream plans.