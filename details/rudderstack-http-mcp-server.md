# RudderStack HTTP MCP Server

## Overview
RudderStack HTTP MCP Server exposes the RudderStack HTTP API as a Model Context Protocol (MCP) server. It allows MCP-compatible clients to send customer event data from various sources into RudderStack, which then routes that data to configured destinations in your customer data platform stack.

- **Name:** RudderStack HTTP MCP Server  
- **Category:** Data Access & Integration – MCP Servers  
- **Brand:** RudderStack  
- **Source URL:** https://mcp.pipedream.com/app/rudderstack  
- **Tags:** `cdp`, `event-data`, `api-integration`

## Features
- **RudderStack HTTP API access via MCP**  
  - Exposes the RudderStack HTTP API through an MCP server interface.  
  - Enables MCP clients (e.g., AI/chat applications that support MCP) to send events programmatically.

- **Customer event data ingestion**  
  - Accepts event data from multiple sources via the HTTP endpoint.  
  - Supports sending customer behavior and tracking events into RudderStack’s customer data platform.

- **Routing to configured destinations**  
  - Forwards ingested event data from RudderStack to your configured downstream tools and destinations (e.g., analytics, warehouses, marketing tools) according to your RudderStack setup.

- **Static MCP server URL**  
  - Uses a single, static endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - The same URL is used across clients, simplifying configuration.

- **Per-client authentication**  
  - Authentication is performed when adding the server to each application or MCP-compatible client (credentials and method configured within the client).

- **Client-agnostic integration**  
  - Designed to work with any MCP-capable chat or application client.  
  - Can be added to supported chat clients to enable event sending from within those environments.

- **Configuration documentation**  
  - Additional setup and configuration details are available through a dedicated configuration page linked from the app.

## Pricing
No pricing information is provided in the available content. Use the source URL or vendor site for current pricing details.