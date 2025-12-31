# Blockchain Exchange MCP Server

## Overview
The Blockchain Exchange MCP Server provides Model Context Protocol (MCP) access to Blockchain.com Exchange functionality, allowing applications and AI agents to interact programmatically with a fast crypto exchange via a standardized MCP endpoint.

- **Type:** MCP server / integration
- **Category:** Blockchain & Crypto MCP Servers
- **Provider / Brand:** blockchaincom
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server**
  - Exposes Blockchain.com Exchange capabilities through the Model Context Protocol.
  - Uses a static MCP server URL (`https://mcp.pipedream.net/v2`) that works across supported clients.

- **AI-driven exchange interaction**
  - Designed for AI agents and chat-based clients to interact with Blockchain.com Exchange.
  - Supports integration into various MCP-enabled chat or agent applications.

- **Client-agnostic configuration**
  - Single endpoint usable by multiple MCP clients.
  - Authentication occurs when adding the server in your application or client.

- **Account-based operations**
  - Connects to a user’s Blockchain.com Exchange account.
  - Performs an account check during setup (e.g., "Checking your account…").

- **Tooling integration**
  - Provides MCP “tools” (actions/endpoints) surfaced via supporting clients.
  - Tools are dynamically loaded in compatible environments ("Loading actions…", "Loading available tools…").

- **Configuration guidance**
  - Workflow to copy the MCP URL and add the server to different chat clients.
  - Additional configuration documentation available via the full configuration page on Pipedream.

## Usage
1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add the MCP server to your MCP-compatible app or chat client.
3. Authenticate with your Blockchain.com Exchange account when prompted.
4. Use the exposed tools to interact with exchange functionality through your client.

## Pricing
The provided content does not include any pricing or plan information for the Blockchain Exchange MCP Server.