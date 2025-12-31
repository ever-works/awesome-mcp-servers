# Enrichley MCP Server

Catch-all email validation via MCP workflows.

## Overview
Enrichley MCP Server is an MCP (Model Context Protocol) server integration that provides catch-all email validation services. It’s exposed via a static MCP endpoint hosted by Pipedream, which you can connect to from compatible chat clients and MCP-enabled applications.

- **Type:** MCP server integration
- **Category:** Business & Commerce – MCP Servers
- **Use case:** Email verification, validation, and data enrichment through MCP workflows

## Features
- **Catch-all email validation:** Supports validating email addresses in a catch-all manner, suitable for workflows that need to confirm whether an address is generally valid/accepting mail.
- **MCP-compatible endpoint:** Exposed as an MCP server that can be consumed by MCP-capable clients and tools.
- **Static server URL:** Uses a single, static MCP server URL (`https://mcp.pipedream.net/v2`) that works across all supported clients.
- **Per-client authentication:** Authentication is performed when adding/configuring the server in each client application.
- **Integration via chat clients:** Can be added to supported chat or assistant clients to perform email validation within conversations and automations.

## Configuration & Access
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Setup:**
  - Copy the static server URL.
  - Add the MCP server to your chosen chat client or application.
  - Authenticate within that client as prompted.
  - Optionally refer to the platform’s configuration guide ("Configuration" page referenced on Pipedream) for client-specific setup details.

## Pricing
The provided content does not specify any pricing or plans for the Enrichley MCP Server integration.