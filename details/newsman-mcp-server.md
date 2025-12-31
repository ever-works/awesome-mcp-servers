# Newsman MCP Server

## Overview
The Newsman MCP Server exposes Newsman’s smart email service through the Model Context Protocol (MCP), allowing compatible clients to create, send, and track marketing and transactional emails via a unified MCP interface.

- **Type:** MCP server / email service integration
- **Category:** Messaging MCP servers
- **Provider:** Newsman (via Pipedream Connect)
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **Email creation**
  - Integrates with Newsman’s smart email service for composing email campaigns.
  - Supports creation of “beautiful emails” using Newsman’s editor capabilities (e.g., custom editor blocks).

- **Email sending**
  - Send emails through Newsman via the MCP interface from compatible chat or developer clients.

- **Email tracking**
  - Track sent emails (e.g., delivery / engagement) using Newsman’s tracking features, exposed through MCP.

- **Automation-oriented design**
  - Technical yet user-friendly approach aimed at automating email-related workflows.
  - Leverages Newsman’s automation capabilities such as custom preferences pages and reusable editor blocks.

- **Standard MCP server URL**
  - Uses a static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL works for all MCP-compatible clients; authentication is handled when adding the server in the client.

- **Multi-client compatibility**
  - Designed to be added to various MCP-compatible chat clients and tools.
  - Central configuration documentation available via the Pipedream Configuration page.

## Integration & Configuration
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Setup flow:**
  - Add the MCP server URL to your MCP-compatible client.
  - Authenticate with Newsman when prompted by your client.
  - Optionally refer to the full configuration documentation on Pipedream for client-specific setup.

## Pricing
No pricing information is provided in the available content. Refer to Newsman or Pipedream for current pricing and plan details.