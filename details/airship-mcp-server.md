# Airship MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Airship  
**Website / Source:** https://mcp.pipedream.com/app/airship

## Overview
The Airship MCP Server is an implementation of Model Context Protocol (MCP) for Airship’s App Experience Platform (AXP). It exposes Airship’s mobile app engagement and lifecycle messaging capabilities through MCP on Pipedream, allowing compatible chat or agent clients to interact with Airship’s mobile experience features.

## Features
- **MCP Server for Airship AXP**: Implements an MCP-compatible server that connects to Airship’s App Experience Platform.
- **Mobile Engagement Integration**: Provides access to mobile app engagement capabilities (e.g., interacting with Airship features that support in-app and lifecycle messaging workflows).
- **Lifecycle Messaging Capabilities**: Exposes lifecycle-related messaging features from Airship AXP through MCP, suitable for automations and agents.
- **Static Server Endpoint**: Uses a single, static MCP server URL for all clients:  
  `https://mcp.pipedream.net/v2`
- **Client-Agnostic Configuration**: Designed to be added to various MCP-compatible chat clients; authentication occurs when adding the server to the application.
- **Hosted by Pipedream**: Runs on Pipedream’s MCP infrastructure (Pipedream Connect), removing the need to self-host the MCP server.

## Configuration
- **MCP Server URL**: `https://mcp.pipedream.net/v2`  
- **Authentication**: Performed when adding the server to your MCP-compatible client.  
- **Additional Setup Docs**: A full configuration guide is available via Pipedream’s Configuration page (linked from the source page).

## Pricing
No pricing information is provided in the available content.