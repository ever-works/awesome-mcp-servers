# goldrush-mcp-server

## Overview
GoldRush MCP Server exposes GoldRush APIs as MCP resources and tools, enabling LLMs to interact with blockchain data across 100+ chains.

## Features
- **Multi-chain**: 100+ supported chains including Ethereum, Polygon, Base, BSC, Avalanche, and more
- **REST API**: Full GoldRush Foundational API — balances, transactions, prices, NFTs, approvals
- **WebSocket streaming**: Real-time OHLCV price feeds and DEX pair monitoring
- **CLI**: Terminal-first blockchain queries via `npx @covalenthq/goldrush-cli`
- **x402**: Pay-per-request access using USDC on Base — no API key required

## Installation
```bash
npx @covalenthq/goldrush-mcp-server
```

## Configuration
Set `GOLDRUSH_API_KEY` environment variable with your key from https://goldrush.dev

## Links
- GitHub: https://goldrush.dev/docs/goldrush-mcp-server
- npm: https://www.npmjs.com/package/@covalenthq/goldrush-mcp-server
- Docs: https://goldrush.dev/docs
- Agent Skills: https://github.com/covalenthq/goldrush-agent-skills
