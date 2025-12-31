## Mboum MCP Server

**Category:** Finance & Market Data MCP Servers  
**Slug:** `mboum-mcp-server`

Mboum MCP Server is an MCP integration that connects to Mboum’s stock market APIs to provide intraday and end‑of‑day market data, options information, technical indicators, and news directly into MCP‑compatible applications.

### Features

- **Mboum API integration**
  - Connects to Mboum’s stock scanning and market data APIs via a unified MCP server.
  - Supports both intraday and end‑of‑day data access.
  - Exposed as ~45 actions available as MCP tools.

- **Server configuration**
  - Static MCP server URL: `https://mcp.pipedream.net/v2` (authentication handled when adding to the client/app).
  - Designed to be added as a server in compatible chat or MCP clients.

- **Market search & discovery**
  - **Search Markets**: Search for stocks, ETFs, and other financial instruments.
  - **Get Market Tickers**: Retrieve a comprehensive list of stock tickers and symbols with detailed information.

- **Symbol & company data**
  - **Get Ticker Summary**: Access key statistics, financial metrics, and company overview for a given ticker.
  - **Get Revenue Data**: Retrieve detailed company revenue breakdown, trends, and segment information.

- **Corporate actions & regulatory data**
  - **Get Stock Splits**: Get upcoming and historical stock split data (ratios, dates, and company info).
  - **Get SEC Filings**: Retrieve SEC filings such as 10‑K, 10‑Q, 8‑K, and other regulatory documents.

- **Market data & quotes**
  - **Get Realtime Quote**: Get real‑time stock quote information, including current price, volume, and market data. *(truncated in source but clearly referenced as a realtime quote action)*
  - Intraday and end‑of‑day stock price data via Mboum’s APIs (implied by product description).

- **Options & derivatives**
  - **Get Unusual Options Activity**: Retrieve unusual options activity, including high volume and large trades that deviate from typical patterns.

- **Screening & analytics**
  - **Get Stock Screener Results**: Screen stocks based on financial criteria and filters.

- **Technical indicators**
  - **Get Stochastic Oscillator (STOCH)**: Calculate the Stochastic Oscillator to identify momentum and potential reversal points.
  - **Get Simple Moving Average (SMA)**: Calculate the Simple Moving Average for stocks and crypto.
  - **Get Relative Strength Index (RSI)**: Calculate RSI to measure momentum and identify overbought/oversold conditions.

> Note: The platform mentions 45 total actions; only the actions explicitly listed in the provided content are included here.

### Pricing

No pricing information is provided in the available content.