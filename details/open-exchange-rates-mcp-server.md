# Open Exchange Rates MCP Server

## Overview
The Open Exchange Rates MCP Server provides consistent, reliable exchange rate data and currency conversion capabilities to MCP-compatible clients and applications. It connects to an Open Exchange Rates account and exposes tools that can be used from supported chat or MCP clients.

- **Category:** Finance / Market Data MCP Servers  
- **Provider / Brand:** Open Exchange Rates (via Pipedream)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Exchange rate data access**  
  - Retrieve currency exchange rate data suitable for business and application use.

- **Currency conversion**  
  - Perform currency conversions using Open Exchange Rates data.

- **MCP-compatible server**  
  - Exposes Open Exchange Rates capabilities as an MCP server for use with MCP clients and chat-based tools.

- **Static server endpoint**  
  - Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for every supported client.

- **Account-based configuration**  
  - Connects to an Open Exchange Rates account via Pipedream configuration.  
  - Authentication occurs when adding the server to your application.

- **Client-agnostic usage**  
  - Can be added to different chat clients / MCP clients; instructions are provided per client type (via the configuration page).

- **Tool exposure**  
  - Provides “available tools” / actions (loaded dynamically) that MCP clients can call to work with exchange rates and conversions.

## Configuration
- Connect an Open Exchange Rates account in Pipedream.  
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server to your MCP-compatible app or chat client following client-specific setup instructions (linked from the configuration page).

## Pricing
- Not specified in the provided content.