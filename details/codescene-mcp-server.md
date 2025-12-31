# CodeScene MCP Server

**Category:** Repository Code Analysis MCP Servers  
**Brand:** CodeScene  
**Slug:** codescene-mcp-server

## Description
CodeScene MCP Server is an MCP (Model Context Protocol) server integration that connects MCP-compatible tools and chat clients to CodeScene. It enables behavioral code analysis of repositories, linking code changes with team activity and business priorities.

The integration is hosted via Pipedream at a static MCP server URL:

- `https://mcp.pipedream.net/v2`

## Features
- **MCP server integration for CodeScene**
  - Exposes CodeScene capabilities as MCP tools that can be invoked by compatible clients.
  - Allows chat-based or programmatic access to CodeScene’s analysis functions.

- **Behavioral code analysis**
  - Uses CodeScene’s behavioral analysis to understand how the codebase evolves over time.
  - Connects code changes with team behavior and work patterns.

- **Business-aware insights**
  - Surfaces insights that connect code, development teams, and business priorities.
  - Helps prioritize work based on impact to the codebase and organization.

- **Static MCP server URL**
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) that works across all supported MCP clients.
  - Authentication occurs when adding/configuring the server in the target application.

- **Multi-client support**
  - Designed to be added to multiple chat or MCP-enabled clients.
  - Configuration instructions are available per client via the hosting platform.

- **Central configuration via Pipedream**
  - Connect a CodeScene account through Pipedream to enable the MCP server.
  - Configuration can be managed from a dedicated configuration page on the hosting platform.

## Setup
1. Connect your CodeScene account via the Pipedream-hosted configuration page.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this MCP server URL to your chosen MCP-compatible application or chat client.  
4. Authenticate when prompted in the client.

## Pricing
No pricing information is provided in the available content.