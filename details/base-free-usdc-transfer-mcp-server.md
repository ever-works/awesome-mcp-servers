# Base Free USDC Transfer MCP Server

## Overview
Base Free USDC Transfer MCP Server is an open-source Model Context Protocol (MCP) server that enables AI/LLM agents to perform USDC transfers on the **Base** network using **Coinbase CDP** MPC wallet infrastructure. It is designed to integrate on-chain USDC transfers directly into AI workflows, including use within Claude Desktop.

## Features
- **USDC transfers on Base network**
  - Implements an MCP tool/function to transfer USDC on the Base blockchain.
  - Intended to support “free” USDC transfers (gasless or sponsored transfer behavior, as implied by the project name and description).

- **Coinbase CDP MPC Wallet integration**
  - Uses **Coinbase CDP** (Coinbase Developer Platform) wallet infrastructure.
  - Supports MPC (multi-party computation) wallets for secure on-chain operations.

- **MCP server implementation**
  - Fully implemented as an MCP (Model Context Protocol) server for integration with compatible LLM tooling.
  - Exposes tools/functions to LLMs so they can initiate blockchain actions programmatically.

- **Available MCP functions**
  - `tranfer-usdc` – MCP tool to initiate a USDC transfer on the Base network.
  - `create_coinbase_mpc_wallet` – MCP tool to create a Coinbase CDP MPC wallet.

- **Configuration & integration**
  - Includes configuration guidance for obtaining an API key (for Coinbase CDP usage).
  - Provides an example `claude_desktop_config.json` for using the MCP server with **Claude Desktop**.

- **Open-source licensing**
  - Licensed under the **MIT License**, allowing use, modification, and redistribution subject to MIT terms.

## Pricing
- **Open-source / MIT-licensed**: No pricing or paid plans are listed. The server can be used under the terms of the MIT License.
- **Transaction costs**: The project name and description indicate support for “free” USDC transfers on Base (e.g., gasless or sponsored transfers), but no detailed pricing or cost model is specified in the provided content.