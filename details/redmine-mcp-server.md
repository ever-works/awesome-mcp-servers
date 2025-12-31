# Redmine MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Redmine  
**Source:** https://mcp.pipedream.com/app/redmine

## Description
Redmine MCP Server is an integration that exposes Redmine’s project management and issue tracking capabilities to AI agents via the Model Context Protocol (MCP). It allows compatible MCP clients (such as AI chat applications) to connect to a Redmine instance and work with projects and issues programmatically.

## Features
- **MCP-compatible Redmine access**: Exposes Redmine functionality through a standardized MCP server endpoint (`https://mcp.pipedream.net/v2`).
- **Project management integration**: Connects AI agents to Redmine’s project management data and workflows.
- **Issue and bug tracking**: Enables access to Redmine issue tracking for tasks like creating, listing, or updating issues (implied by Redmine’s core capabilities).
- **Static server URL**: Uses a single static MCP server URL that works across supported clients.
- **Account-based configuration**: Requires connecting your Redmine-related account before selecting a client and using the server.
- **Client-agnostic setup**: Designed to be added to multiple chat or MCP-compatible clients; setup instructions are provided per client type via the configuration page.

## Configuration & Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Connect your account in the Pipedream Redmine MCP interface.
- Add the MCP server to your chosen app or chat client following its specific configuration instructions.
- Optionally consult the full configuration documentation on the linked configuration page.

## Pricing
No explicit pricing information is provided on the referenced page. The page describes Redmine as a “free and open-source project management and issue tracking tool,” but it does not specify pricing terms for the Redmine MCP Server integration itself.