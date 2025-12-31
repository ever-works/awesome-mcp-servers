# Codat MCP Server

**Category:** Finance & Market Data · MCP Servers  
**Brand:** Codat  
**Slug:** `codat-mcp-server`

## Overview
Codat MCP Server is an MCP (Model Context Protocol) server that exposes Codat’s business financial data APIs to applications such as AI clients and chat-based tools. It provides access to financial data from the systems used by business customers, enabling banks and fintechs to connect to that data through a unified interface.

MCP endpoint:
```text
https://mcp.pipedream.net/v2
```

## Features
- **MCP Server for Codat**
  - Implements the Model Context Protocol for accessing Codat’s APIs.
  - Designed to be added directly as a server in compatible chat or AI clients.

- **Access to Business Financial Data**
  - Connects to financial systems used by business customers.
  - Surfaces business financial data exposed by Codat’s APIs (e.g., the kinds of systems banks and fintechs integrate with).

- **Unified API Access**
  - Provides a single MCP endpoint (`https://mcp.pipedream.net/v2`) that works for all clients.
  - Centralizes access to Codat’s business data integrations through that endpoint.

- **Static Server URL**
  - Uses a static MCP server URL valid for every client.
  - Simplifies configuration because the same URL is reused across environments and applications.

- **Client-Agnostic Integration**
  - Can be added to different chat clients or MCP-compatible tools.
  - Works within applications that support MCP without client-specific URL changes.

- **Authentication at Client Setup**
  - Authentication occurs when adding the server to an application or chat client.
  - Allows the same URL to be reused while credentials remain client-specific.

- **Configuration Documentation (External)**
  - A separate configuration page is referenced for setup details (e.g., how to register and configure the server in various clients).

## Pricing
No pricing information is provided in the available content.

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Protocol:** Model Context Protocol (MCP)  
- **Integration Host:** Pipedream Connect
