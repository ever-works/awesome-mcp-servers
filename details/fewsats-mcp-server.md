# Fewsats MCP Server

**Category:** Blockchain / Crypto MCP Servers  
**Brand:** Fewsats  
**Source:** <https://github.com/Fewsats/fewsats-mcp>

## Overview

Fewsats MCP Server is a Model Context Protocol (MCP) server that integrates with the [Fewsats](https://fewsats.com) payment platform, enabling AI agents to perform secure purchases and interact with a crypto-enabled wallet and payment methods.

## Features

### MCP Integration
- Implements an MCP server compatible with AI agents.  
- Exposes tools for querying wallet information and executing payments through Fewsats.

### Tools / Capabilities

1. **`balance` tool**
   - Retrieves the balance of the user’s wallet.
   - **Input:** None.
   - **Output:** Current wallet balance information.

2. **`payment_methods` tool**
   - Retrieves the user’s available payment methods.
   - **Input:** None.
   - **Output:** List of available payment methods.

3. **`pay_offer` tool**
   - Pays an offer with the specified ID from `l402_offers`.
   - **Inputs:**
     - `offer_id` (string): Identifier for the offer to pay.
     - `l402_offer` (object) including:
       - `offers`: Array of offer objects (each with ID, amount, currency, description, title).
       - `payment_context_token`: String token representing the payment context.
       - `payment_request_url`: URL to initiate or process the payment request.
       - `version`: API version string.
   - **Output:** Payment status response.

### Secure Purchasing via Fewsats
- Uses the Fewsats payment platform to allow AI agents to “purchase anything” in a secure manner (as supported by Fewsats and the offer/payment API).
- Designed for programmatic, agent-driven payment flows.

## Pricing

No pricing information is provided in the available content (the repository appears to be open-source; terms or usage pricing, if any, are not specified in the snippet).