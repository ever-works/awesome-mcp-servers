# coin_api_mcp

A Model Context Protocol (MCP) server that exposes CoinMarketCap cryptocurrency market data to MCP-compatible clients, enabling AI applications to query listings, quotes, and detailed coin information.

## Features

- **CoinMarketCap integration**
  - Connects to CoinMarketCap’s API to retrieve up-to-date cryptocurrency market data.
  - Supports access to listings, detailed coin metadata, and latest quotes.

- **MCP-compatible server**
  - Implements the Model Context Protocol so tools can be used directly from MCP-aware clients (e.g., Claude Desktop / Claude.app via Smithery).

- **Available Tools / Endpoints**
  - **`listing-coins`**
    - Returns a paginated list of all active cryptocurrencies with latest market data.
    - Parameters:
      - `start` – pagination start index.
      - `limit` – number of results to return.
      - `price_min` – minimum price filter.
      - `price_max` – maximum price filter.
      - `market_cap_min` – minimum market cap filter.
      - `market_cap_max` – maximum market cap filter.
      - `convert` – target currency for conversion.
      - `sort` – sorting field.
      - `sort_dir` – sorting direction.

  - **`get-coin-info`**
    - Retrieves detailed information about a specific cryptocurrency.
    - Parameters (one or more identifiers):
      - `id` – CoinMarketCap ID.
      - `slug` – coin slug.
      - `symbol` – coin ticker symbol.

  - **`get-coin-quotes`**
    - Fetches the latest market quotes for one or more cryptocurrencies.
    - Parameters (one or more identifiers):
      - `id` – CoinMarketCap ID.
      - `slug` – coin slug.
      - `symbol` – coin ticker symbol.

- **Docker & Python-based setup**
  - Includes a `Dockerfile` for containerized deployment.
  - Python project with `pyproject.toml` for dependency management and packaging.

- **Smithery integration**
  - Can be installed and wired into Claude Desktop via Smithery as “Cryptocurrency Data for Claude Desktop.”

## Installation

- **Via Smithery**
  - Install as a server for Claude Desktop using Smithery (see Smithery link in the repository README).

- **From source (Python)**
  - Clone the repository.
  - Build and install using your default Python interpreter.
  - Run the server as a Python script after installation.

- **Docker**
  - A `Dockerfile` is provided for building and running the server in a containerized environment.

## Configuration

- **CoinMarketCap API key**
  - A CoinMarketCap API key is required for the server to function.
  - Obtain an API key from the CoinMarketCap API portal.
  - Provide the key to the server as described in the repository’s configuration instructions (e.g., environment variable or config setting).

- **Claude.app / Claude Desktop**
  - Can be added to Claude’s settings as an MCP server (configuration details are outlined in the repo for Claude.app / Claude Desktop integration).

## Pricing

- **Pricing information**
  - No pricing details are specified in the provided content for this MCP server itself.
  - Use of CoinMarketCap’s API may be subject to CoinMarketCap’s own pricing and rate limits.