# Teamioo MCP Server

An MCP (Model Context Protocol) server for integrating Teamioo’s teamwork and project collaboration features into tools and AI agents.

## Overview
- **Type:** MCP server (integration endpoint)
- **Purpose:** Allow chat clients, tools, and agents to connect to Teamioo and leverage its teamwork and project collaboration capabilities.
- **Static MCP URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible endpoint**
  - Provides a single static URL (`https://mcp.pipedream.net/v2`) usable across different MCP-compatible clients.
  - Authentication is handled when adding the server to the client/application.

- **Teamioo integration**
  - Connects tools and agents with Teamioo’s teamwork and project collaboration environment.
  - Intended for use within chat-based or agent-based workflows to access Teamioo-related actions and data (where supported by the MCP implementation and client).

- **Client-agnostic configuration**
  - Works with multiple chat clients that support MCP servers.
  - Configuration guidance available on a central configuration page (per-client setup instructions).

- **Hosted by Pipedream**
  - Runs on Pipedream’s MCP infrastructure (`mcp.pipedream.net`).
  - Governed by Pipedream’s Terms and Privacy Policy.

## Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server URL in a compatible chat client or agent framework.
- Complete authentication during setup within the chosen client.

## Pricing
- Not specified in the provided content.