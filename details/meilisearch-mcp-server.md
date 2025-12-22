# Meilisearch MCP Server

## Overview
Meilisearch MCP Server is an open-source Model Context Protocol (MCP) server that connects large language model (LLM) interfaces and agents to a Meilisearch instance. It exposes Meilisearch’s full-text and semantic search capabilities so agents can index and query content programmatically.

Source: https://github.com/meilisearch/meilisearch-mcp

## Features
- **Model Context Protocol server** for Meilisearch, enabling LLM-based tools and agents to interact with a Meilisearch instance.
- **Full-text search integration**: allows agents to query Meilisearch’s full-text search API.
- **Semantic search integration**: supports using Meilisearch’s semantic search API.
- **Indexing operations**: enables agents to index content into Meilisearch (e.g., adding/updating searchable data).
- **Querying operations**: allows agents to retrieve and search indexed content via Meilisearch APIs.
- **LLM interface support**: specifically designed to be used through LLM interfaces that implement MCP.
- **Python package distribution**: available on PyPI as `meilisearch-mcp`.
- **Docker support**: includes a `Dockerfile` for containerized deployment.
- **Automated workflows & tests**: repository includes GitHub workflows and tests to support development and reliability.

## Technical Details
- **Project type**: MCP server implementation for Meilisearch.
- **Ecosystem**: integrates with Meilisearch (self-hosted or cloud) and MCP-compatible LLM clients.
- **Language**: implemented in Python (distributed via PyPI).
- **License**: Open-source (license file included in the repository; specific license type not detailed in the provided content).

## Pricing
- **Pricing information**: Not specified in the provided content. The project is published as an open-source repository on GitHub; refer to the repository and license for usage terms.