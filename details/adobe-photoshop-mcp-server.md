# Adobe Photoshop MCP Server

An MCP server that exposes Adobe Photoshop APIs for automated, programmatic image editing and creative workflows.

## Overview
- **Type:** MCP server (Model Context Protocol)
- **Provider:** Adobe (via Pipedream Connect)
- **Category:** Media processing / image processing, automation, creative workflows
- **Purpose:** Enable applications and chat clients to perform image editing and creative operations through Adobe Photoshop APIs.

## MCP Server URL
- **Base MCP server URL:** `https://mcp.pipedream.net/v2`
- Static URL used by all supported clients.
- Authentication is handled when adding the server to your application.

## Features
- **Adobe Photoshop API integration**
  - Access Adobe Photoshop capabilities programmatically via MCP.
  - Designed for automated and scripted image editing workflows.
- **Universal MCP endpoint**
  - Single static URL (`https://mcp.pipedream.net/v2`) for all compatible MCP clients.
  - Works across different chat and application clients that support MCP.
- **Client-agnostic setup**
  - Can be added to various chat clients and applications that implement MCP.
  - Configuration guidance available on a dedicated configuration page (outside this summary).
- **Pipedream Connect infrastructure**
  - Runs on Pipedream’s "Connect" platform, handling connectivity and request routing to Adobe Photoshop APIs.

## Usage
- Add the MCP server URL to your MCP-compatible client or application.
- Authenticate when prompted during setup in your chosen client.
- Use available tools/endpoints (as exposed by your client) to perform Photoshop-related operations.

## Pricing
- Not specified in the provided content.