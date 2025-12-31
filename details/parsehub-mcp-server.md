# ParseHub MCP Server

An MCP-compatible server that exposes ParseHub's web scraping capabilities via a standard MCP endpoint for use in compatible chat or agent clients.

---

## Overview
- **Type:** MCP server for web scraping and structured data extraction
- **Provider:** ParseHub (via Pipedream Connect)
- **Category:** Content extraction & summarization MCP servers
- **Endpoint URL:** `https://mcp.pipedream.net/v2`

This server lets MCP-compatible clients use ParseHub’s scraping tools to extract structured data from websites.

---

## Features
- **MCP-compatible server**
  - Exposes ParseHub functionality as tools accessible through any MCP-enabled client.
  - Uses a single static base URL (`https://mcp.pipedream.net/v2`) for all supported clients.

- **Web scraping capabilities**
  - Connects to ParseHub, which is designed for powerful web scraping and data extraction from websites.
  - Suitable for structured data extraction workflows within chat or agent environments.

- **Static server URL**
  - One URL works across clients; no per-client endpoint changes required.
  - Simplifies configuration and reuse across multiple MCP-compatible tools or apps.

- **Client-agnostic integration**
  - Can be added to different chat clients that support MCP.
  - Configuration is handled on the client side, with authentication during server addition.

- **Authentication at connection time**
  - Users authenticate when adding the MCP server to their application (exact auth method handled in client/configuration, not hardcoded in the URL).

- **Configuration guidance available**
  - A dedicated configuration page (referenced as “Configuration page”) describes how to add and configure the server in supported clients.

---

## Integration & Usage
- **Server URL to use in clients:**
  - `https://mcp.pipedream.net/v2`
- **Setup flow (high level):**
  - Add the above URL as an MCP server in your compatible chat / agent client.
  - Authenticate when prompted by the client.
  - Access the exposed scraping and data extraction tools from within the client.

---

## Pricing
The provided content does not include any pricing or plan information for the ParseHub MCP Server.

---

## Links
- **MCP Server page:** https://mcp.pipedream.com/app/parsehub
- **Pipedream Connect:** https://pipedream.com/connect
- **Terms:** https://pipedream.com/terms
- **Privacy Policy:** https://pipedream.com/privacy