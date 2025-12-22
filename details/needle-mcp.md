# Needle MCP

## Overview
Needle MCP is a production-ready Model Context Protocol (MCP) server for Needle that adds retrieval‑augmented generation (RAG) and long‑term memory capabilities to LLM-based agents. It lets you search and retrieve information from your own documents so models can answer questions using your private data.

## Features
- **MCP server for Needle**
  - Implements a server compatible with the Model Context Protocol for use in Needle-based agents.
- **Retrieval-Augmented Generation (RAG)**
  - Enables agents to search across your own documents and use retrieved content as context for language model responses.
- **Long-term memory for LLMs**
  - Designed to provide persistent knowledge and context, so agents can reference prior or stored information rather than relying only on short prompts.
- **Document search and retrieval**
  - Supports querying and fetching relevant data from user-provided document collections.
- **Agent-building support**
  - Intended to be used as a backend component for building and running AI agents with richer context.
- **Containerization support**
  - Includes a `Dockerfile` for containerized deployment.
- **Python-based project**
  - Managed with `pyproject.toml` and `uv.lock`, indicating a modern Python packaging and dependency setup.
- **Smithery integration metadata**
  - Provides a `smithery.yaml` configuration and is published on Smithery for easier MCP server discovery and usage.

## Pricing
- **Free & open source**
  - Distributed via a public GitHub repository; usage is governed by the license found in the `LICENSE` file of the project.

## Links
- **Source code / documentation**: https://github.com/needle-ai/needle-mcp
