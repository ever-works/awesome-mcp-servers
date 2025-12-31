# Brillium MCP Server

Brillium MCP Server integrates Brillium’s assessment and talent screening software with MCP-compatible chat clients via a static MCP endpoint hosted by Pipedream.

## Basic Info

- **Name:** Brillium MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Use Case:** Assessment delivery, talent screening, and HR-related evaluation workflows via MCP-compatible applications  
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features

- **MCP-compatible server**  
  - Exposes Brillium assessment and talent screening capabilities as an MCP Server.  
  - Can be connected to MCP-enabled chat or agent clients.

- **Static, reusable URL**  
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.  
  - The same URL works for all clients; configuration is simplified across environments.

- **Client-side authentication**  
  - Authentication is performed when you add the server to your MCP-compatible application.  
  - The URL is not tied to a specific user or tenant; security is handled at connection time.

- **Hosted by Pipedream Connect**  
  - Infrastructure and connectivity are powered by Pipedream Connect.  
  - Centralized configuration patterns documented via the Pipedream configuration page.

- **Multi-client support**  
  - Intended to be added to various chat or agent clients that support MCP.  
  - Works as a shared integration layer between Brillium and multiple front-ends.

## Configuration

- **Server URL:**  
  Add `https://mcp.pipedream.net/v2` as an MCP server in your chat/agent client.

- **Client selection:**  
  Use your client’s MCP configuration interface ("Add server" or similar) and supply the URL above.

- **Further configuration details:**  
  Additional setup instructions are available on the Pipedream MCP Configuration page referenced by the app.

## Pricing

- Not specified in the provided content.

## Tags

- Assessment  
- Talent  
- HR