# GTmetrix MCP Server

Performance testing and monitoring tool integrating GTmetrix with MCP-compatible chat or agent clients.

## Overview
The GTmetrix MCP Server exposes GTmetrix’s website performance testing and monitoring capabilities via a standard Model Context Protocol (MCP) endpoint, allowing you to trigger and work with GTmetrix tests directly from compatible applications (e.g., Pipedream-based workflows and other MCP clients).

## Features
- **MCP-compatible endpoint**  
  - Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Can be added to any supported MCP chat or agent client.
- **Access to GTmetrix capabilities**  
  - Provides MCP-based access to GTmetrix website performance testing features.  
  - Enables use of GTmetrix monitoring functionality from within workflows and chat clients.  
  - Designed to integrate GTmetrix testing and monitoring into Pipedream-powered automations.
- **Centralized configuration**  
  - Single server URL for configuration across tools.  
  - Authentication handled when adding the server within each client.  
  - Additional configuration details available via a dedicated configuration page (not client-specific).

## Integration
- **Pipedream Connect**: Built and provided by Pipedream, using the Pipedream Connect infrastructure.  
- **Client-agnostic setup**: The same MCP endpoint can be reused across multiple MCP-compatible chat clients.

## Pricing
Pricing information is not specified in the provided content.