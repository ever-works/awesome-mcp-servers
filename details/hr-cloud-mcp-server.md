# HR Cloud MCP Server

## Overview
The HR Cloud MCP Server exposes HR Cloud’s all‑in‑one HRIS capabilities—focused on employee onboarding and engagement—through the Model Context Protocol (MCP). It is hosted and provided via Pipedream and can be connected to compatible MCP-enabled chat or AI applications.

- **Category:** Business & Commerce – MCP Servers
- **Use cases:** HR automation, employee onboarding workflows, engagement-related actions via MCP tools
- **Provider / Brand:** HR Cloud (hosted on Pipedream)

## Features

### MCP Server Integration
- Provides a static, reusable MCP server URL: `https://mcp.pipedream.net/v2`
- Can be added to any compatible MCP client / chat application
- Authentication is handled when adding the server to your application (per-client authentication flow)

### HR Cloud Capabilities (via MCP)
- Exposes HR Cloud’s core HRIS functionality, with emphasis on:
  - Employee onboarding workflows
  - Employee engagement–related operations
- Designed to let AI/chat clients invoke HR Cloud actions as MCP tools (actions list is dynamically loaded in the interface: “Loading actions…”, “Loading available tools…”)

### Configuration & Management
- Connect an existing HR Cloud account via Pipedream
- Select the relevant HR Cloud client/instance after connection
- Centralized configuration page available on Pipedream for advanced setup

## Technical Details
- **Protocol:** Model Context Protocol (MCP)
- **Endpoint type:** Static URL shared across all HR Cloud clients (per-user authentication applied at configuration time)
- **Environment:** Hosted on Pipedream’s MCP infrastructure

## Pricing
The provided content does not list any pricing or plan information for the HR Cloud MCP Server or associated services.