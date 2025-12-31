# USPS MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** USPS  
**Slug:** `usps-mcp-server`

## Overview
USPS MCP Server exposes United States Postal Service shipping, tracking, and postal services through MCP-compatible endpoints. It is provided via Pipedream Connect as a static MCP server endpoint that you can integrate with compatible chat or agent clients.

## MCP Server Endpoint
- **Base MCP URL:** `https://mcp.pipedream.net/v2`  
- **Usage:** Static URL shared across all clients; authentication is performed when adding the server to your application.

## Features
- **USPS shipping services via MCP**  
  - Access USPS shipping-related capabilities through standardized MCP endpoints.  
- **USPS tracking services via MCP**  
  - Integrate USPS package tracking into MCP-compatible applications.  
- **USPS postal services via MCP**  
  - Make USPS postal functionality (e.g., mail-related operations) available to agents / chat clients via MCP.
- **Static, reusable server URL**  
  - A single MCP server URL (`https://mcp.pipedream.net/v2`) is used across clients, simplifying configuration.  
- **Client-initiated authentication**  
  - Authentication is handled during the “add server” step in each client, rather than by changing the base URL.  
- **Integration with multiple chat / agent clients**  
  - Designed to be added to supported chat clients so they can call USPS MCP endpoints.  
- **Configuration documentation available**  
  - A separate configuration page (not included here) provides setup details for different clients.

## Integration Notes
- Add the server URL to your MCP-enabled client as an external tool/server.  
- Follow the client-specific instructions in its configuration or in the Pipedream configuration page.

## Pricing
- No pricing information is provided in the available content.