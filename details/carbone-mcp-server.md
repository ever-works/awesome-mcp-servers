# Carbone MCP Server

**Category:** Document Management MCP Servers  
**Slug:** carbone-mcp-server  
**Brand:** Carbone

## Description
Carbone MCP Server is an MCP-compatible service that generates reports by transforming JSON data into various document formats. It is designed to integrate with chat clients and other MCP-enabled applications via a static MCP server URL.

## Features
- **JSON-to-document transformation**: Converts JSON data into rich document outputs using Carbone templates.
- **Multi-format report generation**:
  - PDF
  - DOCX (Microsoft Word)
  - XLSX (Microsoft Excel)
  - PPTX (Microsoft PowerPoint)
  - ODS (OpenDocument Spreadsheet)
  - Additional document formats supported by Carbone
- **MCP-compatible server**: Exposes Carbone as a Model Context Protocol (MCP) server for use with compatible tools and chat clients.
- **Static MCP server endpoint**: Single server URL usable across clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client authentication**: Authentication is handled when adding the server in each client/application, allowing the same server URL to be reused.
- **Integration with multiple clients**: Can be added to different chat clients or apps by following client-specific setup instructions.

## Configuration
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding Carbone MCP Server to an MCP-compatible client.
- Authentication and client selection are performed during setup in the target application.

## Pricing
- Not specified in the provided content.