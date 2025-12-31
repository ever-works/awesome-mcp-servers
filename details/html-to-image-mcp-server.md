# HTML to Image MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** Pipedream  
**Website:** https://mcp.pipedream.com/app/html_to_image

## Overview

HTML to Image MCP Server is a Pipedream-hosted Model Context Protocol (MCP) server that provides a flexible API for taking website screenshots and converting HTML/CSS into image or PDF files. It is designed for use in Pipedream workflows and can be integrated with MCP-compatible chat clients such as ChatGPT.

## Features

### MCP Server & Integration
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`
- Works with multiple MCP-compatible chat clients (e.g., ChatGPT via OpenAI)
- Authentication handled when adding the server to your application
- Configuration guidance available via a dedicated configuration page on Pipedream

### Conversion & Screenshot Tools
The server exposes 4 actions as tools:

1. **Convert URL to PDF**
   - Create a PDF from a given URL
   - Intended for capturing web pages as PDF documents

2. **Convert URL to Image**
   - Capture a screenshot from a URL
   - Useful for generating image snapshots of live web pages

3. **Convert HTML to PDF**
   - Create a PDF file from raw HTML content
   - Supports workflows where HTML/CSS is generated dynamically, then rendered as a PDF

4. **Convert HTML to Image**
   - Create an image from HTML content
   - Enables rendering of custom HTML/CSS layouts to image formats

### Usage Context
- Built to be used inside Pipedream Connect workflows
- Suitable for web and app development tasks requiring automated rendering of web content to images or PDFs

## Pricing

No pricing information is provided in the available content. Users must refer to Pipedream’s main site or the HTML to Image service documentation for current pricing details.