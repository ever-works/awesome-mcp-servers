# PDF.co MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Slug:** `pdfco-mcp-server`  
**Brand:** PDF.co  
**Source:** https://mcp.pipedream.com/app/pdf_co

## Description
PDF.co MCP Server exposes PDF.co’s PDF, spreadsheet, and barcode data extraction and processing APIs as tools for AI agents and chat clients via the Model Context Protocol (MCP). It enables automated document processing, conversion, and analysis workflows directly from compatible AI applications.

## MCP Server Endpoint
- **Server URL:** `https://mcp.pipedream.net/v2`  
  This is a static URL shared by all clients; authentication is handled when adding the server to your application.

## Features

### General Capabilities
- Access PDF.co’s PDF, spreadsheet, and barcode processing APIs through MCP.
- Integrate with AI chat clients (e.g., ChatGPT via OpenAI) as MCP tools.
- Supports workflows requiring data extraction, transformation, and document security operations.
- Part of an ecosystem with 300+ integrations (via PDF.co platform).

### Available Tools / Actions (17 total)
The following actions are exposed as MCP tools:

1. **PDF to Anything Converter**  
   - Convert PDFs to: CSV, JSON, plain text, XLS, XLSX.  
   - Useful for structured and unstructured data extraction from PDFs.

2. **PDF Split Text Search**  
   - Split a PDF based on text search results.  
   - Allows splitting where specific text appears in the document.

3. **PDF Split by Page Index**  
   - Split PDF by page indices.  
   - Create multiple PDFs from one source based on page ranges.

4. **Search Text in PDF**  
   - Search for text within a PDF and return coordinates of matches.  
   - Supports regular expressions for advanced pattern matching.

5. **Remove PDF Security**  
   - Remove security from PDF files (where permitted).  
   - Simplifies subsequent processing or editing.

6. **PDF Merge**  
   - Merge two or more PDF files into a new, single PDF.  
   - Combine documents programmatically.

7. **PDF Info Reader**  
   - Retrieve detailed PDF document information:  
     - Document properties.  
     - Security permissions.  
   - Useful for inspecting metadata and access settings.

8. **PDF Find Table**  
   - AI-powered document analysis for table detection.  
   - Scans documents for tables and returns:  
     - Arrays of tables per page.  
     - Coordinates of detected tables.  
     - Information about detected columns.

9. **Add PDF Security**  
   - Add security settings to PDF files.  
   - Configure document protection and permissions.

10. **HTML to PDF Converter**  
    - Convert HTML code snippets to fully featured PDF documents.  
    - Supports generating PDFs from HTML content or templates.

11. **Document Toggle Searchable**  
    - Toggle between text-searchable and text-unsearchable formats for:  
      - PDF files.  
      - Scanned JPG, PNG images.  
    - Enables OCR to create searchable PDFs from scans or to remove text-searchability when needed.

> Note: The page states **“17 actions available as tools”**; only the actions explicitly listed in the provided content are included above.

## Integration & Configuration
- **Connection:** Requires signing in on Pipedream MCP to connect a PDF.co account and manage accounts.
- **Client Setup:**  
  - Use the static MCP server URL when adding PDF.co MCP Server to supported chat clients.  
  - Guides are available for specific clients such as ChatGPT (OpenAI).  
  - Additional configuration details are available on the MCP configuration page: https://mcp.pipedream.com/configuration

## Pricing
- No pricing information is provided in the supplied content. Use the PDF.co or Pipedream documentation/website for current pricing and plan details.
