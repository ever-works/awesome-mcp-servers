# D7 SMS MCP Server

## Overview
The D7 SMS MCP Server is an MCP-compatible integration that exposes D7 Networks’ global SMS messaging APIs. It enables applications and chat-based clients to send SMS messages through D7’s telecom infrastructure via a standardized MCP endpoint.

- **Type:** MCP server / messaging integration
- **Provider:** D7 Networks (via Pipedream Connect)
- **Category:** Messaging MCP Servers
- **Use cases:** Programmatic SMS sending, workflow automation, integrating SMS into chat clients or MCP-compatible tools.

## MCP Server Endpoint
- **Server URL (static for all clients):**
  ```
  https://mcp.pipedream.net/v2
  ```
- Authentication is performed when adding the server to your application or chat client.

## Features
- **MCP-compatible SMS gateway**
  - Exposes D7 Networks’ SMS APIs via the Model Context Protocol (MCP).
  - Usable by any MCP-capable client (e.g., chat-based tools that support MCP servers).

- **Global SMS connectivity**
  - Built on D7 Networks’ global SMS network.
  - Designed for sending SMS messages to international destinations.

- **Static server URL**
  - Single, fixed endpoint (`https://mcp.pipedream.net/v2`) for all clients.
  - Simplifies configuration across different tools and environments.

- **Integration via Pipedream Connect**
  - Provided and hosted through Pipedream’s integration platform.
  - Can be combined with other Pipedream workflows and connectors (where supported by your broader setup).

- **Client-agnostic setup**
  - Same server endpoint regardless of which chat client or application you use.
  - Configuration handled on the client side, with authentication performed during setup.

## Configuration & Setup
- Add the MCP server by using the static URL:
  ```
  https://mcp.pipedream.net/v2
  ```
- Configure authentication within your MCP-compatible client when registering this server.
- For detailed, client-specific setup steps, refer to the platform’s configuration documentation (e.g., “Configuration” page linked from the originating site).

## Pricing
- No explicit pricing information is provided in the available content. Consult D7 Networks or the Pipedream / Pipedream Connect documentation for current pricing and billing details related to SMS usage and MCP hosting.
