# Agility CMS MCP Server

## Overview
Agility CMS MCP Server connects the Agility headless CMS (with layout management capabilities) to the MCP ecosystem, allowing AI agents and MCP-compatible clients to manage and interact with CMS content programmatically.

- **Type:** MCP server / integration
- **Category:** Content Management MCP Servers
- **Tags:** cms, content-management, headless
- **Provider:** Agility CMS (via Pipedream Connect)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Headless CMS integration**
  - Connects Agility CMS (a headless CMS with layouts) into MCP-compatible applications.
  - Enables programmatic interaction with content managed in Agility CMS.

- **Layouts support**
  - Designed for a headless CMS that also manages layouts, allowing agents to work with both content and layout structures (as supported by Agility CMS).

- **MCP ecosystem compatibility**
  - Exposes Agility CMS capabilities as an MCP server so AI agents and tools that speak MCP can discover and use the CMS.
  - Uses a single, static MCP server URL that works across different clients.

- **Static server endpoint**
  - One universal MCP server endpoint: `https://mcp.pipedream.net/v2`.
  - Authentication is handled when adding the server in the client, not by changing the URL.

- **Client-agnostic setup**
  - Designed to be added to various MCP-enabled chat or agent clients.
  - Documentation and configuration guidance available via the linked configuration page (client-specific steps, not detailed in the provided content).

## Pricing
Pricing information is not provided in the available content.

## Getting Started
- Use the MCP server URL: `https://mcp.pipedream.net/v2` when adding a new MCP server in your client.
- Authenticate within your chosen MCP-compatible app during server setup.
- Refer to the platform’s configuration page for client-specific setup instructions.