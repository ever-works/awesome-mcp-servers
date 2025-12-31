# DocumentPro MCP Server

## Overview
DocumentPro MCP Server is an MCP server that connects to DocumentPro’s AI-powered data extraction platform. It enables automated parsing of invoices and other documents from PDFs and images into structured formats such as Excel via MCP tools.

## Features
- **MCP-compatible server**: Exposes DocumentPro’s capabilities as an MCP server for integration with MCP-enabled applications and chat clients.
- **AI-powered data extraction**: Uses AI parsers to extract structured data from documents.
- **Invoice processing**: Specialized support for extracting invoice data from PDFs and images.
- **Document-to-structured-format conversion**: Converts parsed document data into structured outputs such as Excel and other tabular formats.
- **PDF and image support**: Handles both PDF files and image-based documents for OCR and parsing.
- **Static server endpoint**: Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for every client.
- **Per-client authentication**: Authentication occurs when adding the server to each application or client, allowing secure multi-client use.
- **Integration with chat clients**: Can be added to compatible chat clients to trigger data extraction workflows through conversational interfaces.
- **Tool-based workflows**: Provides MCP tools/actions (loaded dynamically) for performing extraction operations and related document-processing tasks.

## Technical Details
- **Server URL**: `https://mcp.pipedream.net/v2`
- **Hosting / provider**: Delivered via Pipedream’s MCP infrastructure.
- **Authentication**: Handled when connecting the server to your app or chat client.

## Pricing
Pricing information is not provided in the available content. Users should refer to the linked DocumentPro or Pipedream pages for current pricing details.