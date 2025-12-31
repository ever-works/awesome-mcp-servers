# Crowdin MCP Server

Cloud-based MCP (Model Context Protocol) server that connects MCP-aware applications to Crowdin’s localization and multilingual content management platform via Pipedream.

## Overview
- **Type:** MCP Server / Developer Integration
- **Category:** Business & Commerce – MCP Servers
- **Provider:** Crowdin (via Pipedream)
- **Purpose:** Give MCP-compatible apps access to Crowdin’s cloud-based localization and multilingual content management features.

## Features
- **MCP Server Endpoint**
  - Static MCP server URL: `https://mcp.pipedream.net/v2`
  - Same URL works across all supported MCP clients.
  - Authentication handled when adding the server to your application.

- **Crowdin Localization Integration**
  - Connects MCP-aware applications to Crowdin’s cloud-based localization platform.
  - Supports management of multilingual content through Crowdin.
  - Designed for agile localization use cases, especially for tech teams.

- **Client Configuration Flow**
  - Connect a Crowdin account via Pipedream.
  - Select your chat or MCP client and follow client-specific setup steps.
  - Option to use a dedicated configuration page for full setup details (per Pipedream documentation).

- **Developer Tools Orientation**
  - Positioned as a developer tool for integrating localization workflows into MCP-based apps.
  - Provides “available tools” / actions exposed through MCP for use inside compatible clients (details loaded dynamically in the UI).

## Integration & Setup
- Copy the static MCP server URL and add it to your MCP-compatible app or chat client.
- Authenticate your Crowdin/Pipedream connection during server addition.
- Optionally refer to the Pipedream configuration page for step-by-step client-specific guidance.

## Pricing
- Not specified in the provided content.