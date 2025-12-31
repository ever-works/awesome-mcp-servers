# Lemon Squeezy MCP Server

## Overview
The Lemon Squeezy MCP Server is an integration that exposes Lemon Squeezy’s all‑in‑one SaaS business platform to MCP-compatible tools and chat clients. It allows applications to interact with Lemon Squeezy for managing payments, subscriptions, and related SaaS commerce operations through the MCP protocol.

## MCP Server URL
- Base MCP server URL (static for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is performed when adding the server to an MCP-compatible application.

## Features
- **Payments**
  - Process online payments for SaaS products.
  - Support for PayPal integration.
- **Subscriptions**
  - Handle recurring billing and subscription management for SaaS customers.
- **Global Tax Compliance**
  - Tools to support tax compliance across multiple regions.
- **Fraud Prevention**
  - Mechanisms to help detect or reduce fraudulent transactions.
- **Multi‑Currency Support**
  - Accept payments in multiple currencies.
- **Failed Payment Recovery**
  - Capabilities to address or recover failed payments.
- **MCP Integration**
  - Accessible as an MCP Server for use by MCP-compatible chat clients and tools.
  - Single static server URL usable across different clients.

## Integration & Configuration
- Add the server URL `https://mcp.pipedream.net/v2` to your MCP-compatible chat client or application.
- Client-specific setup is done within each chat client using that URL.
- Additional configuration details are available on the platform’s configuration page (referenced as the “Configuration page” in the source content).

## Pricing
- Not specified in the provided content.