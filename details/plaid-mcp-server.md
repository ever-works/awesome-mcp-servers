# Plaid MCP Server

An MCP server integration for Plaid that lets MCP-compatible agents securely connect to and interact with users’ bank account data.

- **Category:** Finance & Market Data MCP Servers  
- **Tags:** banking, API integration, transactions  
- **Provider:** Pipedream  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

---

## Overview

Plaid MCP Server exposes Plaid banking capabilities as MCP tools so chat-based or agent-based applications can:
- Connect to users’ bank accounts via Plaid
- Retrieve transaction and account data
- Work with sandbox and production Plaid flows

You authenticate when adding this static MCP server URL to your application or chat client.

---

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.
- Designed to be added as a server in MCP-compatible chat/agent applications.
- Central configuration via a separate configuration page (not detailed here).

### Available Tools (Actions)

1. **Get Transactions**
   - Retrieves user-authorized transaction data.
   - Supports specifying a date range.
   - Uses Plaid’s transaction endpoints via MCP.

2. **Get Real-Time Balance**
   - Fetches real-time balance for each of an Item’s accounts.
   - Intended for up-to-date account balance checks.

3. **Create User**
   - Creates a user ID and token.
   - Usable with:
     - Plaid Check
     - Plaid Income
     - Plaid Multi-Item Link flow

4. **Create Sandbox Public Token**
   - Generates a valid `public_token` for Plaid’s sandbox.
   - Works with arbitrary institution IDs.
   - Supports specifying initial products.
   - Uses test credentials for development and testing.

5. **Create Access Token**
   - Exchanges a Plaid Link `public_token` for an API `access_token`.
   - Enables authenticated server-side calls to Plaid APIs via MCP.

---

## Use Cases

- Building MCP-enabled agents that can:
  - Read user bank transactions over a chosen date range.
  - Check up-to-date balances across linked accounts.
  - Use sandbox flows to test Plaid integrations safely.
  - Manage Plaid user identities and tokens for various Plaid products.

---

## Pricing

The provided content does not specify any pricing or plans for the Plaid MCP Server. Refer to the source or provider for current pricing details.