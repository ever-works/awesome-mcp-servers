# TinyURL MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** TinyURL  
**Source:** https://mcp.pipedream.com/app/tinyurl

## Overview
TinyURL MCP Server is an MCP-compatible integration that connects applications to TinyURL’s link management platform. It enables programmatic creation, management, and analysis of shortened links (including branded links) directly from MCP-aware clients.

## Features
- **Static MCP endpoint**  
  - Single MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to the application.

- **Link creation**  
  - Create new shortened TinyURL links.  
  - Supports use with TinyURL premium accounts for branded and campaign links (where available in the underlying TinyURL account).

- **Link metadata management**  
  - Update metadata of existing TinyURL links.  
  - Suitable for maintaining accurate, up‑to‑date link information (e.g., titles, descriptions, tags, or other supported metadata fields).

- **Analytics and reporting**  
  - Retrieve analytics for specific TinyURL links.  
  - Provides total click counts.  
  - Includes geographic breakdowns of clicks.  
  - Includes device-type breakdowns (e.g., mobile vs desktop, where supported).

- **MCP tools / actions**  
  - Exposes 3 actions as tools within MCP-compatible clients:  
    - `Create Shortened Link`  
    - `Update Link Metadata`  
    - `Retrieve Link Analytics`

## Use Cases
- Generate shortened or branded URLs from within chat or other MCP-enabled applications.  
- Run link campaigns and adjust metadata without leaving the client.  
- Monitor link performance (clicks, geography, devices) directly through MCP tools.

## Pricing
No specific pricing details for the TinyURL MCP Server are provided in the source content. (TinyURL premium account references indicate that some capabilities depend on a paid TinyURL plan, but no plan names or prices are listed.)