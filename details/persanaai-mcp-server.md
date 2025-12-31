# PersanaAI MCP Server

An MCP server that integrates PersanaAI’s AI-driven sales prospecting, lead research, and outreach workflows into MCP-compatible applications.

## Overview
- **Type:** MCP server (for MCP-based apps / chat clients)
- **Focus:** Sales prospecting, lead research, and outreach automation using PersanaAI
- **Provider:** PersanaAI via Pipedream Connect
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP Integration**
  - Exposes PersanaAI capabilities through the Model Context Protocol (MCP)
  - Usable from any compatible MCP-based client or chat application
  - Single static base URL for all clients (`https://mcp.pipedream.net/v2`)

- **AI-Driven Sales Prospecting**
  - Designed to assist with sales prospecting workflows using AI
  - Supports workflows for identifying and researching leads
  - Helps structure and automate outreach-related tasks

- **Centralized Configuration**
  - Static MCP URL works across different clients
  - Authentication is performed when adding the server within each client
  - Additional configuration guidance available via the linked configuration documentation (Pipedream configuration page)

- **Pipedream Connect Integration**
  - Delivered through Pipedream Connect’s infrastructure
  - Can be combined with other Pipedream-powered workflows and integrations (via the Pipedream ecosystem)

## Usage
- **Server URL:**
  ```text
  https://mcp.pipedream.net/v2
  ```
- **Client Setup:**
  - Add the above URL as an MCP server in your MCP-compatible chat client or application
  - Authenticate with your credentials when prompted by the client
  - Follow any client-specific instructions from the configuration documentation (via Pipedream’s configuration page)

## Pricing
- Not specified in the provided content. No plan or pricing details are available from this source.