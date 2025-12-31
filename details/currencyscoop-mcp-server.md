# CurrencyScoop MCP Server

**Category:** Finance / Market Data MCP Servers  
**Brand:** CurrencyBeacon  
**Slug:** currencyscoop-mcp-server

## Description
The CurrencyScoop MCP Server is an MCP-compatible service that connects to the CurrencyBeacon/CurrencyScoop REST API to provide real-time and historical foreign exchange (FX) and cryptocurrency rates to MCP clients through a standardized server interface.

## Features
- **MCP-compatible server**: Exposes CurrencyBeacon/CurrencyScoop data via a standardized Model Context Protocol (MCP) server interface for use in compatible chat or AI clients.
- **Real-time exchange rates**: Access up-to-date FX rates for fiat currencies and cryptocurrencies.
- **Historical exchange rates**: Retrieve past FX and crypto rates for historical or analytical use cases.
- **Fiat and crypto coverage**: Supports both traditional (fiat) currency pairs and cryptocurrencies.
- **Static MCP endpoint**: Uses a single static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Application-level authentication**: Authentication is handled when adding/configuring the server in your application rather than changing the server URL.
- **Client-agnostic setup**: Can be added to different MCP-compatible chat clients using the same server URL.

## Integration & Usage
- Add the MCP server using the static URL `https://mcp.pipedream.net/v2` in your MCP-compatible client.
- Configure authentication and any client-specific settings within your application.
- Detailed setup instructions are available via the provider’s configuration documentation.

## Pricing
Pricing details are not provided in the available content.