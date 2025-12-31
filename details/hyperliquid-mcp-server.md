# Hyperliquid MCP Server

An MCP server implementation that integrates the Hyperliquid SDK to expose Hyperliquid exchange data to AI agents and tools.

- **Category:** Finance / Market Data MCP Servers  
- **Brand:** hyperliquid  
- **Source:** https://github.com/mektigboy/server-hyperliquid  
- **License:** MIT

## Features

### MCP Integration
- Implements a Model Context Protocol (MCP) server for interacting with Hyperliquid.
- Designed to let AI agents and tools access Hyperliquid exchange data programmatically.

### Available Tools

#### `get_all_mids`
- Retrieves mid prices for all coins listed on Hyperliquid.
- Requires **no inputs**.
- Useful for:
  - Snapshotting market-wide mid prices.
  - Building market overview dashboards.
  - Feeding real-time pricing into trading or analysis agents.

#### `get_candle_snapshot`
- Returns historical candlestick (OHLC-type) data for a given token.
- **Inputs:**
  - `coin` (string): Token symbol on Hyperliquid.
  - `interval` (string): Candlestick interval (e.g. `"15m"`, `"1h"`).
  - `startTime` (number): Start time in milliseconds.
- Useful for:
  - Backtesting and historical analysis.
  - Technical analysis signals.
  - Providing structured time-series data to AI models.

## Use Cases
- Crypto trading strategy research and backtesting.
- Market data feeds for trading bots or AI agents.
- Generating market analytics (mid prices, historical candles) inside MCP-compatible environments.

## Pricing
- No pricing information is provided in the source repository. The project is open source under the MIT license.