# Typless MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Slug:** `typless-mcp-server`

## Overview
Typless MCP Server exposes the Typless AI-powered invoice OCR as a REST API endpoint compatible with MCP (Model Context Protocol) tools. It enables applications and chat clients to perform invoice OCR and document data extraction via a standardized MCP server URL.

- **Product type:** MCP server / API integration
- **Primary use case:** OCR and data extraction from invoices and similar documents
- **Provider / Platform:** Typless via Pipedream Connect
- **Endpoint base URL:** `https://mcp.pipedream.net/v2`

## Features
- **AI-powered invoice OCR**  
  - Extracts structured data from invoices using optical character recognition and AI.
- **REST API interface**  
  - Accessed via a static REST endpoint that works across MCP-compatible clients.
- **Static MCP server URL**  
  - Single URL (`https://mcp.pipedream.net/v2`) used by all supported clients.
- **Client-agnostic integration**  
  - Designed to be added to different chat clients and MCP-compatible applications.
- **Authentication at configuration time**  
  - Authentication is performed when adding the server to an application (details handled during client configuration).
- **Configuration documentation**  
  - A dedicated configuration page (via Pipedream) explains how to connect the MCP server to supported clients.

## Integration & Usage
- Add the MCP server to supported chat clients or apps using the provided static URL.
- Authenticate as part of the server-add / configuration flow in your client.
- Use the MCP tools in your client to call Typless for invoice OCR and document processing.

## Pricing
- The provided content does not list any pricing or plans for the Typless MCP Server.

## Links
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Configuration page:** `/configuration` (on Pipedream)  
- **Pipedream Connect:** https://pipedream.com/connect  
- **Terms:** https://pipedream.com/terms  
- **Privacy Policy:** https://pipedream.com/privacy
