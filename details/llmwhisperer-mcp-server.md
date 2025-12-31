# LLMWhisperer MCP Server

## Overview
LLMWhisperer MCP Server is an MCP-compatible service that optimizes how complex document data is presented to large language models. It focuses on converting and structuring content from PDFs and scanned documents so LLMs can process and understand it more effectively within MCP-enabled applications.

- **Category:** Content Extraction & Summarization MCP Server
- **Provider / Brand:** LLMWhisperer (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable for all clients.
- Authentication handled when adding the server to your MCP-compatible application.
- Works with multiple chat / MCP clients (configuration guidance available on the Pipedream configuration page).

### Document Text Extraction
- **Extract Text**
  - Converts PDF and scanned documents into text format.
  - Produces text optimized for use by LLMs.
  - Supports asynchronous processing (conversion can be performed in async mode).

### Asynchronous Processing Support
- **Get Status**
  - Retrieves the status of the “whisper” conversion process.
  - Intended for workflows where document conversion is run asynchronously.
- **Retrieve Extracted Text**
  - Retrieves the extracted text after the conversion has completed.
  - Used in conjunction with async conversion and status checks.

### Search & Highlighting
- **Highlight Locations**
  - Generates highlight locations (positions) for a given search term within a processed document.
  - Useful for pinpointing and referencing relevant sections of text inside larger documents.

### Available Tools (Actions)
The MCP server exposes the following actions as tools:
1. `extract-text` – Convert PDF/scanned documents to LLM-ready text.
2. `get-status` – Check the status of an ongoing asynchronous conversion.
3. `retrieve-text` – Retrieve the final extracted text once conversion is complete.
4. `highlight-locations` – Compute highlight locations for search terms in the document.

## Use Cases
- Preparing large, complex PDF or scanned documents for LLM-based question answering.
- Building MCP chat clients that need async document conversion and status polling.
- Implementing search-with-highlighting experiences over long documents for LLM-powered apps.

## Pricing
No pricing information is provided in the available content. Users should refer to the main LLMWhisperer or Pipedream site for current pricing details, if applicable.