# Daily MCP Server

WebRTC video and audio APIs for developers, exposed via an MCP (Model Context Protocol) server so you can add live video and audio experiences into applications and workflows.

## Overview
- **Type:** MCP server integration
- **Provider:** Daily (via Pipedream Connect)
- **Category:** Messaging MCP servers
- **Use cases:** Embed live video/audio, build real-time communication features, integrate WebRTC capabilities into chat or other tools.

## Features
- **WebRTC-based video and audio APIs**
  - Access Daily’s WebRTC capabilities through the MCP protocol.
  - Enable live video and audio experiences within products and automated workflows.

- **Static MCP server endpoint**
  - Single shared endpoint for all clients:
    - `https://mcp.pipedream.net/v2`
  - Same URL can be reused across different MCP-compatible clients.

- **Client-agnostic integration**
  - Designed to be added to multiple chat or agent clients.
  - Configuration is handled at the client side while using the same MCP URL.

- **Authentication at configuration time**
  - Authentication is performed when adding the server to your application or client.
  - The public endpoint remains static; credentials are not embedded in the URL.

- **Central configuration docs**
  - A dedicated configuration page (via Pipedream) provides full setup details for supported clients.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Setup steps (high level):**
  1. Add the MCP server URL to your MCP-compatible app or chat client.
  2. Configure authentication as instructed by the client or configuration guide.
  3. Use the Daily MCP tools to access video and audio APIs within your workflows.

## Pricing
- Not specified in the provided content.