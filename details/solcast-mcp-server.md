# Solcast MCP Server

Solcast MCP Server is an MCP integration that gives AI agents programmatic access to Solcast’s global solar resource assessment and forecasting data, including irradiance and PV power predictions.

---

## Overview
- **Type:** MCP server / data-access integration
- **Category:** Data Access Integration – MCP Servers
- **Provider / Brand:** Solcast (via Pipedream)
- **Scope:** Global (worldwide coverage)
- **Primary Use Cases:** Solar resource assessment, PV power forecasting, weather- and irradiance-aware automation, energy and grid applications.

---

## Features

### MCP Integration
- Exposes Solcast data via the **Model Context Protocol (MCP)** for use by AI agents and compatible chat clients.
- Accessible through a **single static MCP server URL**: `https://mcp.pipedream.net/v2`.
- Authentication handled when adding the server to your MCP-compatible application.

### Available Tools / Actions
Three main actions are exposed as MCP tools:

1. **Get Weather Forecast**
   - Retrieves **irradiance and weather forecasts** for a specified location.
   - Forecast horizon: **from the present up to 14 days ahead**.
   - Data derived from **satellite** and **numerical weather models**.
   - Designed for planning and forecasting solar generation and related weather-dependent operations.

2. **Get Monthly Averages**
   - Returns **monthly weather averages** for a specified location.
   - Useful for **climatological baselines**, long-term solar resource assessment, and planning PV system performance.

3. **Get Live Weather**
   - Provides **irradiance and weather estimated actuals** in **near real-time**.
   - Includes data for the **past 7 days** for a given location.
   - Data derived from **satellite** and **numerical weather models**.
   - Supports monitoring, operational optimization, and short-term analysis of solar conditions and PV output.

### Data Types and Coverage
- **Solar resource data:** global solar irradiance estimates and forecasts.
- **PV power–related predictions:** suitable for solar PV performance and production use cases.
- **Weather data:** forecasts and near real-time / historical (last 7 days) conditions.
- **Global coverage:** data available worldwide.

### Integration & Configuration
- Works with multiple **MCP-compatible chat clients**; users select their client and follow specific setup instructions.
- Central documentation and configuration guidance available via Pipedream’s configuration pages and GitHub action definitions.

---

## Pricing
Pricing information is not provided in the available content. Users should refer to Solcast or Pipedream directly for current pricing and usage limits.

---

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Hosted by:** Pipedream
- **Documentation Links:**
  - Get Weather Forecast action: GitHub (Pipedream components)
  - Get Monthly Averages action: GitHub (Pipedream components)
  - Get Live Weather action: GitHub (Pipedream components)
- **Protocols / Models:** Satellite-based data and numerical weather models underpin the irradiance and weather outputs.