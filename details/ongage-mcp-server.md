# Ongage MCP Server

Email marketing platform integration for data‑driven campaign management via MCP.

## Overview
The Ongage MCP Server is an MCP (Model Context Protocol) integration that connects MCP‑enabled clients to Ongage’s email marketing platform. It exposes Ongage’s APIs so you can manage email campaigns, audiences, and performance data directly from compatible chat or automation clients.

- **Type:** MCP server integration
- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Email campaign management, audience management, performance monitoring and analytics
- **Provider:** Ongage, powered by Pipedream Connect

## MCP Server URL
Use the following static MCP server URL for all clients (authentication occurs when adding the server to your application):

```text
https://mcp.pipedream.net/v2
```

## Features
- **MCP-compatible server**
  - Single static endpoint (`https://mcp.pipedream.net/v2`) usable across MCP clients.
  - Designed to be added as a server within any supported MCP chat or automation client.

- **Ongage email marketing integration**
  - Connects to Ongage’s email marketing platform via Ongage APIs.
  - Enables MCP clients to interact with email marketing data programmatically.

- **Campaign management**
  - Interfaces with Ongage APIs to manage email campaigns from within MCP clients (e.g., creating, updating, or orchestrating campaigns programmatically).

- **Audience management**
  - Accesses Ongage audience and contact data through MCP.
  - Supports workflows that organize or target subscriber lists via Ongage APIs.

- **Performance and analytics access**
  - Surfaces performance data from Ongage (e.g., campaign metrics) to MCP clients.
  - Enables data‑driven workflows and analysis using Ongage’s reporting endpoints.

- **Client-agnostic setup**
  - Same MCP server URL for every client; configuration handled within each MCP-compatible app.
  - Documentation available via the referenced configuration page for step‑by‑step setup (client‑specific instructions).

- **Pipedream Connect infrastructure**
  - Runs on Pipedream Connect’s platform for integration and connectivity.
  - Benefits from Pipedream’s underlying terms, privacy, and cookie policies for the hosted MCP service.

## Setup & Configuration
- Add the server URL `https://mcp.pipedream.net/v2` to your MCP-compatible client.
- Follow that client’s instructions (as referenced on the configuration page) to:
  - Authenticate with Ongage.
  - Enable access to campaigns, audiences, and performance data through the MCP server.

## Pricing
No pricing details are provided in the referenced content. Any costs would depend on Ongage and/or Pipedream’s plans, which are not specified here.