# Axonaut MCP Server

## Overview
Axonaut MCP Server is an MCP (Model Context Protocol) integration for Axonaut that allows MCP-enabled applications (such as compatible chat clients) to automate billing and business management workflows within the Axonaut CRM environment.

- **Category:** Business & Commerce – MCP Servers
- **Brand:** Axonaut
- **Integration Host:** Pipedream
- **Primary Use Cases:** Billing automation, business management workflows, CRM-related operations via MCP tools

## Features

- **MCP-based integration**
  - Exposes Axonaut functionality as MCP tools that can be used by compatible clients and assistants.
  - Designed to support billing and business management workflows in Axonaut through automated actions.

- **Static MCP server URL**
  - Single static endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Same URL used across different chat clients and MCP-compatible applications.

- **Account-based authentication**
  - Authentication occurs when adding the MCP server to your application, not when copying the URL.
  - Works on a per-account basis so each user connects their own Axonaut account.

- **Multi-client compatibility**
  - Intended for use with various MCP-compatible chat clients and tools.
  - Configuration guidance is available per client type (via Pipedream’s configuration resources).

- **CRM-oriented**
  - Integrates specifically with Axonaut’s CRM context, allowing workflows around customer and billing data.

- **Configuration support via Pipedream**
  - Central place to configure Axonaut connection and then select the relevant client.
  - A dedicated configuration page (on Pipedream) provides the full setup details.

> Note: The UI mentions "Available tools" and "Loading actions...", but specific tool names and actions are not listed in the provided content.

## Pricing

The provided content does not include any pricing information or plan details for Axonaut MCP Server.