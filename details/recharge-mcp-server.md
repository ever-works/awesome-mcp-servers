# ReCharge MCP Server

**Website:** https://mcp.pipedream.com/app/recharge  
**Category:** Business & Commerce – MCP Servers  
**Provider / Brand:** Pipedream  
**Protocol:** Model Context Protocol (MCP)

## Overview
ReCharge MCP Server is a Pipedream-hosted Model Context Protocol server that exposes ReCharge’s ecommerce subscription and recurring payments functionality to LLM agents and MCP-compatible clients. It enables applications and chat-based agents to manage ecommerce subscriptions and related customer data via standardized MCP tools.

## Features
- **Static MCP Server Endpoint**  
  - Single MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to your MCP-compatible application.

- **LLM / Chat Client Integration**  
  - Can be added as a server to supported chat clients (e.g., ChatGPT via OpenAI).  
  - Configuration guidance available via a dedicated configuration page.

- **ReCharge Subscription & Payments Operations (Tools)**  
  Exposes ReCharge ecommerce subscription and recurring payments capabilities as MCP tools/actions:
  - **Create Customer**  
    - Create a new customer in ReCharge.
  - **Update Customer**  
    - Update an existing customer’s details.
  - **Create Subscription**  
    - Create a new subscription so a customer can subscribe to a product.
  - **Cancel Subscription**  
    - Cancel an existing subscription.

- **Ecommerce Focus**  
  - Designed for subscription and recurring payments workflows in ecommerce contexts.

## Usage
- Connect a ReCharge account through Pipedream’s interface.  
- Add the MCP server URL to an MCP-compatible client (such as ChatGPT) and authenticate.  
- Use the exposed tools to programmatically manage customers and subscriptions from within LLM agents or chat interfaces.

## Pricing
No pricing information is provided on the referenced page for the ReCharge MCP Server. Pricing, if any, would need to be obtained from Pipedream or ReCharge directly.