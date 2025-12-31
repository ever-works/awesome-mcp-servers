# Chaindesk MCP Server

An MCP (Model Context Protocol) server for integrating Chaindesk-powered agents into MCP-compatible clients.

## Overview
Chaindesk MCP Server lets you build and use ChatGPT-style agents trained on custom data within MCP ecosystems. It is delivered as a static MCP server endpoint hosted by Pipedream Connect.

## Features
- **Custom-data agents**: Use Chaindesk to build agents that are trained on your own content and knowledge base.
- **MCP-compatible server**: Exposes Chaindesk agents via the Model Context Protocol for use in compatible chat clients and tools.
- **Single static endpoint**: Uses a single, static MCP server URL that works across clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client authentication**: Authentication is handled when you add the MCP server to each application or client.
- **Works with multiple chat clients**: Can be added to different MCP-aware chat clients (e.g., ChatGPT or others that support MCP configuration).
- **Central configuration docs**: Additional setup details are available via a configuration page (not included here, but referenced on the source site).

## Getting Started
1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this URL as an MCP server in your MCP-compatible chat client.
3. Authenticate when prompted by the client.
4. Configure or select Chaindesk agents trained on your custom data within that environment.

## Pricing
The provided content does not include any pricing information for the Chaindesk MCP Server.