# Brex MCP Server (Staging)

**Category:** Finance / Market Data MCP Servers  
**Brand:** Brex  
**Environment:** Staging / Test

Staging MCP server for Brex that exposes payments, deposits, and card operations via the Model Context Protocol (MCP). Designed for testing and integration in a non‑production environment.

---

## Features

- **Model Context Protocol (MCP) server**  
  - Exposes Brex operations as MCP tools/actions for use in MCP-compatible clients.

- **Staging / test environment**  
  - Intended for development and testing, not live production data.

- **Payments operations**  
  - Access to payment-related functionality (test environment).

- **Deposits operations**  
  - Access to deposit-related functionality (test environment).

- **Card operations**  
  - Access to card-related actions (e.g., card-related transactions and controls in staging).

- **Static MCP server URL**  
  - Single endpoint for all clients: `https://mcp.pipedream.net/v2`  
  - Same URL used across different chat or MCP clients; authentication handled when adding the server to your application.

- **Client-agnostic integration**  
  - Can be added to various chat or MCP-compatible applications; workflow guided per client.

- **Configuration via Pipedream**  
  - Configure the server, connect your account, and select the appropriate client within Pipedream’s UI.

---

## Integration & Setup

- Connect a Brex staging account through Pipedream.  
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server to your MCP-compatible app or chat client and authenticate there.  
- Additional configuration details are available on the Pipedream configuration page for this server.

---

## Pricing

- No pricing information is provided in the available content.