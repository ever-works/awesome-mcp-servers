# ChatPDF MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Brand:** ChatPDF  
**URL:** https://mcp.pipedream.com/app/chatpdf

An MCP server that integrates the ChatPDF Backend API into MCP-compatible clients, enabling extraction of information from PDFs and conversational interaction with their contents.

---

## Features

### MCP Server Integration
- Provides a static MCP server endpoint usable by any compatible client:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Authentication handled when adding the server to your application.
- Configuration guides available for different chat clients (e.g., ChatGPT / OpenAI) via the Pipedream configuration pages.

### PDF Ingestion
- **Add PDF via URL**
  - Adds a PDF from a publicly accessible URL to ChatPDF.
  - Returns a **source ID** that can be used for subsequent interactions and operations.

### Conversational PDF Interaction
- **Chat With PDF**
  - Sends messages to interact with a specific PDF using its source ID.
  - Supports single or multiple messages, enabling complex and multi-step queries about the PDF’s contents.
  - Uses the ChatPDF backend API to extract and summarize information from the document.

### PDF Management
- **Delete PDF**
  - Deletes one or more PDFs from ChatPDF using their source IDs.
  - Helps manage and clean up stored document sources.

### Tooling / Actions
- Exposes **3 actions as MCP tools**:
  1. Add PDF via URL
  2. Chat With PDF
  3. Delete PDF
- Designed for use inside MCP-compatible clients via Pipedream’s MCP infrastructure.

---

## Use Cases
- Upload and register PDFs via URL, then query them conversationally from within an MCP-enabled chat client.
- Extract specific information, summaries, or answers from PDFs using natural language.
- Manage the lifecycle of documents (add, interact, delete) directly through MCP tools.

---

## Pricing

No pricing information is provided in the available content. Users may need to refer to ChatPDF or Pipedream directly for details on usage limits or costs.