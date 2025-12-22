# Elasticsearch MCP Server

**Type:** Open-source MCP server implementation  
**Category:** MCP Servers / Developer Tools  
**Source:** https://github.com/cr7258/elasticsearch-mcp-server

## Description
Elasticsearch MCP Server is a Model Context Protocol (MCP) server that exposes Elasticsearch and OpenSearch capabilities to MCP-compatible clients. It enables search, indexing, and general cluster interactions through standardized MCP tools.

## Features
- **MCP server implementation**
  - Implements a Model Context Protocol (MCP) server for search and indexing use cases.
  - Provides tools that allow MCP clients to interact with search backends.

- **Elasticsearch integration**
  - Connects to Elasticsearch clusters.
  - Supports search and indexing interactions via MCP tools (as described in the project summary).

- **OpenSearch integration**
  - Supports interaction with OpenSearch in addition to Elasticsearch.

- **Configuration & environment setup**
  - `.env.example` for environment variable configuration.
  - `server.json` for MCP server configuration/registration.

- **Container-based examples**
  - `docker-compose-elasticsearch.yml` for running Elasticsearch in a containerized environment.
  - `docker-compose-opensearch.yml` for running OpenSearch in a containerized environment.

- **Implementation details & tooling**
  - Python-based project (managed via `pyproject.toml`).
  - `Makefile` for common development/build tasks.
  - GitHub Actions workflows under `.github/workflows` for CI or automation.

- **Client integration example**
  - `mcp_client/spring-ai` directory suggests example or reference integration with Spring AI as an MCP client.

- **Project governance & contribution**
  - `CONTRIBUTING.md` describing contribution guidelines.
  - `cliff.toml` configuration for managing changelogs or releases.

## Pricing
- **Open-source**: Free to use under the terms of the license included in the repository (`LICENSE` file).

## License
- Distributed under an open-source license (see the `LICENSE` file in the repository for exact terms).