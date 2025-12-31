# Finnhub MCP Server

**Category:** Finance / Market Data MCP Servers  
**Brand:** Finnhub  
**Slug:** finnhub-mcp-server

Free MCP Server integration for accessing Finnhub’s stock, forex, and crypto market data, plus company fundamentals and reference data, via the Finnhub API.

---

## Description
Finnhub MCP Server is an MCP-compatible integration that exposes the Finnhub API to MCP-based applications. It provides programmatic access to real-time and historical market data across stocks, forex, and cryptocurrencies, along with company fundamentals and market reference data. The server is accessed through a static MCP endpoint and is intended to be added as a server within compatible chat or agent clients.

MCP endpoint:
```text
https://mcp.pipedream.net/v2
```

---

## Features
- **MCP server integration**
  - Exposes Finnhub API functionality via the Model Context Protocol (MCP)
  - Usable from MCP-compatible chat and agent clients
  - Single static URL endpoint for all clients

- **Market data access**
  - Stock market data
  - Forex market data
  - Crypto market data

- **Fundamentals & reference data**
  - Company fundamentals
  - Reference data (e.g., instruments and identifiers)
  - Alternative data (as provided by Finnhub)

- **Authentication model**
  - Use a single static MCP server URL (`https://mcp.pipedream.net/v2`)
  - Client-side authentication when adding/configuring the server in your application

- **Configuration support**
  - Works with multiple MCP clients (chat or other interfaces)
  - Additional setup guidance available via a dedicated configuration page (not required for basic usage of the URL)

---

## Usage
1. Use the static MCP server URL:
   ```text
   https://mcp.pipedream.net/v2
   ```
2. Add this server to your MCP-compatible app or chat client.
3. Configure authentication within your client when prompted (Finnhub credentials as required).

---

## Pricing
- The description states “Free API for stock, forex and crypto market.”
- No detailed plan breakdown or paid tiers are provided in the available content.

*(For exact rate limits, quotas, or paid plans, consult Finnhub’s official pricing documentation.)*