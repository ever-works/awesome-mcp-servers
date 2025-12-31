# VoxApp MCP Server

**Category:** Messaging MCP Servers  
**Slug:** `voxapp-mcp-server`  
**Brand:** VoxApp  
**Source:** https://mcp.pipedream.com/app/voxapp

## Description
VoxApp MCP Server integrates VoxApp AI voice assistants for business into Model Context Protocol (MCP) environments. It enables building and using voicebots and call assistants from within MCP-compatible clients.

The server is hosted via Pipedream Connect and is accessed through a shared MCP endpoint URL, with authentication handled when configuring the server in each client.

## Features
- **AI voice assistant integration**: Connects VoxApp AI voice assistants to MCP-based applications.
- **Voicebot and call assistant use cases**: Designed for call-center, voice, and agent-style workflows.
- **Static MCP endpoint URL**: Single shared server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client authentication**: Authentication occurs when adding the server to each MCP client.
- **Client-agnostic setup**: Intended to work with any compatible MCP chat client; setup instructions are provided per client via the configuration guidance.
- **Central configuration documentation**: Additional setup and configuration details are available on the platform’s Configuration page.

## Usage
1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this URL as an MCP server in your supported chat/MCP client.
3. Authenticate when prompted by the client.
4. Configure VoxApp voice assistants and call flows through the client / platform configuration.

## Pricing
No pricing information is provided in the available content.