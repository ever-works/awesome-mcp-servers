# CoinMarketCap MCP Server

An MCP server that exposes CoinMarketCap cryptocurrency market data (rankings, quotes, listings, and metadata) to MCP-compatible chat or automation clients via Pipedream.

---

## Overview
- **Type**: MCP server / integration
- **Category**: Finance · Cryptocurrency · Market Data
- **Provider / Host**: Pipedream
- **Data Source**: CoinMarketCap
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

Use this static MCP endpoint in any supported client and authenticate when adding the server to your application.

---

## Features

### Market Data Access
- **Get Latest Quotes**
  - Returns the latest market quote for one or more cryptocurrencies.
  - Supports querying by `id`, `slug`, or `symbol` (at least one required).
  - Optional **`convert`** parameter to return prices and market values in multiple fiat and/or cryptocurrency conversions in a single call.

- **Get Latest Listings**
  - Returns a paginated list of all active cryptocurrencies.
  - Includes latest market data for each asset (e.g., price-related fields provided by CoinMarketCap’s listings endpoint).

- **Get ID Map (V1)**
  - Returns a mapping of all cryptocurrencies to unique CoinMarketCap IDs.
  - Useful for resolving symbols or slugs to consistent internal IDs before making other API calls.

- **Get Cryptocurrency Metadata**
  - Returns static metadata for one or more cryptocurrencies.
  - Covers non-price data made available by CoinMarketCap’s metadata endpoint (e.g., descriptive and reference information).

### MCP Integration & Configuration
- Single **static MCP server URL** (`https://mcp.pipedream.net/v2`) usable across all supported clients.
- Authentication handled when adding the server to your MCP-compatible application.
- Works across multiple chat or automation clients; setup instructions are client-specific.
- Central **Configuration page** (linked from the app) for details on connecting and managing the integration.

---

## Usage
1. **Copy MCP Server URL**: `https://mcp.pipedream.net/v2`.
2. **Add to Client**: Register this URL as an MCP server in your chosen chat/agent client.
3. **Authenticate**: Complete authentication when prompted in your application.
4. **Call Tools**: Use the four available tools (Latest Quotes, Latest Listings, ID Map, Cryptocurrency Metadata) from within your MCP client.

---

## Pricing
The provided content does not list any pricing or plans for the CoinMarketCap MCP Server. Pricing, if any, would need to be confirmed directly on Pipedream or CoinMarketCap’s official documentation.