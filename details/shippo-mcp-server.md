# Shippo MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** Pipedream  
**Slug:** `shippo-mcp-server`

## Overview
Shippo MCP Server is a Model Context Protocol server hosted on Pipedream that connects Shippo’s ecommerce shipping tools and carrier integrations to MCP-compatible agents and workflows. It lets applications and AI agents interact with Shippo’s shipping capabilities via a standardized MCP endpoint.

## MCP Server URL
- Static MCP endpoint for all clients:  
  `https://mcp.pipedream.net/v2`  
- Authentication is performed when adding the server to your MCP-compatible application or client.

## Features
- **MCP-compatible server**: Exposes Shippo functionality through the Model Context Protocol, enabling integration with MCP-aware chat clients, agents, and workflows.
- **Ecommerce shipping integration**: Connects to Shippo’s ecommerce shipping tools for label generation, rate shopping, and carrier management (via Shippo’s APIs, accessed through MCP).
- **Carrier integrations**: Provides access to Shippo’s multi-carrier connections so MCP agents can work with multiple shipping providers through a single interface.
- **Workflow automation ready**: Designed to be used inside MCP-based workflows and automations, allowing AI agents or orchestrators to trigger and manage shipping-related operations.
- **Static server URL**: Uses a single, static URL (`https://mcp.pipedream.net/v2`) that works across clients, simplifying configuration and reuse.
- **Client-agnostic**: Can be added to any MCP-compatible chat client or application; authentication is handled per client during setup.
- **Pipedream-hosted**: Runs on Pipedream’s infrastructure, benefitting from its managed MCP hosting environment.

## Integration & Usage
- Add the server URL `https://mcp.pipedream.net/v2` to your MCP-compatible app or chat client.
- Authenticate during the add/connect flow in your chosen client (details depend on the client implementation).
- Use within agents or workflows that support MCP to perform shipping-related tasks through Shippo.

## Pricing
- No pricing information is provided in the available content.