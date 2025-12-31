# CraftMyPDF MCP Server

Auto-generate PDF documents from reusable templates using a drag-and-drop editor and a simple API, exposed as an MCP (Model Context Protocol) server via Pipedream.

## Overview
- **Type:** MCP Server (document generation / PDF automation)
- **Category:** Document Management MCP Servers
- **Provider / Brand:** CraftMyPDF (via Pipedream)
- **Purpose:** Automate creation and management of PDFs and images from templates within MCP-driven workflows and chat-based tools.
- **MCP Server URL:** `https://mcp.pipedream.net/v2` (static for all clients; authentication handled on client/app side)

## Features

### MCP Integration & Configuration
- Static MCP server URL usable across compatible MCP clients.
- Supports configuration and connection of CraftMyPDF accounts via Pipedream.
- Can be added to different chat clients (e.g., ChatGPT / OpenAI) with provided configuration guidance.

### Template-Based PDF Generation
- **Reusable templates:** Generate PDF documents from reusable templates designed in CraftMyPDF.
- **Drag-and-drop editor:** Use a visual editor (in CraftMyPDF) to design templates that can then be automated via MCP tools.

### Available MCP Tools (Actions)
Four actions are exposed as tools through the MCP server:

1. **Merge PDF**
   - Create a new PDF file by merging multiple template-based PDFs.
   - Combines multiple PDFs into a single document.

2. **Create PDF**
   - Generate a new PDF document from a template.
   - Uses CraftMyPDF’s API behind the scenes.

3. **Create Image**
   - Generate a new image (e.g., from templates/configurations defined in CraftMyPDF).

4. **Create Editor Session**
   - Create a new PDF editor session.
   - Returns a PDF editor URL that can be embedded in an `<iframe>` in your application.

## Use Cases
- Automated document generation from templates (invoices, reports, certificates, etc.) within chat/MCP workflows.
- Merging multiple generated PDFs into a single deliverable file.
- Embedding a PDF editor experience in web applications via editor sessions.
- Generating images programmatically as part of document or media workflows.

## Pricing
- No pricing details are provided in the available content for the CraftMyPDF MCP Server or CraftMyPDF usage. Consult the CraftMyPDF or Pipedream websites for current pricing information.