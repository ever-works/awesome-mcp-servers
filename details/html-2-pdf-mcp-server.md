# HTML 2 PDF MCP Server

## Overview
HTML 2 PDF MCP Server is an MCP (Model Context Protocol) server by Pipedream that converts HTML content into PDF documents. It’s designed to be used as a tool within compatible chat clients or applications to automate HTML-to-PDF generation.

## Features
- **HTML to PDF conversion**: Transforms HTML content into PDF files.
- **MCP-compatible server**: Exposed as an MCP server that can be added to MCP-enabled apps and chat clients.
- **Static server URL**: Uses a single static endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic usage**: The same server URL works across different MCP-compatible clients.
- **Authentication at integration time**: Authentication is handled when you add the server to your application (not tied to a per-client URL).
- **Configurable in Pipedream**: Can be configured via Pipedream’s "Configure HTML 2 PDF" interface.
- **Intended for workflows**: Suitable for use inside automated workflows (e.g., in Pipedream environments) where HTML must be converted to PDF.

## Setup & Integration
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible app or chat client.
- Authenticate during the add/integration step.
- Optionally refer to the full configuration documentation on Pipedream’s Configuration page.

## Category
- Web & App Development
- Document Management MCP Servers

## Tags
- document-conversion
- pdf
- html

## Pricing
The provided content does not specify any pricing or plans for the HTML 2 PDF MCP Server.