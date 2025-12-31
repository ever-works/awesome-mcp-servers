# Docs MCP Server

**Category:** AI Integration – MCP Servers  
**Tags:** documentation, RAG, open‑source

## Overview
Docs MCP Server is a free, open‑source Model Context Protocol (MCP) server that indexes and serves version‑aware software documentation to AI tools. It can run locally or be self‑hosted and is designed to reduce hallucinations by letting MCP‑compatible clients query an up‑to‑date, version‑specific documentation corpus.

## Features

### Documentation Ingestion
- Scrapes and indexes documentation from multiple sources:
  - Public or private documentation websites
  - GitHub repositories
  - Package registries (e.g., npm, PyPI)
  - Local directories

### Processing & Indexing
- Semantically chunks documentation content for better retrieval.
- Generates vector embeddings for indexed content.
- Builds a searchable corpus optimized for question‑answering.
- Maintains version awareness so answers can be tied to specific software versions.

### Search & Retrieval
- Exposes powerful search over the entire documentation corpus.
- Supports semantic search using generated embeddings.
- Designed to return accurate, version‑specific documentation snippets to AI tools.

### MCP Integration
- Implements the Model Context Protocol (MCP).
- Integrates with MCP‑compatible clients, including:
  - Claude
  - Cline
  - Roo
- Provides AI tools with structured, documentation‑grounded context to reduce hallucinations.

### Deployment & Hosting
- Runs locally on a developer machine.
- Can be self‑hosted in your own infrastructure.

### Embedding Provider Support
- Works with multiple embedding providers, including:
  - OpenAI‑compatible APIs
  - Google Gemini / Vertex
  - Azure OpenAI
  - AWS Bedrock

### Authentication & Security
- Optional enterprise authentication via OAuth2/OIDC.

### User Interface
- Includes a web UI for interacting with and managing the documentation corpus.

### Licensing & Openness
- Free to use.
- Open‑source codebase.

## Pricing
- Free and open‑source (no paid plans are described).