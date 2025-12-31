# Document Loader MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Tags:** content-extraction, document-processing, llm-integration  
**Website:** https://awslabs.github.io/mcp/servers/document-loader-mcp-server

## Description
Document Loader MCP Server is a Model Context Protocol (MCP) server that enables LLMs to parse and extract content from external documents. It supports multiple office and image formats and exposes tools that MCP-compatible clients can call for document loading and analysis.

## Features
- **Multi-format document support**
  - PDF text extraction using `pdfplumber`
  - Word document processing: convert DOCX/DOC files to Markdown (via `markitdown`)
  - Excel spreadsheet reading: parse XLSX/XLS and convert to Markdown
  - PowerPoint processing: extract content from PPTX/PPT presentations
  - Image loading: open and display multiple image formats (PNG, JPG, GIF, BMP, TIFF, WEBP)

- **MCP tools**
  - `read_document`
    - Extracts content from documents by specifying `file_path` and `file_type`
    - Supported `file_type` values: `pdf`, `docx`, `doc`, `xlsx`, `xls`, `pptx`, `ppt`
  - `read_image`
    - Loads image files for LLM viewing and analysis

- **Logging configuration**
  - `FASTMCP_LOG_LEVEL` environment variable controls logging level
  - Supported levels: `ERROR`, `INFO`, `DEBUG`

- **Developer-focused setup**
  - Installable via `uvx` (Astral’s `uv` toolchain)
  - Python 3.10+ required
  - Development workflow via `uv sync` and editable install (`uv pip install -e .`)
  - Test execution with `uv run pytest`, including coverage support (`uv run pytest --cov=awslabs.document_loader_mcp_server`)

- **Client integration examples**
  - Configuration snippets for MCP clients (e.g., typical `mcpServers` JSON block with command `uvx` and package `awslabs.document-loader-mcp-server@latest`)
  - Example integration for Amazon Q Developer CLI via `~/.aws/amazonq/cli-agents/default.json`

## Prerequisites
- `uv` installed (from Astral or GitHub instructions)
- Python 3.10 or newer (e.g., via `uv python install 3.10`)

## Technical Setup (High-Level)
- Configure an MCP client to run the server with:
  - Command: `uvx`
  - Args: `["awslabs.document-loader-mcp-server@latest"]`
  - Optional env: `{ "FASTMCP_LOG_LEVEL": "ERROR" }`
  - Enable/disable via `disabled` flag and `autoApprove` list in client configuration

## Pricing
No pricing information is provided in the available content (likely open-source / no listed plans).