# Bolt IoT MCP Server

## Overview
The Bolt IoT MCP Server exposes the Bolt IoT platform (Bolt WiFi module, Bolt Cloud, and Bolt Mobile App) into an MCP-compatible environment. It enables control of Bolt IoT devices and collection of sensor and device data through a unified MCP server endpoint.

## Features
- **MCP-compatible IoT control**: Integrates the Bolt IoT platform into any MCP-capable client or chat application.
- **Device control via Bolt WiFi modules**: Provides access to control Bolt WiFi–based IoT devices remotely through the MCP server.
- **Data collection from IoT devices**: Enables retrieval of readings and telemetry from devices connected to the Bolt Cloud.
- **Single static MCP server URL**: Uses a shared MCP endpoint for all clients:
  - Server URL: `https://mcp.pipedream.net/v2`
- **Authentication at client level**: Authentication is handled when adding the server to an MCP-compatible application, allowing secure access to your Bolt IoT account and devices.
- **Works with multiple clients**: Can be added to various MCP chat clients or tools that support MCP servers.

## Configuration
- Copy and use the MCP server URL: `https://mcp.pipedream.net/v2` in your MCP-compatible app.
- Add the server to your chat client or tool following its MCP server configuration instructions.

## Pricing
- Not specified in the provided content.