# Ergo Blockchain MCP Server

**Category:** Blockchain & Crypto MCP Servers  
**Brand:** ergo-platform  
**Source:** https://github.com/marctheshark3/ergo-mcp

## Overview
Ergo Blockchain MCP Server is a Model Context Protocol (MCP) server for the Ergo blockchain. It connects to Ergo node and explorer APIs to provide balance checks, transaction analysis, address forensics, token search, and network monitoring capabilities for tools that speak MCP.

## Features
- **Node & Explorer Integration**  
  - Interfaces with Ergo full node APIs.  
  - Interfaces with Ergo explorer APIs.  
  - Supports using environment configuration (e.g., `.env.example`) for API endpoints and credentials.

- **Account & Balance Operations**  
  - Check balances for Ergo addresses.  
  - Inspect asset holdings, including ERG and tokens (where supported by explorer APIs).

- **Transaction Analysis**  
  - Analyze individual transactions on the Ergo blockchain.  
  - Inspect transaction details such as inputs, outputs, and associated addresses (via explorer APIs).  
  - Explore transaction history for given addresses.

- **Address & History Inspection**  
  - Retrieve address history from the explorer (transactions and related activity).  
  - Perform forensic address analysis using explorer data (e.g., tracing flows through multiple transactions and addresses).  
  - Cache and log relevant history data (e.g., via `cache/` and `logs/` directories).

- **Token & Asset Search**  
  - Search for tokens on the Ergo blockchain through the explorer.  
  - Query token metadata and holder information (with stored history under `cache/token_holders/history`).

- **Network Monitoring**  
  - Monitor network status using node and/or explorer endpoints (e.g., height, sync status, basic health metrics).  
  - Provide MCP-accessible tools to query current chain state.

- **MCP Server Integration**  
  - Exposes Ergo-specific tools as MCP endpoints for use with MCP-compatible clients.  
  - Structured project layout with `ergo_explorer/`, `scripts/`, and `tests/` directories to support development, scripting, and automated testing.  
  - Includes test configuration via `.env.test` and automated tests in `tests/` and `isolated_tests/`.

- **Documentation & Examples**  
  - Project documentation under `docs/`.  
  - Example environment configuration in `.env.example`.  
  - Scripts in `scripts/` to assist with setup or maintenance tasks (inferred from repository structure).

- **Logging & Diagnostics**  
  - Log directory (`logs/`) for request, response, and error logging.  
  - Helpful for debugging MCP interactions and blockchain queries.

- **Open Source**  
  - Licensed under the MIT license, allowing modification and reuse.

## Pricing
- Not specified in the provided content. The project is an open-source GitHub repository under the MIT license, with no pricing information listed.