# EasyPost MCP Server

## Overview
The EasyPost MCP Server exposes the EasyPost Shipping API to MCP-compatible clients, enabling eCommerce and logistics workflows such as shipping label generation and package tracking through a unified MCP endpoint.

- **Name:** EasyPost MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Tags:** shipping, logistics, API  
- **Provider / Brand:** EasyPost (via Pipedream Connect)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible shipping API access**  
  - Provides an MCP Server interface over EasyPost’s shipping capabilities.  
  - Usable from any MCP client via the shared endpoint.

- **Logistics and eCommerce workflows**  
  - Supports logistics operations typically powered by EasyPost, such as shipping label creation and shipment tracking (as described in the item metadata).  
  - Designed for eCommerce and logistics use cases.

- **Static, reusable server URL**  
  - Uses a single static MCP URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - No per-client URL changes required.

- **Client-agnostic integration**  
  - Intended to be added to multiple MCP-compatible chat or agent clients.  
  - Configuration is handled on the client side, using the provided URL.

- **Authentication handled on add**  
  - Authentication occurs when the server is added to a client application (specific auth details are handled in the client / configuration flow).

- **Configuration documentation available**  
  - A dedicated configuration page is referenced for detailed setup instructions.

## Pricing
Pricing information is not provided in the available content.

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Integration Platform:** Pipedream Connect  
- **Intended Use:** Accessing EasyPost’s shipping and logistics functionality through the Model Context Protocol (MCP).