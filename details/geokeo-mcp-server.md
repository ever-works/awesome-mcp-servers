# Geokeo MCP Server

Geokeo MCP Server is an MCP (Model Context Protocol) server that exposes Geokeo’s forward and reverse geocoding APIs as MCP actions, enabling location-based functionality within MCP-compatible applications and workflows.

- **Website / Source**: https://mcp.pipedream.com/app/geokeo
- **Category**: Data Access & Integration – MCP Servers
- **Tags**: geocoding, location-intelligence, api
- **MCP Endpoint**: `https://mcp.pipedream.net/v2`

## Features

- **Forward geocoding**  
  - Convert place names, addresses, or location descriptions into geographic coordinates (latitude/longitude).

- **Reverse geocoding**  
  - Convert geographic coordinates (latitude/longitude) into human-readable addresses or place information.

- **MCP-native integration**  
  - Exposes Geokeo geocoding capabilities as MCP actions for use in MCP-compatible chat clients and tools.  
  - Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) for all supported clients.

- **Location-based workflow support**  
  - Designed to be embedded into MCP workflows that require address lookup, coordinate lookup, or other location-intelligence steps.

- **Client-agnostic configuration**  
  - Same MCP server URL is used across different chat / MCP clients; authentication is handled when adding the server to each application.

## Usage

- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible application or chat client.
- Authenticate within your client when prompted.
- Use the exposed actions for forward and reverse geocoding inside your workflows.

## Pricing

- Not specified in the provided content.