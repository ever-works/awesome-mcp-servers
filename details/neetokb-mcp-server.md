# neetoKB MCP Server

Simple MCP server integration for neetoKB, a hosted knowledge base designed to reduce support requests.

## Overview
- **Type:** MCP Server (Model Context Protocol)
- **Purpose:** Connects chat clients and MCP-compatible applications to a neetoKB knowledge base.
- **Category:** Content Management MCP Servers
- **Tags:** knowledge-base, documentation, helpdesk

## Features
- **Static MCP Server Endpoint**  
  - Single shared URL for all compatible clients:  
    `https://mcp.pipedream.net/v2`
  - No per-client URL differences; configuration is standardized.

- **Client-Agnostic Integration**  
  - Works with any MCP-compatible chat client or application.  
  - Add the server by pointing your client to the static MCP URL.

- **Knowledge Base Access**  
  - Designed to connect to neetoKB, a simple hosted knowledge base.  
  - Intended to surface KB content in chat or agent workflows to help reduce support requests.

- **Centralized Configuration Resources**  
  - Documentation available via a general configuration page ("Configuration"), describing how to add the MCP server to different clients.

- **Hosted by Pipedream**  
  - Runs on Pipedream’s infrastructure (Pipedream Connect), so there is no self-hosting of the MCP endpoint required.

## Setup
1. Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this URL in your MCP-compatible client’s configuration.
3. Authenticate within your client when prompted (details depend on the client and configuration docs).

## Pricing
- No pricing information is provided in the available content.
