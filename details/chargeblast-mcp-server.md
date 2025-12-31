# Chargeblast MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Chargeblast  
**Slug:** `chargeblast-mcp-server`

## Description
Chargeblast MCP Server exposes Chargeblast’s chargeback reduction workflows over the Model Context Protocol (MCP), allowing AI tools and chat-based clients to integrate chargeback mitigation processes into their applications. It is intended for hypergrowth startups that want to automate and streamline chargeback-related operations.

## Features
- **MCP-compatible server**: Implements the Model Context Protocol so AI tools and chat clients can interact with Chargeblast programmatically.
- **Static server endpoint**: Uses a single, static MCP server URL that works for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: Designed to be added to various MCP-capable chat clients; setup is handled at the client level with authentication during configuration.
- **Authentication at connection time**: Authentication is performed when adding the server to an application, allowing secure, per-client access.
- **Chargeback workflow integration**: Connects AI tools to Chargeblast’s chargeback reduction workflows aimed at significantly lowering chargeback rates for high-growth businesses.
- **Hosted via Pipedream Connect**: Runs on Pipedream’s infrastructure, removing the need to self-host the MCP server.
- **Central configuration documentation**: A dedicated configuration page (via Pipedream) provides instructions for adding and configuring the server in different clients.

## Usage
- Use the endpoint `https://mcp.pipedream.net/v2` as the MCP server URL in compatible chat or AI clients.
- Configure authentication within your chosen client following its MCP server setup instructions (as outlined in the related configuration documentation).

## Pricing
- No pricing information is provided in the available content.