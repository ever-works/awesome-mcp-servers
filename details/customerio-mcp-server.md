# Customer.io MCP Server

An MCP server that connects MCP-compatible clients (like ChatGPT) with Customer.io, enabling automated messaging and customer engagement workflows via Pipedream.

## Overview
- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Provider:** Pipedream
- **Platform integrated:** Customer.io (customer engagement & messaging)
- **MCP Endpoint:** `https://mcp.pipedream.net/v2` (static URL for all clients; authentication handled per client)

## Features

### MCP Server & Connectivity
- Static MCP server URL that works across all supported clients.
- Authentication handled when adding the server to your MCP-compatible application.
- Configuration guides available for specific chat clients (e.g., ChatGPT / OpenAI) via Pipedream.

### Available Tools (Actions)
The server exposes Customer.io actions as MCP tools:

1. **Send Event To**
   - Sends an event to Customer.io.
   - Integrates with Customer.io’s event tracking API.
   - Suitable for triggering workflows or campaigns based on custom events.

2. **Send Event To Customer.io**
   - Sends and tracks a customer event in Customer.io.
   - Used for recording user actions (e.g., sign-ups, purchases) to drive automated messaging.

3. **Create or Update Customer**
   - Creates a new customer record in Customer.io or updates an existing one.
   - Supports synchronizing user data from your MCP-compatible tools into Customer.io.

4. **Add Customers to Segment**
   - Adds people to a manual segment in Customer.io by segment ID.
   - Supports up to **1,000 customer IDs per request**.
   - Enables bulk inclusion of users into targeted segments for campaigns.

## Usage
- Connect your Customer.io account via Pipedream.
- Copy the MCP server URL `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible client (e.g., ChatGPT) and authenticate.
- Invoke tools to:
  - Track events
  - Create or update customers
  - Add customers to segments

## Pricing
- No explicit pricing information for the **Customer.io MCP Server** is provided in the available content.
- Any costs, if applicable, would depend on Pipedream and/or Customer.io plans (not specified in the source text).