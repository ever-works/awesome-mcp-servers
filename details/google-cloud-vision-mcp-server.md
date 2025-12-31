# Google Cloud Vision MCP Server

## Overview
The Google Cloud Vision MCP Server exposes Google Cloud Vision API capabilities through the Model Context Protocol (MCP), enabling image recognition and analysis from compatible MCP clients.

**Category:** Media Processing MCP Servers  
**Provider / Brand:** Google Cloud (via Pipedream)  
**MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server**
  - Single static MCP server URL usable from multiple clients.
  - Authentication handled when adding the server to your MCP-compatible application.

- **Google Cloud Vision API integration**
  - Uses Google Cloud Vision’s pre-trained REST and RPC models for image recognition.
  - Works with both local image files and remote image URLs (where supported by the action).

- **Available tools (actions)**
  1. **Detect Text in Image**  
     - Detects text within an image.  
     - Supports local images and remote image URLs.  
     - Useful for OCR-style extraction of text content from images.

  2. **Detect Logos in Image**  
     - Detects logos present in an image.  
     - Supports both local and remote image files.

  3. **Detect Labels in Image**  
     - Performs general feature detection on an image.  
     - Returns labels describing objects, scenes, and other visual concepts.  
     - Supports local and remote image files.

- **Client integration**
  - Compatible with MCP-enabled chat clients (e.g., ChatGPT with MCP support).  
  - Documentation and configuration guidance available via Pipedream’s configuration pages.

## Configuration
- **Server URL:** `https://mcp.pipedream.net/v2` (static for all clients).  
- **Authentication:** Performed after adding the server to your application; requires connecting a Google Cloud Vision account through Pipedream.

## Pricing
The provided content does not include any pricing or plan details for the Google Cloud Vision MCP Server. Users should refer to Pipedream and Google Cloud Vision official documentation or consoles for up-to-date pricing information.