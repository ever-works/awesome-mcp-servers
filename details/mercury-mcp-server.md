# Mercury MCP Server

**Category:** Finance & Market Data MCP Servers  
**Brand:** Mercury  
**Source:** https://mcp.pipedream.com/app/mercury

## Overview
Mercury MCP Server is an MCP (Model Context Protocol) server endpoint that enables integration of Mercury banking functionality into MCP-based automation, tooling, and chat clients. It is provided via Pipedream Connect as a static, shared MCP server URL.

## Features
- **Static MCP server URL**  
  - Single shared endpoint for all clients:  
    `https://mcp.pipedream.net/v2`
  - URL is the same across different applications and chat clients.

- **Authentication handled per client**  
  - Authentication occurs when adding the server to your application or client.  
  - The static URL does not embed credentials.

- **MCP-based integration**  
  - Designed to be added as an MCP server within compatible chat clients and tools.  
  - Intended to expose Mercury banking-related capabilities into MCP-powered workflows and automations.

- **Client-agnostic usage**  
  - Can be used with multiple MCP-capable chat clients.  
  - Setup instructions are provided per client (via the host site’s "Select your chat client" flow).

- **Configuration documentation**  
  - Additional setup and configuration details available via a dedicated configuration page (`/configuration` on the host site).

- **Hosted by Pipedream**  
  - Operated and provided through Pipedream Connect infrastructure.

## Integration & Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your MCP-compatible chat client or application.  
- Complete authentication during the add/connect flow for that client.  
- Refer to the configuration page for client-specific instructions.

## Pricing
No pricing information is provided in the available content.
