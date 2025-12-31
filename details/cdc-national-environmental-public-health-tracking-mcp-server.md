# CDC National Environmental Public Health Tracking MCP Server

## Overview
The CDC National Environmental Public Health Tracking MCP Server exposes data from the National Environmental Public Health Tracking Network via the MCP (Model Context Protocol). It enables MCP-compatible clients to query linked health and environmental datasets collected from national, state, and city sources.

Source: [Pipedream app page](https://mcp.pipedream.com/app/cdc_national_environmental_public_health_tracking)

## Features
- **MCP-compatible data access**: Provides an MCP Server endpoint that can be added to any MCP-capable client or application.
- **Unified health and environmental data**: Surfaces data from the CDC’s National Environmental Public Health Tracking Network, combining health outcomes and environmental exposure information.
- **Multiple data sources**: Incorporates data from national, state, and city-level providers.
- **Linked datasets**: Facilitates exploration of relationships between environmental indicators and public health metrics.
- **Central static endpoint**: Uses a single static MCP server URL that works across clients: `https://mcp.pipedream.net/v2`.
- **Client-agnostic integration**: Designed to be added to different chat or MCP clients by configuring the same server URL.

## Technical Details
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Protocol**: Model Context Protocol (MCP)
- **Provider / Host**: Pipedream Connect
- **Data origin**: CDC National Environmental Public Health Tracking Network

## Use Cases
- Query environmental indicators (e.g., air quality, pollutants) alongside associated health outcomes.
- Explore spatial or temporal trends in environmental and health data across jurisdictions.
- Integrate environmental public health datasets into AI assistants, analytics tools, or custom MCP-enabled applications.

## Pricing
No pricing information is provided in the available content.