# Smartproxy MCP Server

## Overview
Smartproxy MCP Server is an MCP-compatible server that exposes Smartproxy’s web scraping and proxy infrastructure to AI agents and MCP clients. It enables programmatic web data collection through a single, static server endpoint that can be integrated into compatible chat or agent applications.

- **Category:** Web Search MCP Servers  
- **Use cases:** Web and app development, web scraping, data collection via Smartproxy’s proxy and scraping services

## Features
- **MCP-compatible server** – Implements the Model Context Protocol (MCP) so that AI agents and MCP clients can interact with Smartproxy programmatically.
- **Access to Smartproxy infrastructure** – Provides access to Smartproxy’s web scraping and proxy network for data collection.
- **Static server URL** – Single endpoint for all clients:  
  `https://mcp.pipedream.net/v2`
- **Client-agnostic integration** – The same server URL works with multiple MCP-compatible chat or agent clients; authentication is handled when adding the server to the application.
- **Configuration via Pipedream** – Setup and configuration are managed through Pipedream’s interface, including connecting a Smartproxy account and selecting the desired client.
- **Web & app development focus** – Designed to be embedded into development workflows that require automated web data collection.

## Configuration
- **Server URL:** `https://mcp.pipedream.net/v2` (static for all clients)
- **Setup flow:**
  1. Connect your Smartproxy account in Pipedream.
  2. Copy the MCP server URL.
  3. Add the server to your MCP-compatible app or chat client.
  4. Authenticate when prompted by the client.
- A more detailed configuration guide is available on the linked configuration page from Pipedream.

## Available Tools
- The server exposes tools (actions) for interacting with Smartproxy’s web scraping and proxy services. Specific tools are dynamically loaded by the Pipedream interface and may vary over time.

## Pricing
- No explicit pricing details for the Smartproxy MCP Server or Smartproxy usage are provided in the available content. Pricing would follow Smartproxy and/or Pipedream account plans, which must be checked on their respective sites.