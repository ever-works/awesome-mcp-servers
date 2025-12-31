# Uploadcare MCP Server

**Category:** File Management MCP Servers  
**Tags:** file-upload, media-management, cdn

## Overview
Uploadcare MCP Server is an integration that exposes Uploadcare’s APIs to MCP-compatible clients. It enables file uploads, storage, processing, and delivery within chat or agent environments using a unified MCP server URL.

## Features
- **MCP Server Integration**
  - Provides a static MCP server endpoint usable by any compatible client: `https://mcp.pipedream.net/v2`.
  - Authentication handled when adding the server to your application / client.

- **File Uploads**
  - Connects to Uploadcare’s API for handling file uploads from MCP clients.

- **File Storage**
  - Uses Uploadcare’s backend to store uploaded files for later access and processing.

- **File Processing**
  - Integrates with Uploadcare’s processing capabilities (e.g., transformations and media processing) through the MCP server.

- **Content Delivery**
  - Delivers stored and processed files via Uploadcare’s CDN-enabled delivery infrastructure.

- **Client-Agnostic Configuration**
  - Single static server URL works across different MCP-compatible chat clients.
  - Configuration instructions available per client type via the linked configuration page.

## Requirements
- Uploadcare account.
- Uploadcare API key obtained from uploadcare.com.

## Pricing
- The page notes that you can sign up at uploadcare.com for a free API key.
- No additional or detailed pricing tiers or plans are specified in the provided content.