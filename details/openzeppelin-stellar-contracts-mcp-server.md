# OpenZeppelin Stellar Contracts MCP Server

Access OpenZeppelin’s Stellar smart contract templates and libraries via a Model Context Protocol (MCP) server, suitable for programmatic exploration and integration.

## Basic Info
- **Name:** OpenZeppelin Stellar Contracts MCP Server  
- **Category:** Blockchain / Crypto MCP Servers  
- **Ecosystem:** Stellar  
- **Brand:** OpenZeppelin  
- **Docker Hub URL:** https://hub.docker.com/mcp/server/openzeppelin-stellar/tools  
- **Requires:** Docker Desktop **v4.43 or later** to add the server automatically

## Features
- Provides programmatic access to OpenZeppelin Stellar smart contract templates and libraries through MCP.
- Designed for generating Stellar token contracts that follow official standards (fungible, non‑fungible, and stablecoin).
- All tools return source code as Markdown code blocks and **do not write to disk**, suitable for safe exploration and code generation workflows.
- Includes **3 tools**:

### 1. `stellar-fungible`
- Generates a **fungible token** contract.
- Implements the **Fungible Token Standard**, compatible with **SEP‑41**.
- Conceptually similar to **ERC‑20** on Ethereum.
- Outputs the generated contract’s source code formatted in a **Markdown code block**.
- Does **not** write any files to disk.

### 2. `stellar-stablecoin`
- Generates a **stablecoin** contract.
- Uses the **Fungible Token Standard**, compatible with **SEP‑41**.
- Intended for tokens designed to maintain a stable value.
- Outputs the generated contract’s source code formatted in a **Markdown code block**.
- Does **not** write any files to disk.

### 3. `stellar-non-fungible`
- Generates a **non‑fungible token (NFT)** contract.
- Implements the **Non‑Fungible Token Standard**, compatible with **SEP‑50**.
- Conceptually similar to **ERC‑721** on Ethereum.
- Outputs the generated contract’s source code formatted in a **Markdown code block**.
- Does **not** write any files to disk.

## Pricing
- No pricing or plan information is provided in the available content.

## Related MCP Servers (Same Vendor)
- OpenZeppelin Cairo Contracts MCP Server  
- OpenZeppelin Solidity Contracts MCP Server  
- OpenZeppelin Stylus Contracts MCP Server  
(Each provides access to OpenZeppelin contracts for their respective ecosystems.)