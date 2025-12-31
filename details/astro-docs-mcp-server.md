# Astro Docs MCP Server

## Overview
Astro Docs MCP Server is an open Model Context Protocol (MCP) server that provides structured, machine-readable access to the official Astro framework documentation at `https://mcp.docs.astro.build/mcp`. It enables compatible AI tools and editors to query and use the latest Astro docs programmatically.

- **Type:** Open-source MCP server / developer tool
- **Ecosystem:** Astro framework, web development
- **Source Code:** https://github.com/withastro/docs-mcp
- **MCP Endpoint:** https://mcp.docs.astro.build/mcp

## Features
- **MCP-compliant server**
  - Implements the Model Context Protocol to connect language models to external data.
  - Designed for integration with MCP-capable AI tools and editors.

- **Access to Astro documentation**
  - Provides structured access to Astro’s official framework documentation.
  - Covers topics such as features, APIs, and best practices for Astro.
  - Intended to keep responses aligned with the latest published docs.

- **AI tool integration**
  - Usable by LLM-powered tools such as:
    - Cursor
    - VS Code (with MCP-capable extensions/clients)
    - Claude
    - ChatGPT
    - Windsurf
  - Supports use cases like code generation assistance, Q&A, and inline documentation help.

- **Structured querying of docs**
  - Exposes documentation in a structured form suitable for automated querying by LLMs.
  - Helps tools retrieve relevant sections for answering questions about Astro usage and configuration.

- **Open-source implementation**
  - Repository includes configuration files (e.g., `deno.json`, `package.json`, `netlify.toml`).
  - Can be inspected, self-hosted, or adapted for custom use cases.

## Category
- Documentation & Learning Resources
- Tags: documentation, framework, web-development

## Pricing
- No pricing information is provided in the available content.
- The project is hosted as a public open-source GitHub repository; usage terms and licensing should be confirmed in the repository itself.