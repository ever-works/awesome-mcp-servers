# ngrok MCP Server

## Overview
The ngrok MCP Server is an MCP-compatible service that connects MCP clients (such as ChatGPT) to ngrok’s secure tunnels and gateway services. It enables AI tools to manage ngrok HTTPS Edges and access exposed local or remote services via ngrok.

- **Category:** Cloud & DevOps MCP Servers
- **Provider / Brand:** ngrok (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP server endpoint**
  - Single static MCP server URL: `https://mcp.pipedream.net/v2`
  - Works with any compatible MCP client; authentication handled when adding the server to the application.

- **HTTPS Edge management tools (actions)**
  - **Create HTTPS Edge**
    - Create a new HTTPS Edge in ngrok.
    - Configurable according to ngrok’s HTTPS Edge API (e.g., hostnames, routes, backend services – per ngrok documentation).
  - **Get HTTPS Edge**
    - Retrieve details of an existing HTTPS Edge.
    - Useful for inspecting current configuration, status, and properties of the edge.
  - **Update HTTPS Edge**
    - Modify an existing HTTPS Edge.
    - Supports updating configuration parameters as exposed via the ngrok HTTPS Edge API.
  - **Delete HTTPS Edge**
    - Remove an existing HTTPS Edge from ngrok.

- **Client integration guidance**
  - Instructions available for adding the server to specific chat clients (e.g., ChatGPT / OpenAI clients).
  - Links to a full configuration page for broader MCP client setup.

- **Use cases (implied from ngrok capabilities)**
  - Managing API gateways via HTTPS Edges.
  - Handling IoT device gateway endpoints.
  - Operating secure tunnels for containers, applications, and APIs from within MCP-compatible AI tools.

## Requirements & Setup
- **ngrok account connection**
  - Users must sign in via Pipedream to connect their ngrok account.
  - Once connected, they can manage ngrok HTTPS Edges through MCP-compatible clients.

- **MCP client configuration**
  - Add `https://mcp.pipedream.net/v2` as an MCP server in the client.
  - Authenticate when prompted to enable ngrok tool access.

## Pricing
The provided content does not include any pricing information for the ngrok MCP Server or related plans.