## BuyWhere MCP Server

**Product search and price comparison MCP server** for Singapore and Southeast Asia. Gives AI agents real-time access to 260K+ products across major SEA merchants including Lazada, Shopee, Courts, and FairPrice.

## Features

- **Real-time product search** — query by name, category, or price range across 260K+ products
- **Price comparison** — compare prices across multiple merchants in one response
- **Singapore & SEA focus** — covers major local and regional online retailers
- **Self-serve API keys** — instant registration at buywhere.ai/api-keys, no waitlist

## Installation

```bash
npx -y @buywhere/mcp-server
```

## Configuration (Claude Desktop)

```json
{
  "mcpServers": {
    "buywhere": {
      "command": "npx",
      "args": ["-y", "@buywhere/mcp-server"],
      "env": { "BUYWHERE_API_KEY": "your-key" }
    }
  }
}
```

## Resources

- GitHub: https://github.com/BuyWhere/buywhere-mcp
- NPM: https://npmjs.com/package/@buywhere/mcp-server
- API Keys: https://buywhere.ai/api-keys
