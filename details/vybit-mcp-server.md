# Vybit MCP Server

MCP Server for Vybit that allows sending customized audio notifications through MCP-compatible clients and workflows.

## Overview
Vybit MCP Server integrates Vybit’s personalized sound notifications into MCP-compatible chat clients and applications, enabling audio-based alerts so users can reduce reliance on visual notifications.

- **Type:** MCP server / messaging integration
- **Category:** Messaging MCP Servers
- **Brand:** Vybit
- **Source URL:** https://mcp.pipedream.com/app/vybit
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Customized audio notifications**
  - Send audio-based notifications instead of (or in addition to) visual alerts.
  - Use personalized sounds to distinguish different types of events or messages.

- **MCP-compatible**
  - Exposed as an MCP server that can be added to various MCP-compatible chat clients and tools.
  - Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) across clients.

- **Client-agnostic configuration**
  - Same static URL works for every supported MCP client.
  - Authentication performed when adding the server to the chosen application.

- **Workflow integration**
  - Designed to be used within workflows that trigger audio notifications based on events.

- **Available tools (MCP actions)**
  - Tools / actions are dynamically loaded from the server for supported clients (exact list not shown in source content, but exposed via MCP "available tools").

- **Account-based setup**
  - Connect a Vybit-related account (via the Pipedream integration page) before using tools.
  - Per-account configuration for how notifications are sent.

- **Web-based configuration page**
  - Central configuration interface available via the app’s configuration page on Pipedream.

## Pricing
- The provided content does not include any pricing or plan information for Vybit MCP Server.
