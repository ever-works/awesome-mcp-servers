# InMobile MCP Server

Efficient SMS gateway access via MCP-based workflows and tools.

## Overview
The InMobile MCP Server exposes InMobile’s SMS gateway through a standardized MCP (Model Context Protocol) endpoint, allowing chat clients and MCP-compatible tools to send SMS messages as part of automated workflows.

- **Type:** MCP server (messaging / SMS gateway)
- **Provider:** InMobile (hosted via Pipedream Connect)
- **Category:** Messaging MCP servers
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible SMS access** – Provides an MCP server endpoint that connects to InMobile’s SMS gateway.
- **Static, shared server URL** – Uses a single static URL (`https://mcp.pipedream.net/v2`) that works across clients.
- **Per-client authentication** – Authentication is performed when adding the server to each application/client (credentials not embedded in the URL).
- **Chat client integration** – Designed to be added to supported chat clients, enabling SMS actions from within those clients.
- **Workflow integration via Pipedream Connect** – Runs on Pipedream’s infrastructure, allowing use within broader Pipedream-based automations and tools.
- **Configuration documentation** – A central configuration page (linked from the app) explains how to connect and configure the MCP server with different clients.

## Setup
1. Use the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this server URL in your MCP-compatible chat client or tool.
3. Authenticate when prompted by the client according to its instructions.
4. Optionally, refer to the provider’s configuration page for client-specific steps.

## Pricing
The provided content does not include any pricing or plan information for the InMobile MCP Server or underlying InMobile/Pipedream usage.