# BingX MCP Server

MCP Server for the BingX crypto exchange, exposing trading and market data capabilities to AI tools over the Model Context Protocol.

---

## Overview

The **BingX MCP Server** connects the BingX crypto exchange to MCP-compatible clients (such as ChatGPT), enabling AI agents and applications to perform trading operations and access market data programmatically via a static MCP endpoint.

**MCP server URL:**

```text
https://mcp.pipedream.net/v2
```

You authenticate when adding the server to your MCP-compatible application.

---

## Features

### Connection & Configuration
- Static MCP server URL usable across different MCP clients.
- Account-based authentication after adding the server to your application.
- Supports integration with popular chat clients (e.g., ChatGPT via OpenAI) using MCP configuration guides.

### Trading Actions

These actions are exposed as MCP tools and can be invoked by AI agents:

- **Trade Set Margin Mode**  
  Switch the margin mode for your BingX trading account.

- **Trade Set Leverage**  
  Adjust leverage settings for supported trading pairs / positions.

- **Trade New Order**  
  Place a new order on BingX (e.g., open a new position or submit a spot/derivatives order, as supported by the underlying BingX component).

- **Trade Query Order**  
  Retrieve detailed information about a specific order.

- **Trade Pending Orders**  
  Get a list of unfilled (open) orders.

- **Trade Cancel Order**  
  Cancel a single existing order.

- **Trade Cancel All Orders**  
  Cancel all open orders.

- **Trade Batch Cancel Orders**  
  Cancel multiple selected orders in a single operation.

- **Trade One-Click Close All Positions**  
  Close all open positions with a single command.

### Market Data Actions

- **Market Get Ticker**  
  Retrieve ticker data for a trading pair.

- **Market Get Open Positions**  
  Retrieve current swap open positions.

- **Market Get Market Trades**  
  Get the latest trades for a given trading pair.

> Note: The interface exposes **24 actions** in total as MCP tools; only the ones listed on the page are detailed here. Additional actions may be available in the full component repository.

---

## Use Cases

- Build AI trading assistants that can place, modify, and cancel orders on BingX.
- Create conversational interfaces for checking open positions and recent trades.
- Automate risk management operations like adjusting leverage or margin mode via AI tools.

---

## Pricing

The provided content does not specify any pricing or plan information for the BingX MCP Server. Pricing details (if any) would need to be obtained from the main service provider or platform documentation.