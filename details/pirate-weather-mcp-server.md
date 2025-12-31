# Pirate Weather MCP Server

## Overview
Pirate Weather MCP Server provides access to the Pirate Weather API through the Model Context Protocol (MCP), exposing a Dark Sky–compatible weather forecast API for use in MCP-enabled applications and chat clients.

- **Type:** MCP server / data-access integration
- **Category:** Data-access & integration MCP servers
- **Use cases:** Weather data retrieval, forecast queries, smart home automation, and other applications needing programmatic weather information.

## Features
- **MCP-compatible weather access**: Exposes Pirate Weather API functionality via a standard MCP server endpoint.
- **Dark Sky–compatible API**: Designed as a compatible alternative to the Dark Sky API, easing migration from Dark Sky–based integrations.
- **Forecast and weather data retrieval**: Supports querying forecast and weather data (hourly/daily/current conditions) via MCP tools (details are loaded dynamically in the UI).
- **Static MCP server URL**: Uses a single static endpoint that works across clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: Can be added to different MCP-enabled chat clients; configuration instructions are provided per client.
- **Authentication handled at client setup**: You authenticate when adding the MCP server to your application, rather than changing the server URL.
- **Smart home automation usage**: Positioned for use in smart home or automation workflows where weather conditions and forecasts inform triggers or behaviors.

## Configuration
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Setup flow:**
  - Connect your account in Pipedream.
  - Select your client and follow client-specific instructions to add the MCP server.
  - Authenticate when adding the server to your app.

## Pricing
The page describes the underlying forecast API as **“Free, Open, and Documented”**, but does not list specific pricing plans or tiers for this MCP server. No detailed pricing information is provided in the available content.