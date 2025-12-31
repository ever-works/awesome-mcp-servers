# ServiceM8 MCP Server

An MCP server integration that lets MCP-based agents access and manage field service operations in ServiceM8, including jobs, scheduling, and client data.

## Overview
- **Type:** MCP server / integration
- **Platform:** ServiceM8 via Pipedream
- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Field service management, job management, scheduling, client data access through MCP-compatible chat or agent clients.

## Features
- **ServiceM8 integration**
  - Connects MCP-based agents to your ServiceM8 account.
  - Enables interaction with ServiceM8 field service data (jobs, scheduling, client information).

- **Static MCP server endpoint**
  - Single static URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when adding the server to your application, not via per-client URL changes.

- **Multi-client compatibility**
  - Designed to be added to different MCP-compatible chat or agent clients.
  - Step-by-step configuration guidance available via the configuration page in the Pipedream interface.

- **Managed hosting**
  - MCP server hosted by Pipedream; no need to deploy your own MCP infrastructure.

- **Tool-based operations**
  - Exposes ServiceM8 capabilities as “tools” (actions) to MCP agents (e.g., for jobs, scheduling, client records). *(Specific tools are dynamically loaded in the UI and not listed in the provided content.)*

## Configuration
- Connect your ServiceM8 account within Pipedream.
- Use the static MCP server URL `https://mcp.pipedream.net/v2` in your MCP-compatible app.
- Authenticate when adding the server to your application.
- Optionally follow the detailed instructions on the Pipedream configuration page.

## Pricing
- Not specified in the provided content. Refer to the Pipedream and/or ServiceM8 pricing pages for current details.