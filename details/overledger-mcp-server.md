# Overledger MCP Server

**Category:** Blockchain & Crypto MCP Servers  
**Brand:** Quant Network  
**Source:** https://mcp.pipedream.com/app/overledger

## Overview
Overledger MCP Server exposes the Overledger enterprise blockchain platform as an MCP-compatible endpoint, allowing MCP clients and chat-based applications to access and orchestrate blockchain capabilities (including smart contract interactions and transaction execution) via a single static server URL.

- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible endpoint**
  - Single static URL usable by any MCP client.
  - Authentication handled when adding the server to an application.

- **Transaction lifecycle tooling**
  - **Prepare Smart Contract Transaction**  
    - Prepares a smart contract transaction for signing on the Overledger platform.  
    - Supports constructing the payload required before signing.
  - **Sign a Transaction**  
    - Signs a prepared transaction using Overledger (Part 2 of the Overledger pattern).  
    - Integrates with Overledger’s signing capabilities for enterprise workflows.
  - **Execute Signed Transaction**  
    - Sends a signed transaction to a blockchain node via Overledger.  
    - Completes the on-chain execution step after signing.

- **Smart contract data access**
  - **Read from a Smart Contract**  
    - Reads data from a specified smart contract on the Overledger network.  
    - Suitable for retrieving on-chain state or view/pure function outputs.

- **Client integration**
  - Designed to be added to chat and MCP clients as a server configuration.  
  - Works across multiple client types via the same MCP server URL.

## Pricing
The provided content does not include any pricing or plan information for Overledger MCP Server.