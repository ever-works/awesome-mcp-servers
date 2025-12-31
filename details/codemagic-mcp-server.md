# Codemagic MCP Server

**Category:** Cloud & DevOps MCP Servers  
**Brand:** Codemagic  
**Slug:** `codemagic-mcp-server`

## Overview
Codemagic MCP Server is an MCP (Model Context Protocol) server integration for Codemagic that enables MCP-compatible tools and clients to orchestrate and monitor mobile-first CI/CD workflows within Codemagic pipelines. It is provided via Pipedream Connect as a hosted MCP endpoint.

## MCP Server Endpoint
- **Base URL (static for all clients):**
  ```
  https://mcp.pipedream.net/v2
  ```
- Authentication occurs when adding the server to your MCP-enabled application or chat client.

## Features
- **Mobile-first CI/CD integration**
  - Designed to work with Codemagic’s mobile-focused continuous integration and delivery workflows.
  - Enables orchestration and monitoring of mobile build and deployment pipelines via MCP tools.

- **Hosted MCP server**
  - Exposed as a static, shared MCP server URL usable from any compatible client.
  - Managed and hosted by Pipedream Connect, removing the need to self-host an MCP server.

- **Client-agnostic setup**
  - Works with multiple MCP-enabled chat or agent clients.
  - A single URL is used across different clients; configuration is performed in the client when adding the server.

- **Configuration guidance**
  - Can be added to supported chat clients using documented configuration steps.
  - A separate configuration page is referenced for detailed setup instructions (per client).

## Integration & Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your MCP-capable application or chat client.
- Authenticate within the client as prompted to connect to Codemagic workflows through the Pipedream-hosted MCP server.

## Pricing
- No pricing information is provided in the available content.