# Kucoin Futures MCP Server

An MCP server that connects to KuCoin Futures, allowing MCP-based tools and chat clients to interact with KuCoin’s cryptocurrency futures exchange.

## Overview
- **Type:** MCP server / integration
- **Category:** Blockchain & Crypto MCP Servers
- **Provider / Brand:** KuCoin (via Pipedream)
- **Use Case:** Enable tools and chat clients to access KuCoin Futures exchange functionality through a standardized MCP endpoint.

## Features
- **KuCoin Futures integration**
  - Connects to KuCoin’s cryptocurrency futures exchange services.
  - Designed for MCP-based tools to interact with KuCoin Futures via a unified server.

- **Static MCP server URL**
  - Uses a single static URL for all clients: `https://mcp.pipedream.net/v2`.
  - Same endpoint works across supported MCP/chat clients.

- **Account-based authentication**
  - Authentication occurs when adding the server to your application, after connecting your KuCoin account.

- **Client-agnostic setup**
  - Can be added to different chat or MCP clients.
  - Configuration guidance is available per client via the Pipedream configuration flow.

- **Configuration support page**
  - A dedicated configuration page (via Pipedream) describes how to add and use the server within applications.

- **Tool exposure (MCP tools)**
  - Exposes KuCoin Futures functionality as “tools”/actions that can be loaded and invoked by MCP-compatible clients (exact tools not listed in the provided content).

## Usage
1. Connect your KuCoin account in the Pipedream Kucoin Futures MCP Server page.
2. Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.
3. Add this server URL to your MCP-compatible app or chat client.
4. Follow the client-specific setup instructions from the configuration page.

## Pricing
- Not specified in the provided content.

## Links
- **Source / App page:** https://mcp.pipedream.com/app/kucoin_futures
- **Configuration page:** Referenced “Configuration page” on Pipedream (exact URL not given in content).