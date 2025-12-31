# BrandMentions MCP Server

**Category:** Search & Discovery MCP Servers  
**Brand:** BrandMentions  
**Slug:** `brandmentions-mcp-server`

## Description
The BrandMentions MCP Server integrates BrandMentions with MCP-compatible clients, allowing applications to monitor and query brand mentions across the web through a unified MCP server endpoint. It is delivered via Pipedream Connect and uses a static server URL that can be added to any supported MCP client.

## Features
- **MCP integration for BrandMentions**: Exposes BrandMentions capabilities through the Model Context Protocol so MCP clients can work with brand mention data as context or tools.
- **Web-wide brand monitoring**: Designed to track references to a brand or product across the internet (e.g., news sites, blogs, social platforms), leveraging BrandMentions’ monitoring engine.
- **Brand mention querying**: Enables clients to query existing brand mentions (e.g., search for a brand, product, or keyword mentions) through MCP-compatible workflows.
- **Static MCP server endpoint**: Uses a single, static URL that works across all supported MCP clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: Can be added to different MCP chat or agent clients by configuring the same server URL and authenticating within each client.
- **Authentication at client setup**: Authentication is handled when adding the server in the client, rather than requiring different URLs per environment.
- **Configuration guidance**: A separate configuration page (via Pipedream) provides step-by-step instructions for adding the server to various MCP-compatible apps.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Hosting / platform:** Delivered via Pipedream Connect.

## Pricing
No pricing information is provided in the available content.

## Tags
- brand-monitoring  
- social-sentiment  
- web-search