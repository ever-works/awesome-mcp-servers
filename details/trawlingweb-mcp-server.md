# Trawlingweb MCP Server

## Overview
Trawlingweb MCP Server is a Model Context Protocol (MCP) server that connects applications to Trawlingweb’s large-scale collections of news and social data gathered from the web and social networks. It is hosted via Pipedream and exposed through a static MCP server URL.

- **Category:** Web Search MCP Servers  
- **Use cases:** News monitoring, social media analysis, data analytics, data extraction from web and social sources.

## Features
- **Access to news data**: Integrates with Trawlingweb’s large-scale news collections from across the web.
- **Access to social data**: Provides data collected from various social networks and user-generated content.
- **Web-wide coverage**: Designed to collect and expose information published on the web and social media platforms.
- **Data analytics integration**: Intended for use in analytics workflows that rely on news and social data.
- **MCP-compatible endpoint**: Exposed as a Model Context Protocol server for easy integration into MCP-compatible chat and AI clients.
- **Static server URL**: Uses a single, static URL (`https://mcp.pipedream.net/v2`) that works for all clients, simplifying configuration.
- **Per-client authentication**: Authentication occurs when adding the MCP server to a client or application, allowing secure, account-based access.
- **Client-agnostic setup**: Can be added to various chat clients or MCP-capable tools; configuration guidance is available via the Pipedream configuration pages.
- **Tool-based interaction**: Exposes “tools” (actions) that can be invoked from supported clients to query or work with Trawlingweb data.

## Configuration
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Setup flow:**
  - Connect a Trawlingweb account in Pipedream.
  - Select the appropriate client.
  - Add the MCP server URL to the client and authenticate.
  - Use the available tools/actions once they load in the client.

## Pricing
The provided content does not list any pricing or plans for the Trawlingweb MCP Server.