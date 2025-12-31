# DigitalRiver MCP Server

An MCP-compatible server that exposes DigitalRiver’s ecommerce, payments, and global selling capabilities to AI agents and tools.

## Overview
- **Type:** MCP server (integration connector)
- **Category:** Business & Commerce MCP Servers
- **Provider / Brand:** DigitalRiver (via Pipedream)
- **Purpose:** Enable AI agents and MCP-compatible clients (e.g., ChatGPT) to interact programmatically with DigitalRiver’s commerce services.
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- **Static MCP server endpoint** usable for all DigitalRiver clients:
  - `https://mcp.pipedream.net/v2`
- **Authentication at app level:** You authenticate your DigitalRiver account when adding the server to your application or chat client.
- **Works with multiple chat clients:** Configuration guidance is provided for ChatGPT (OpenAI), with additional instructions available on the general MCP configuration page.

### DigitalRiver Account Configuration
- **Account connection:**
  - Connect your DigitalRiver account via the Pipedream MCP interface.
  - Select and manage your DigitalRiver client configuration after sign-in.

### Available Tools (Actions)
The MCP server currently exposes three main actions as tools:

1. **Update Customer Information**
   - Action: `Update Customer Information`
   - Function: Updates the information for an existing customer in DigitalRiver.
   - Usage: Maintain accurate and current customer profiles (e.g., contact details, profile updates) directly via MCP.
   - Documentation: Linked in source app (GitHub action file).

2. **Create a Product**
   - Action: `Create a Product`
   - Function: Creates a new product on the DigitalRiver platform.
   - Usage: Add new items to your catalog (e.g., digital or physical products) programmatically through MCP.
   - Documentation: Linked in source app (GitHub action file).

3. **Cancel Order**
   - Action: `Cancel Order`
   - Function: Cancels an existing order in DigitalRiver.
   - Usage: Manage order lifecycle and handle cancellations directly from AI agents or tools.
   - Documentation: Linked in source app (GitHub action file).

### Commerce & Global Selling Context
- Surfaces DigitalRiver’s core capabilities (as described):
  - Ecommerce operations
  - Payments
  - Global selling / cross-border commerce
- Intended to support global expansion and operations by letting AI agents interact with DigitalRiver’s commerce APIs via MCP.

## Pricing
No pricing information or plan details are provided in the available content for the DigitalRiver MCP Server. Users should refer to Pipedream and/or DigitalRiver directly for current pricing or usage terms.

## Links
- **App page:** https://mcp.pipedream.com/app/digitalriver
- **MCP configuration guide:** https://mcp.pipedream.com/configuration
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Update Customer Information action:** https://github.com/PipedreamHQ/pipedream/blob/master/components/digitalriver/actions/update-customer-information/update-customer-information.mjs
- **Create Product action:** https://github.com/PipedreamHQ/pipedream/blob/master/components/digitalriver/actions/create-product/create-product.mjs
- **Cancel Order action:** https://github.com/PipedreamHQ/pipedream/blob/master/components/digitalriver/actions/cancel-order/cancel-order.mjs
