# Ghost Content API MCP Server

## Overview
The Ghost Content API MCP Server provides Model Context Protocol (MCP) access to published content from Ghost.org, the open‑source publishing platform. It is intended for use in AI and automation workflows that need to read Ghost content programmatically via an MCP-compatible client.

- **Type:** MCP server / integration
- **Platform:** Ghost.org Content API
- **Category:** Content management MCP server
- **Use cases:** Blogs, publishing workflows, content management, AI assistants, automation tools

## Features
- **MCP-based access to Ghost content**  
  - Exposes the Ghost.org Content API through the Model Context Protocol.  
  - Designed for use with MCP-compatible chat or AI clients.

- **Works with published content from Ghost**  
  - Integrates specifically with the Ghost open‑source publishing platform’s Content API.  
  - Suitable for retrieving and using published blog and site content in downstream tools.

- **Static MCP server endpoint**  
  - Single MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - The same endpoint is used regardless of client; authentication is handled when adding the server to your application.

- **Client-agnostic configuration**  
  - Can be added to multiple MCP-compatible chat or app clients.  
  - Setup is performed by copying the server URL and configuring it inside your chosen client.

- **Pipedream-hosted integration**  
  - Hosted and provided via Pipedream’s infrastructure.  
  - Tied into Pipedream’s configuration flows for connecting accounts and managing integrations.

- **Automation and AI workflow readiness**  
  - Designed for use in AI agents, chat clients, and automation workflows that rely on MCP servers as content sources.

> Note: The page references “Available tools / Loading actions…”, but no specific tools or actions are listed in the provided content.

## Configuration
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible app or chat client.
- Authenticate with your Ghost.org account and configure the connection via Pipedream as prompted by your client.

## Pricing
Pricing information is not provided in the available content.