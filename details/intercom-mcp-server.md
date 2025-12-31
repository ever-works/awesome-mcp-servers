# Intercom MCP Server

**Website:** https://www.intercom.com/  
**MCP Listing:** https://www.pulsemcp.com/servers/intercom  
**Category:** Messaging MCP Servers  
**Brand:** Intercom  
**Slug:** `intercom-mcp-server`  
**Release Date:** May 1, 2025  
**Estimated Visitors (All Time):** 16.3k (1k this week)  
**Popularity Rank:** #755 overall (#369 this week)

## Overview
The Intercom MCP Server exposes Intercom’s customer support and messaging capabilities to MCP-based agents via OAuth 2.1. It enables AI systems to securely access Intercom customer conversation data, user profiles, and tickets in real time for analysis, troubleshooting, and decision-making.

## Features
- **Intercom Data Access for AI Agents**  
  - Securely exposes Intercom customer conversation data.  
  - Provides access to user profiles.  
  - Provides access to support tickets.  
  - Enables real-time retrieval of Intercom data for pattern identification, issue troubleshooting, and business insights.

- **MCP Integration**  
  - Implements an MCP-compatible remote server endpoint for use by MCP clients and agents.  
  - Official `server.json` definition available, including installation, configuration, and usage guidelines.  
  - MCP identifier: `com.pulsemcp.mirror/intercom`.

- **Authentication**  
  - Uses OAuth-based authentication (OAuth flow initiated when connecting).  
  - No manual API key setup required in the MCP client.

- **Transport**  
  - Uses Server-Sent Events (SSE) transport for streaming interactions (the original, now-deprecated SSE version in MCP).  
  - Compatible with MCP clients that still support SSE-based servers.

- **Ecosystem & Metadata**  
  - Tracked estimated visitors and popularity ranking across the MCP ecosystem.  
  - Managed `server.json` temporarily by PulseMCP until the maintainer publishes to the official MCP registry.

## Technical Details
- **Remote Endpoint URL Pattern**  
  - Base URL: `https://mcp.intercom.com/...`  
  - This is the URL to use in MCP client configuration for the remote endpoint.

- **Server Definition**  
  - `server.json` file provided in a standardized, official format defined by the MCP registry.  
  - Includes installation instructions, configuration options, and usage guidelines (refer to the listing’s `server.json` link).

## Authentication
- **Method:** OAuth 2.x (initiated on connection from MCP client).  
- **Implication:** Users authenticate through an OAuth flow rather than supplying API keys directly.

## Transport
- **Protocol:** Server-Sent Events (SSE) for MCP communication.  
- **Status:** SSE is noted as deprecated in favor of Streamable HTTP in newer MCP versions but still supported by this server.

## Pricing
- **Free Trial:** Available. The service or remote server offers a free trial period allowing limited-time free usage.  
- No additional pricing tiers or paid plan details are provided in the source content.

## Related MCP Servers (Ecosystem)
*(Not part of the Intercom MCP Server feature set, but listed as related options in the ecosystem)*
- Intercom (community) – filtered access to conversations and chats for analysis.  
- WeCom – WeChat Work bot integration.  
- Iaptic – e-commerce customer and transaction data.  
- Dify AI – chat completion API integration.  
- Intercom Support Tickets – access and analysis of Intercom support tickets.  
- Frontapp – customer communication platform integration.  
- Prem AI – chat completions and RAG tools.  
- Gong – call-related data integration.