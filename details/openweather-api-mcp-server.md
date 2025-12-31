# OpenWeather API MCP Server

## Overview
The **OpenWeather API MCP Server** exposes OpenWeather’s current, forecast, and historical weather data via the MCP (Model Context Protocol), allowing compatible clients and chat-based tools to query weather information through a unified server endpoint.

- **Category:** Data Access / Integration – MCP Servers
- **Provider / Brand:** OpenWeather (hosted via Pipedream)
- **Protocol:** MCP (Model Context Protocol)
- **Primary Use Cases:** Weather-aware applications, travel planning, forecasting tools, and any MCP-enabled client that needs structured weather data.

## Features
- **Comprehensive Weather Data Coverage**
  - Current weather conditions
  - Forecast weather data
  - Historical weather information

- **Single Static MCP Endpoint**
  - MCP server URL: `https://mcp.pipedream.net/v2`
  - Same URL works for all compatible MCP clients

- **Client‑Agnostic Integration**
  - Designed to be added to various MCP-compatible chat or agent clients
  - Authentication handled when adding the server to your application

- **Centralized Configuration**
  - Connect your OpenWeather account through Pipedream’s configuration flow
  - Use the same configured server across multiple clients

- **MCP Tools Exposure**
  - Exposes OpenWeather data as MCP tools/actions (current, forecast, and historical queries)
  - Tools are discoverable from within MCP-capable clients once the server is added

## Setup & Usage
1. **Configure OpenWeather API** via Pipedream (connect your account).
2. **Copy the MCP server URL:** `https://mcp.pipedream.net/v2`.
3. **Add the server to your MCP-compatible app or chat client** and complete authentication.
4. **Use the available MCP tools** to fetch current, forecast, and historical weather data.

## Pricing
The provided content does not include any pricing or plan information for the OpenWeather API MCP Server.