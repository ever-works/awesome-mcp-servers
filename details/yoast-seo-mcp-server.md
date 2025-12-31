# Yoast SEO MCP Server

MCP Server integration with Yoast SEO, enabling SEO analysis and optimization actions on WordPress sites via the MCP protocol.

---

## Overview

The **Yoast SEO MCP Server** exposes Yoast SEO capabilities through a standardized MCP (Model Context Protocol) server endpoint. It allows compatible clients (e.g., AI assistants or chat-based tools) to connect to Yoast SEO functionality for WordPress sites via a single static URL.

- **Type:** MCP server integration
- **Category:** Business & Commerce – MCP Servers
- **Primary use case:** SEO analysis and content optimization for WordPress websites through MCP-enabled clients
- **Provider / Platform:** Pipedream Connect

---

## Features

- **Static MCP Server Endpoint**  
  - Single MCP server URL usable by any compatible client:  
    `https://mcp.pipedream.net/v2`  
  - Centralized endpoint for connecting to Yoast SEO-related actions.

- **Client-Agnostic Integration**  
  - Designed to work with multiple chat or MCP-compatible clients.  
  - Authentication is performed when adding the server to each client/application.

- **Authentication at Client Setup**  
  - You authenticate to the MCP server during configuration in your application.  
  - The same URL can be reused across different tools, each with its own auth context.

- **Configuration Guidance**  
  - Documentation on adding the server to supported chat clients.  
  - Additional setup and configuration details available via a dedicated configuration page (linked from the product page).

- **Pipedream Connect Integration**  
  - Implemented and hosted via Pipedream Connect’s infrastructure.  
  - Integrates Yoast SEO capabilities into workflows that use MCP servers.

> Note: The page describes the MCP server endpoint and setup flow, but does not list specific SEO operations or methods. Those are implied to be Yoast SEO analysis and optimization actions available once connected.

---

## Usage

1. **Copy MCP Server URL**  
   Use the static endpoint in your MCP-compatible client:  
   `https://mcp.pipedream.net/v2`

2. **Add to Your Application**  
   - Open your chat client or MCP-enabled tool.
   - Add a new MCP server using the URL above.
   - Complete the authentication flow prompted by the client.

3. **Access Yoast SEO Actions**  
   - Once configured, use your client’s interface to invoke Yoast-related SEO analysis and optimization actions on your WordPress content.

---

## Pricing

The provided content does not include any pricing or plan information for the Yoast SEO MCP Server. Pricing details are not specified on the referenced page.