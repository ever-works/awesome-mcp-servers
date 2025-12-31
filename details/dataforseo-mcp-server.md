# DataForSEO MCP Server

**Category:** Web Search MCP Servers  
**Slug:** `dataforseo-mcp-server`  
**Source:** https://mcp.pipedream.com/app/dataforseo

## Overview
DataForSEO MCP Server connects DataForSEO’s aggregated SERP, marketplace, review, and web data to MCP-compatible tools and chat clients. It enables SEO, marketing, and analytics workflows by exposing DataForSEO actions as tools within your MCP environment.

A static MCP server URL is provided for all clients:

```text
https://mcp.pipedream.net/v2
```

## Features
- **Unified MCP integration**
  - Single static MCP server URL usable by all supported clients.
  - Authentication handled when adding the server to the application.
  - 57 actions exposed as MCP tools (partial list below).

- **On-page SEO analysis**
  - **Parse Page Content with OnPage**  
    - Parse the content of any web page.  
    - Return structured content for further processing or analysis.
  - **Get Crawled Pages with OnPage**  
    - Retrieve page-specific data for crawled URLs.  
    - Includes detailed information on how well pages are optimized for search.
  - **Create OnPage Task**  
    - Programmatically create OnPage tasks.  
    - Retrieve detailed on‑page optimization information at scale.

- **Local and business listings data**
  - **Search Business Listings**  
    - Query business entities listed on Google Maps.  
    - Useful for local SEO, lead research, and competitive analysis.

- **Search engine results (SERP) data**
  - **Get Yahoo Organic Results**  
    - Retrieve Yahoo organic search results for specified keywords.
  - **Get Top SERP Results**  
    - Obtain top‑ranking pages for given keywords.  
    - Support for competitor and ranking analysis scenarios.

- **Reviews and reputation data**
  - **Get Trustpilot Reviews**  
    - Fetch Trustpilot business reviews and ratings.  
    - Helps in monitoring and analyzing brand reputation.
  - **Get TripAdvisor Reviews**  
    - Fetch TripAdvisor business reviews and ratings.  
    - Especially relevant for hospitality and travel‑related businesses.

- **Technology stack detection**
  - **Get Technologies Domain List**  
    - Identify technologies used by a domain (e.g., CMS, analytics tools, frameworks).

- **Sentiment and brand monitoring**
  - **Get Sentiment Analysis**  
    - Analyze sentiment of brand mentions and content.  
    - Useful for reputation and campaign performance monitoring.

- **Backlinks and referring domains**
  - **Get Referring Domains**  
    - Retrieve a detailed overview of referring domains pointing to a specified target.  
    - Supports backlink analysis and link profile evaluation.

- **Keyword and ranking data**
  - **Get Ranked Keywords**  
    - Action exists for retrieving ranked keywords (description truncated in source but indicates keyword ranking retrieval capabilities).

- **Client configuration**
  - "Configure DataForSEO" flow to connect a DataForSEO account.  
  - Sign-in and account selection inside the hosting platform (Pipedream/Workday environment).  
  - Additional configuration guidance provided via a dedicated configuration page.

## Integrations
- Designed for use with MCP‑compatible chat clients and tools.  
- Accessible via the MCP server endpoint: `https://mcp.pipedream.net/v2`.

## Pricing
No pricing information is provided in the available content.
