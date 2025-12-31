# Fixer MCP Server

## Overview
Fixer MCP Server provides access to foreign exchange rates and currency conversion via a JSON API, exposed as an MCP-compatible server endpoint that can be integrated into MCP-capable chat or agent applications.

- **Category:** Finance / Market Data (MCP Server)
- **Brand:** Fixer
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Use case:** Retrieve FX rates and perform currency conversions programmatically in MCP-enabled environments.

## Features
- **Foreign exchange rates API**
  - Access up-to-date FX rates via JSON responses.
  - Designed for use in MCP-compatible tools and environments.

- **Currency conversion**
  - Convert between currencies using the Fixer-backed rate data.

- **MCP-compatible server**
  - Exposes functionality as an MCP server endpoint for integration with MCP-capable chat clients and applications.
  - Static base URL (`https://mcp.pipedream.net/v2`) used for all clients; authentication handled when adding the server to the target application.

- **Client-agnostic configuration**
  - Same server URL works across different MCP clients.
  - Can be added to various chat/agent clients that support MCP, following their respective setup instructions.

## Integration & Configuration
- Connect your Fixer account within the Pipedream-based configuration flow.
- Copy and use the static MCP server URL in your MCP-enabled app.
- Add the server to your chat client or agent framework and complete authentication as prompted.

## Pricing
- Not specified in the provided content.