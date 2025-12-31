# WhoisFreaks MCP Server

**Category:** Search & Discovery MCP Servers  
**Brand:** WhoisFreaks  
**Slug:** `whoisfreaks-mcp-server`

## Description
The WhoisFreaks MCP Server is a model context protocol (MCP) server that allows AI agents and chat-based applications to query domain WHOIS data and related domain intelligence using the WhoisFreaks API. It is provided via Pipedream Connect and exposes a static MCP endpoint that can be integrated with compatible clients.

## Features
- **WHOIS data access**: Enables querying of domain WHOIS records via the WhoisFreaks API.
- **Domain intelligence**: Provides access to related domain intelligence data (e.g., metadata associated with domain ownership and registration), as supported by the WhoisFreaks API.
- **MCP-compatible server**: Implements the Model Context Protocol so that AI agents and MCP-capable chat clients can consume WhoisFreaks data.
- **Static server URL**: Uses a single static MCP endpoint that works across supported clients:  
  - MCP server URL: `https://mcp.pipedream.net/v2`
- **Client-agnostic setup**: Designed to be added to various MCP-compatible chat clients; configuration is handled at the client level.
- **Authentication via client**: Authentication to WhoisFreaks is performed when adding/configuring the server within your application or client (credentials not hard-coded in the URL).
- **Hosted by Pipedream Connect**: The MCP server is run and delivered through Pipedream’s infrastructure.

## Integration & Usage
- **Add to your app**: Configure the MCP server URL (`https://mcp.pipedream.net/v2`) in your MCP-enabled chat client or application.
- **Configuration reference**: Detailed setup and configuration options are available on the provider’s Configuration page (linked from the product page).

## Pricing
Pricing information is not provided in the available content. Refer to the provider’s main site or API documentation for details on plans and usage costs.