# Kartra MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Kartra  
**Source:** https://mcp.pipedream.com/app/kartra

## Overview
Kartra MCP Server is an MCP (Model Context Protocol) server that provides programmatic access to Kartra’s all‑in‑one online business, marketing, and sales platform. It allows applications and chat clients to interact with Kartra’s tools via a standardized MCP endpoint.

## Features
- **MCP-based access to Kartra**: Exposes Kartra’s online business, marketing, and sales capabilities through the MCP protocol.
- **Static MCP endpoint**: Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all clients.
- **Authentication at app level**: Authentication is handled when adding the server to your application, rather than requiring different URLs per client.
- **Multi-client support**: Designed to be added to various chat clients or MCP-compatible applications.
- **Configuration guidance**: Provides configuration instructions (via the linked configuration page) for connecting accounts and selecting a client.
- **Tool discovery**: Supports loading and listing available tools/actions exposed by the Kartra MCP Server (e.g., “Loading actions…”, “Loading available tools…” indicates dynamic tool enumeration).

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Integration host:** Pipedream platform
- **Usage model:** Add as an MCP server in compatible clients, then authenticate and configure your Kartra account.

## Use Cases
- Integrating Kartra marketing and sales operations into chat-based assistants.
- Automating or orchestrating Kartra workflows via MCP-compatible tools.
- Centralizing access to Kartra’s online business platform within MCP-enabled environments.

## Pricing
Pricing information is not provided in the available content. Refer to the source page or the Kartra/Pipedream documentation for current pricing details.