# Wise MCP Server

**Category:** Finance & Market Data MCP Servers  
**Brand:** Wise (formerly TransferWise)

## Overview
The Wise MCP Server exposes Wise’s international money transfer and multi-currency account capabilities as MCP tools, allowing chat-based clients and other MCP-compatible applications to create and manage transfers, quotes, recipients, and balances via a single MCP endpoint.

## MCP Server URL
- **Base MCP Server URL:** `https://mcp.pipedream.net/v2`
- This is a static URL used by all MCP clients; authentication is performed when adding the server to your application.

## Features
- **Authentication & Account Connection**
  - Connect a Wise account via Pipedream.
  - Manage access from supported chat clients (e.g., ChatGPT / OpenAI) using MCP configuration.

- **Transfer Operations**
  - **Get Transfer**
    - Retrieve details of a specific Wise transfer.
  - **Create Transfer**
    - Create a new international money transfer.
  - **Fund Transfer**
    - Fund a created transfer through the Wise API.

- **Recipient Management**
  - **Get Recipient Account**
    - Retrieve details for a specific recipient account.
  - **Create Recipient Account**
    - Create a new recipient account to be used for future transfers.

- **Rates, Quotes & Pricing Calculation**
  - **Get Exchange Rates**
    - Fetch Wise exchange rates for supported currencies.
  - **Create Quote**
    - Generate a quote for a transfer, including rate and fee information for the specified currencies and amounts.

- **Balance Management**
  - **Get Balance**
    - Retrieve balances for Wise multi-currency accounts.

- **Client Integration**
  - Compatible with MCP-enabled chat clients, including ChatGPT (OpenAI).
  - Configuration instructions available via Pipedream’s MCP configuration page.

## Pricing
- No explicit pricing information for the Wise MCP Server or its usage is provided in the available content.

## Tags
- Payments  
- Banking  
- Currency
