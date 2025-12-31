# Jira Data Center MCP Server

## Overview
The Jira Data Center MCP Server exposes Jira Software Data Center via the Model Context Protocol (MCP), enabling AI agents and MCP-compatible clients to interact with Jira for planning, tracking, and managing large-scale agile software projects.

- **Type:** MCP server / integration
- **Category:** Project Management MCP Servers
- **Ecosystem / Brand:** Atlassian Jira Software Data Center
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Jira Data Center integration via MCP**
  - Connects Jira Software Data Center to MCP-compatible AI agents and applications.
  - Intended for planning, tracking, and managing large-scale agile software projects.

- **Static MCP endpoint**
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL works across all compatible MCP clients.

- **Client-agnostic configuration**
  - Can be added to different chat / AI clients that support MCP.
  - Authentication is handled when adding the server to the client or application.

## Configuration
- Add the MCP server to your MCP-capable client or application using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Authentication is performed during server setup within the client.

## Pricing
- Not specified in the provided content.

## Source
- **More info:** https://mcp.pipedream.com/app/jira_data_center
- **Host platform:** Pipedream Connect
