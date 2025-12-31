# mcp-pandoc

**Category:** Document Management MCP Servers  
**Repository:** https://github.com/vivekVells/mcp-pandoc

## Overview
mcp-pandoc is an MCP (Model Context Protocol) server that exposes Pandoc-based document format conversion as tools usable by LLM-powered agents. It focuses on seamless conversion between multiple document formats, including Markdown, HTML, PDF, DOCX, CSV, and others supported by Pandoc.

## Features
- **MCP server integration**
  - Implements an MCP server interface for use with LLM agents and MCP-compatible clients.
  - Exposes document conversion as callable tools within an agent workflow.

- **Pandoc-based conversion**
  - Uses Pandoc as the underlying engine for document transformations.
  - Inherits broad format support from Pandoc (e.g., Markdown, HTML, PDF, DOCX, CSV, and many other text and document formats).

- **Multi-format support**
  - Converts between common authoring and publishing formats (e.g., Markdown ↔ HTML, Markdown → PDF/DOCX, etc.).
  - Designed to handle a wide range of formats that Pandoc supports, not limited to those explicitly listed.

- **Developer tooling and configuration**
  - Dockerfile included for containerized deployment.
  - `pyproject.toml`-based Python project configuration.
  - Example configurations under `examples/defaults`.
  - Testing and demo directories (`tests`, `testing`, `demo`) to illustrate usage and ensure reliability.
  - CHEATSHEET and CONTRIBUTING guides included in the repository.

- **Open source**
  - Distributed via GitHub with a LICENSE file (exact license details available in the repository).

## Use Cases
- Integrating document conversion into LLM workflows.
- Building agents that can ingest one document format and output another.
- Automating report generation or transformation across Markdown, HTML, PDF, DOCX, CSV, and compatible formats.

## Pricing
- Not specified in the provided content. The project appears to be an open-source repository; for exact licensing and usage terms, refer to the LICENSE file in the repository.