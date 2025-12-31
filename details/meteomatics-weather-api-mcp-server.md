# Meteomatics Weather API MCP Server

## Overview
Meteomatics Weather API MCP Server provides MCP-compatible applications with access to Meteomatics’ weather and climate data, exposing over 1,800 meteorological and environmental parameters via a unified MCP endpoint.

- **Category:** Data Access & Integration – MCP Servers  
- **Provider / Brand:** Meteomatics (via Pipedream Connect)  
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible weather data access**  
  - Exposes Meteomatics Weather API through the Model Context Protocol (MCP) for use in compatible chat and agent clients.
- **Extensive parameter coverage**  
  - Access to weather and climate data from a collection of 1,800+ parameters (e.g., temperature, precipitation, wind, and other environmental metrics).  
- **Static server URL**  
  - Uses a single, static MCP server URL (`https://mcp.pipedream.net/v2`) that works across supported MCP clients.  
- **Per-client authentication**  
  - Authentication is performed when adding the server to each application or chat client (credentials not embedded in the URL).  
- **Client-agnostic integration**  
  - Designed to be added to multiple MCP-enabled chat clients and tools, following each client’s configuration method.  
- **Central configuration reference**  
  - Configuration details and setup steps are documented on a central configuration page (linked from the app page).

## Integration Details
- **How it’s used**:  
  - Add the MCP server URL to an MCP-compatible client.  
  - Authenticate with the Meteomatics Weather API / Pipedream Connect when prompted.  
  - Query or consume weather and climate data parameters via the client’s MCP tools interface.
- **Platform**:  
  - Delivered via Pipedream Connect infrastructure.

## Pricing
- Not specified in the provided content. No plan or pricing details are available from the given source.
