# OpenZeppelin Cairo Contracts MCP Server

Smart contract development MCP server exposing OpenZeppelin’s Cairo contracts for StarkNet and related tooling as an open MCP endpoint.

- **Category:** Blockchain & Crypto MCP Servers
- **Brand:** OpenZeppelin
- **Endpoint:** `https://mcp.openzeppelin.com/contracts/cairo/mcp`
- **Source / Deployment:** [Docker MCP Catalog](https://hub.docker.com/mcp/server/openzeppelin-cairo/tools)
- **Slug:** `openzeppelin-cairo-contracts-mcp-server`
- **Tags:** `starknet`, `smart-contracts`, `openzeppelin`

## Features

### General
- Provides access to **OpenZeppelin Cairo Contracts** via an MCP server.
- Designed for **StarkNet** smart contract development using the Cairo language.
- Exposes contract tooling as **open MCP tools** that other clients can call.
- Integrates with **Docker Desktop** (MCP server can be added directly from Docker Hub).

### Tools
Currently listed tools include (from Docker MCP catalog):

- **`cairo-governor`**  
  - Purpose: Generate a governance contract (e.g., for a DAO) in Cairo.  
  - Behavior:  
    - Produces the **source code** of a governance contract.  
    - Returns the contract source **formatted in a Markdown code block**.  
    - **Does not write to disk** (pure code generation; no file system side effects).

> Note: The catalog page indicates **8 tools** are available under this server, but only `cairo-governor` is explicitly documented in the provided content. Additional tools likely exist but are not listed in the given excerpt.

### Integration / Requirements
- Can be added to Docker Desktop from the MCP catalog via the **“Add to Docker Desktop”** link.
- Requires **Docker Desktop version 4.43 or later** for automatic server addition.

### Related Servers (Ecosystem)
Other OpenZeppelin MCP servers (separate items, but part of the same ecosystem):
- **OpenZeppelin Solidity Contracts MCP Server** – Access to Solidity contracts.
- **OpenZeppelin Stellar Contracts MCP Server** – Access to Stellar contracts.
- **OpenZeppelin Stylus Contracts MCP Server** – Access to Stylus contracts.

## Pricing
No pricing information is provided in the available content. The page does not list any plans or fees for using the OpenZeppelin Cairo Contracts MCP Server.