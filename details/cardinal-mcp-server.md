# Cardinal MCP Server

An MCP (Model Context Protocol) server for Cardinal that exposes AI-driven product backlog and product management workflows to compatible MCP clients.

## Overview
- **Type:** MCP Server
- **Category:** Project management / product management
- **Purpose:** Surface AI product backlog and product management workflows via the Model Context Protocol so they can be accessed from MCP-compatible chat or developer tools.
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible endpoint**
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) usable across any MCP client.
  - Authentication is handled during server addition/configuration in the client.

- **AI product backlog access**
  - Exposes Cardinal’s AI product backlog through the MCP interface.
  - Designed so AI agents and chat clients can retrieve and interact with product backlog data.

- **Product management workflows**
  - Surfaces product management workflows (e.g., backlog-related workflows) over MCP for use in AI tooling.

- **Client-agnostic integration**
  - Intended to work with multiple MCP-compatible chat clients and applications.
  - Setup instructions are provided per client type via documentation.

- **Configuration documentation**
  - Central Configuration page (linked from the app) that explains how to add and configure the server in different clients.

## Integration & Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your chosen MCP-compatible client.
- Authenticate within the client when prompted.
- Use the client’s MCP tooling to access Cardinal AI backlog and related workflows.

## Pricing
- Not specified in the provided content.