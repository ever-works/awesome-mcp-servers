# LoopMessage MCP Server

iMessage API for two-way communication

## Overview
LoopMessage MCP Server is an MCP (Model Context Protocol) server that exposes an iMessage-based API, enabling two-way SMS/iMessage messaging for MCP-compatible tools, agents, and chat clients. It is hosted via Pipedream Connect and is accessible through a static MCP server URL.

- **Category:** Messaging MCP Servers  
- **Brand:** LoopMessage  
- **Use case:** Integrate iMessage/SMS-style two-way messaging into MCP-compatible applications and agents.

## Features
- **MCP-compatible messaging server**  
  - Implements an MCP Server interface for use with MCP-compatible tools, agents, and chat clients.

- **iMessage-focused API**  
  - Exposes an iMessage API suitable for two-way SMS/iMessage-style communication.

- **Two-way messaging support**  
  - Designed for bidirectional (send and receive) messaging flows between applications/agents and end users.

- **Static MCP server URL**  
  - Single, static endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - The same URL is used across different MCP clients.

- **Authentication at client setup**  
  - Authentication occurs when adding the server to your application or chat client (details provided in client/configuration docs).

- **Client-agnostic integration**  
  - Can be added to multiple MCP-compatible chat clients; each client follows its own setup instructions.

- **Configuration documentation**  
  - A dedicated configuration page (via Pipedream Connect) provides step-by-step integration instructions for supported clients.

## Integration & Setup
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup flow:**  
  1. Copy the MCP server URL.  
  2. Add the server to your MCP-compatible app or chat client.  
  3. Authenticate within that client according to its instructions.  
  4. Configure messaging behavior as described in the configuration documentation.

## Pricing
The provided content does not list any pricing or plans for LoopMessage MCP Server. Refer to the provider’s main site or app listing for current pricing details, if available.