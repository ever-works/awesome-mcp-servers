# New Sloth MCP Server

Simple MCP server interface for media monitoring, market intelligence, and web data extraction via New Sloth.

## Overview
The New Sloth MCP Server exposes New Sloth’s media monitoring and data analytics capabilities to MCP-compatible clients through a single static server URL. Once connected, clients can use New Sloth for data-driven analysis and integrations within their chat or tooling environment.

- **Category:** Content Extraction & Summarization MCP Servers  
- **Use cases:** Media monitoring, market / competitive intelligence, web data extraction, analytics-driven decision support

## Features
- **Media monitoring**  
  - Track and analyze media sources to support monitoring workflows.

- **Market intelligence**  
  - Use New Sloth data and analytics for market and competitive insights.

- **Web data extraction**  
  - Extract structured information from web content for analysis or downstream use.

- **Data analytics / active knowledge**  
  - Provide “active knowledge” from monitored and extracted data to support decisions.

- **MCP server integration**  
  - Exposes New Sloth as an MCP server for use with compatible chat clients and tools.
  - Single **static MCP server URL** for all clients:  
    `https://mcp.pipedream.net/v2`
  - Authentication occurs when adding the server to your application.

- **Client-agnostic setup**  
  - Works with multiple MCP-enabled chat clients.  
  - Per-client setup instructions available via the configuration flow.

- **Configuration via Pipedream**  
  - Connect a New Sloth account through Pipedream.  
  - Select a client after connection to finalize configuration.  
  - Full details available from the Pipedream configuration page (not reproduced here).

## Integration & Usage
- Connect your New Sloth account in Pipedream.
- Use the static MCP URL `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible app.
- Authenticate during server addition and select the appropriate client in the configuration flow.

## Pricing
- No pricing information is provided in the available content.