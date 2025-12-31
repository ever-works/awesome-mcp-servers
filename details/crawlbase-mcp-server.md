# Crawlbase MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Tags:** web-scraping, proxy, data-extraction

## Overview
Crawlbase MCP Server is an MCP (Model Context Protocol) server integration that connects MCP-compatible agents and chat clients to Crawlbase’s web crawling, scraping, and proxy capabilities through Pipedream. It provides a static MCP endpoint that applications can register to gain programmatic access to Crawlbase’s data crawling infrastructure.

## Features
- **MCP-compatible server endpoint**  
  - Provides a single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Can be added to any supported MCP chat client or application.

- **Integration with Crawlbase platform**  
  - Connects to a Crawlbase account via Pipedream configuration.  
  - Exposes Crawlbase’s crawling, scraping, and proxy features to MCP-compatible agents.

- **Client-agnostic setup**  
  - Same server URL works across different MCP clients.  
  - Authentication handled when adding the server to the client or app.

- **Configurable via Pipedream UI**  
  - "Configure Crawlbase" flow to connect your Crawlbase account.  
  - Client selection to view specific setup instructions.  
  - Link to a full configuration page for detailed setup steps.

- **Tool-based access**  
  - Exposes "Available tools" (actions) to the connected MCP client (details are loaded dynamically in the UI).  
  - Designed for programmatic use in data analytics and automation flows.

## Usage
1. Connect your Crawlbase account in the Pipedream "Configure Crawlbase" screen.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this server URL to your MCP-compatible chat client or application.  
4. Authenticate when prompted in the client.  
5. Use the exposed tools/actions to perform web crawling, scraping, and data extraction via Crawlbase.

## Pricing
The provided content does not list any pricing or plan details for the Crawlbase MCP Server integration.