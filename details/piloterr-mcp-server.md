# Piloterr MCP Server

An MCP Server that connects to Piloterr’s web scraping platform, enabling MCP-compatible agents and chat clients to perform structured web scraping via a unified endpoint.

## Overview
- **Type:** MCP server (Model Context Protocol)
- **Purpose:** Structured web scraping and data extraction
- **Provider / Infrastructure:** Powered by Pipedream Connect
- **Base MCP URL:** `https://mcp.pipedream.net/v2`

## Features
- **Unified MCP Endpoint**  
  - Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) for all supported clients.  
  - Authentication is handled when adding the server to each application.

- **Integration with MCP-Compatible Clients**  
  - Designed to be added to various MCP-supporting chat clients and agents.  
  - Clients can use the same endpoint and configure authentication per environment.

- **Piloterr Web Scraping Integration**  
  - Connects MCP agents to the Piloterr web scraping platform for structured web scraping tasks.  
  - Suitable for web scraping and data extraction workflows that need to run via an MCP server.

- **Configuration Resources**  
  - Documentation available via a dedicated configuration page (how to add and configure the server in different clients).

## Use Cases
- Running structured web scraping jobs from MCP-compatible chat clients.
- Integrating web data extraction into agent workflows via a single MCP endpoint.

## Pricing
- Not specified in the provided content.