# Docnify MCP Server

**Category:** Document Management MCP Servers  
**Brand:** Docnify  
**Slug:** `docnify-mcp-server`  
**Source:** https://mcp.pipedream.com/app/docnify

## Overview
Docnify MCP Server is an MCP-compatible server that exposes Docnify’s document signing capabilities to MCP-enabled agents and applications. It allows clients (such as chat-based agents) to interact with Docnify for e-signature and contract workflows via a standardized MCP endpoint.

## Features
- **Document signing integration**
  - Provides Docnify’s e-signature functionality to MCP-compatible agents and apps.
  - Supports workflows involving contracts and other signable documents.
- **Standard MCP endpoint**
  - Static server URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication handled when you add the server to your application.
- **Multi-client compatibility**
  - Designed to be added to different chat clients or MCP-compatible tools.
  - Central configuration flow: connect a Docnify account, then select a client.
- **File storage support**
  - Integrates with file storage as part of document handling (as indicated by the interface section "File Storage").
- **Configurable connection**
  - “Configure Docnify” flow to connect your Docnify account.
  - Account checking and validation before use.
- **Tool-based actions (MCP tools)**
  - Exposes “available tools” (actions) over MCP for document-related operations (exact tools not listed but surfaced via the MCP server).

## Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible application or chat client.
- Authenticate with your Docnify account as prompted.
- Use the exposed tools to manage document signing and related workflows.

## Pricing
The provided content does not list any pricing or plans for Docnify MCP Server.