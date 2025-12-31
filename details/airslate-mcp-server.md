# Airslate MCP Server

**Category:** Workflow Automation MCP Servers  
**Brand:** airSlate  
**Source:** https://mcp.pipedream.com/app/airslate  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview
Airslate MCP Server is an MCP (Model Context Protocol) server integration that exposes airSlate’s document workflow and automation capabilities—along with related services like signNow, pdfFiller, USLegalForms, and DocHub—to MCP-based agents and tools. It lets applications and chat clients interact programmatically with these services through a standardized MCP interface.

## Features
- **MCP-based integration**
  - Implements a static MCP server endpoint: `https://mcp.pipedream.net/v2`.
  - Can be added to compatible MCP-enabled apps and chat clients.

- **Account-based configuration**
  - Connect an airSlate-related account to enable the integration.
  - Select a client/account context after connection to start using tools.

- **Document workflow & automation exposure**
  - Surfaces airSlate’s document workflow and automation solutions to MCP agents.
  - Integrates with the broader airSlate ecosystem, including:
    - airSlate (workflow automation)
    - signNow (e-signatures)
    - pdfFiller (PDF editing and form filling)
    - USLegalForms (legal document templates)
    - DocHub (PDF and document management)

- **Surveys & forms support**
  - Designed to work with surveys and forms scenarios (as indicated by the interface context).

- **Tool discovery via MCP client**
  - "Available tools" are dynamically loaded in the MCP client after configuration (exact tools not listed in the provided content but are exposed through the server).

- **Central configuration reference**
  - Full configuration details available via a dedicated configuration page (linked from the app UI).

## Authentication
- Uses a **static MCP server URL** for all clients.
- Authentication occurs when adding/configuring the server in the target application or chat client, rather than via per-client URLs.

## Usage
1. Connect your airSlate-related account in the Airslate MCP Server page on Pipedream.
2. Select the appropriate client/account context.
3. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
4. Add this server URL to your MCP-capable application or chat client and authenticate.
5. Use the loaded tools to automate and manage document workflows, forms, and related tasks.

## Pricing
- No pricing information is provided in the supplied content.