# Akeneo MCP Server

Product information management (PIM) and data intelligence MCP server integration for Akeneo.

## Overview
The Akeneo MCP Server connects Akeneo’s product information management and data intelligence capabilities to MCP-compatible applications via a static MCP endpoint hosted by Pipedream.

## MCP Server Endpoint
- **MCP server base URL:** `https://mcp.pipedream.net/v2`
- This static URL is used by all clients.
- Authentication is performed when adding the server to your MCP-compatible application.

## Features
- Integrates Akeneo’s product information management (PIM) with MCP.
- Exposes Akeneo product data and related data intelligence capabilities to MCP-aware chat or agent clients (via the shared Pipedream MCP endpoint).
- Uses a single, static MCP URL for all clients, simplifying configuration.
- Works with multiple chat clients that support MCP by adding the same server URL and authenticating per client.

## Configuration
- Add the server to your MCP-compatible application using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
  - Complete setup steps in your chosen chat or agent client.
- Additional generic configuration guidance is available on Pipedream’s **Configuration** page (no Akeneo-specific steps detailed in the provided content).

## Pricing
- No pricing information is provided in the available content.