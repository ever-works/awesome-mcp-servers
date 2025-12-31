# Ghost Admin API MCP Server

## Overview
The Ghost Admin API MCP Server is an integration for the Ghost.org Admin API, enabling Model Context Protocol (MCP) clients and tools to manage content, settings, and administrative operations on the Ghost publishing platform via a standardized MCP server endpoint.

- **Name:** Ghost Admin API MCP Server (Ghost.org Admin API MCP Server)
- **Category:** Content Management MCP Servers
- **Use cases:** Managing Ghost blog content, automating publishing workflows, adjusting site settings, and performing admin operations through MCP-compatible chat or agent clients.
- **MCP Server URL:** `https://mcp.pipedream.net/v2` (static URL used across clients; authentication is handled when adding the server to an application)

## Features
- **MCP Server integration for Ghost Admin API**
  - Connects Ghost’s Admin API to MCP-compatible clients.
  - Provides a standardized interface for tools that support MCP.

- **Content management capabilities** (via Ghost Admin API)
  - Create, read, update, and delete posts and pages.
  - Manage blog content programmatically from within MCP-aware tools.

- **Settings and configuration management**
  - Access and modify site settings exposed by the Ghost Admin API.
  - Support for administrative configuration operations through the MCP layer.

- **Administrative operations**
  - Perform admin-level tasks supported by Ghost’s Admin API (e.g., managing tags, authors, and other administrative resources, subject to the API’s capabilities and permissions).

- **Static, reusable MCP endpoint**
  - Single static URL (`https://mcp.pipedream.net/v2`) for all supported clients.
  - Authentication handled when the server is added to the application, rather than per-URL customization.

- **Client-agnostic setup**
  - Designed to be added to various MCP-compatible chat or agent clients.
  - Works the same way across supported clients, with configuration handled on the client side.

## Configuration & Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible application or chat client.
- Authenticate with Ghost Admin API credentials when prompted by the client.
- Optionally refer to the platform’s configuration documentation ("Configuration" page) for client-specific setup instructions.

## Pricing
- Not specified in the provided content.