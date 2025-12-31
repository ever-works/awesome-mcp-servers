# SerpApi MCP Server

## Overview
The SerpApi MCP Server is a Pipedream-hosted MCP (Model Context Protocol) server integration that allows tools and agents to access SerpApi’s search capabilities. It enables scraping of Google and other search engines via SerpApi’s fast, comprehensive search API through a single static MCP endpoint.

- **Name:** SerpApi MCP Server  
- **Category:** Web Search MCP Servers  
- **Slug:** serpapi-mcp-server  
- **Provider / Brand:** SerpApi (via Pipedream Connect)  
- **Source URL:** https://mcp.pipedream.com/app/serpapi

## Features
- **Search engine scraping via SerpApi**  
  - Scrape Google and other supported search engines through SerpApi’s API.  
  - Designed for fast and complete search results retrieval.

- **MCP-compatible server**  
  - Exposes SerpApi functionality as an MCP server for use with MCP-compatible chat or agent clients.  
  - Centralized MCP endpoint usable across different clients and applications.

- **Static MCP server URL**  
  - Single, static URL that works for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Simplifies configuration since the same endpoint can be reused across tools.

- **Client-agnostic integration**  
  - Can be added to various chat or agent clients that support MCP.  
  - Authentication is handled when adding the server to the application, not at URL level.

- **Configuration documentation**  
  - Detailed setup and configuration instructions available via the referenced Configuration page.

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Hosting / Runtime:** Powered by Pipedream Connect  
- **Integration Type:** External search API integration exposed over MCP

## Pricing
The provided content does not include any pricing or plan details for the SerpApi MCP Server or underlying SerpApi / Pipedream services.