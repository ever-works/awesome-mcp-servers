# PDFMonkey MCP Server

## Overview
PDFMonkey MCP Server is an MCP (Model Context Protocol) server integration for PDFMonkey that allows AI agents and compatible chat clients to generate and manage PDFs via the PDFMonkey document generation API.

- **Category:** Document Management MCP Servers  
- **Vendor/Brand:** PDFMonkey  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **PDF generation via PDFMonkey API**  
  Enables AI agents and MCP-compatible applications to generate PDFs using PDFMonkey’s document generation capabilities.

- **MCP server integration**  
  Exposes PDFMonkey functionality as tools/actions through the MCP protocol so chat clients and AI-powered apps can call them programmatically.

- **Static server endpoint**  
  Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all clients.

- **Account-based configuration**  
  Requires connecting a PDFMonkey account and selecting the appropriate client configuration before use.

- **Authentication at client level**  
  Authentication occurs when adding the MCP server to your application, allowing secure access to PDFMonkey resources.

- **Tool/action discovery**  
  The server supports listing and loading available tools/actions, which can then be invoked by AI agents or chat clients.

- **Chat client integration guidance**  
  Provides instructions per chat client type (via the configuration page) for adding and configuring the MCP server.

## Pricing
No pricing information is provided in the available content.

## Links
- Product page: https://mcp.pipedream.com/app/pdfmonkey
- Configuration page: /configuration (relative to the Pipedream MCP site)
- MCP server URL: `https://mcp.pipedream.net/v2`