# RedCircle API MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** redcircle  
**Slug:** `redcircle-api-mcp-server`

## Overview
The RedCircle API MCP Server exposes the RedCircle API through the Model Context Protocol (MCP), providing real-time access to Target product data without relying on custom scraping rules or maintaining web scrapers.

## Features
- **MCP server for RedCircle API**: Implements the RedCircle API as an MCP Server for integration with MCP-compatible chat and AI applications.
- **Real-time Target product data**: Provides up-to-date product information from Target via an API interface.
- **No manual rules required**: Eliminates the need to define and maintain custom extraction or parsing rules for Target product pages.
- **No web-scraper maintenance**: Avoids traditional web-scraping approaches and their ongoing maintenance overhead.
- **Static MCP endpoint**: Uses a single static MCP server URL that works across clients:  
  `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: Designed to be added to multiple MCP-compatible chat clients and applications using the same endpoint.
- **Authentication at configuration time**: Authentication is handled when adding the server to an application, rather than embedding credentials in the URL.

## Integration & Usage
- **Server URL**: Add the MCP server to your application using:  
  `https://mcp.pipedream.net/v2`
- **Client setup**: Select your MCP-compatible chat client or app and configure it with the static server URL, then authenticate as prompted.

## Pricing
No pricing information is provided in the available content.