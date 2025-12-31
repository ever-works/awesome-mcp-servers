# OpenGraph.io MCP Server

## Overview
The OpenGraph.io MCP Server is an MCP-compatible service that connects to the OpenGraph.io API, allowing tools and agents to unfurl URLs and retrieve Open Graph metadata without implementing custom scraping logic. It is provided via a static MCP endpoint hosted on Pipedream.

- **Category:** Content Extraction & Summarization MCP Servers
- **Use Cases:** URL unfurling, link previews, metadata extraction from web pages

## Features
- **Open Graph Metadata Retrieval:** Fetches Open Graph tags and related metadata for a given URL.
- **URL Unfurling:** Expands URLs into structured information suitable for link previews and content summaries.
- **Central MCP Endpoint:** Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works across compatible clients.
- **Client-agnostic Integration:** Designed to be added to different chat or agent clients that support MCP, using the same server URL.
- **No Custom Scraping Required:** Offloads HTML parsing and scraping to the OpenGraph.io API, avoiding the need to maintain custom scraping logic.
- **Pipedream-hosted Infrastructure:** Runs on Pipedream’s MCP infrastructure (Pipedream Connect), with centralized configuration and management.

## Integration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Setup:**
  - Add the MCP server URL to your MCP-compatible client or application.
  - Authenticate as required when configuring the server in your app.
  - Configuration details are available via the platform’s configuration page.

## Pricing
Pricing information is not provided in the available content.