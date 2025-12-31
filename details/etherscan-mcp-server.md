# Etherscan MCP Server

An MCP server that exposes human-readable Ethereum blockchain data (transactions, addresses, and other on-chain information) to MCP-compatible tools and chat clients.

- **Website / Source**: https://mcp.pipedream.com/app/ethereum
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Category**: Blockchain & Crypto MCP Servers
- **Brand**: Etherscan
- **Tags**: blockchain, ethereum, api-integration

## Features

- **Human-readable Ethereum data access**  
  - Provides Ethereum blockchain data in a format suitable for non-technical and tooling-oriented use.  
  - Intended for querying on-chain information like transactions and addresses.

- **MCP-compatible server**  
  - Exposes a static MCP server URL (`https://mcp.pipedream.net/v2`) usable across different MCP clients.  
  - Designed to be added as a server within MCP-enabled chat applications or tools.

- **Client-agnostic configuration**  
  - Single static URL works for “every client”; configuration is done on the client side.  
  - Authentication is handled when adding the server to each specific application.

- **Pipedream Connect integration**  
  - Hosted and powered by Pipedream Connect, enabling use alongside other Pipedream-based integrations and workflows.

## Authentication

- Authentication is required and is performed during the process of adding the server to your MCP-enabled application or chat client (details are client-specific and handled at configuration time).

## Usage

1. Use the static MCP server URL: `https://mcp.pipedream.net/v2`.  
2. Add this URL as an MCP server in your chosen MCP-compatible client.  
3. Complete authentication as prompted by your client.  
4. Query Ethereum blockchain data (e.g., transactions, addresses, on-chain information) via the client’s MCP tooling interface.

## Pricing

- Not specified in the provided content.

## Additional Links

- Configuration details: `/configuration` (on the Pipedream site)  
- Pipedream Connect: https://pipedream.com/connect  
- Terms: https://pipedream.com/terms  
- Privacy Policy: https://pipedream.com/privacy