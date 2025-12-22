# Dify MCP Server

## Overview
Dify MCP Server is a simple implementation of a Model Context Protocol (MCP) server that lets MCP-compatible clients invoke and orchestrate [Dify](https://github.com/langgenius/dify) workflows as tools.

## Features
- **MCP server for Dify workflows**  
  - Exposes Dify workflows as MCP tools so they can be called from MCP-compatible clients.
  - Enables invocation and orchestration of Dify workflows via MCP tool calls.

- **Environment-based configuration**  
  - Supports configuring `base_url` and `app_sks` via environment variables (as of 2025-04-15).  
  - Intended to make configuration easier, especially for cloud-hosted platforms.

- **Containerized deployment**  
  - Includes a `Dockerfile` for running the server in a containerized environment.

- **Python-based project**  
  - Managed with `pyproject.toml` and `.python-version` for reproducible Python environments.  
  - Includes `uv.lock`, indicating support for `uv`-based dependency management.

- **Smithery integration**  
  - Provides a `smithery.yaml` configuration, indicating support for installation and use via Smithery as an MCP server.

## Installation & Configuration
- Installable as an MCP server from the provided GitHub repository.  
- Supports configuration through environment variables for at least:
  - `base_url`
  - `app_sks`

(For exact installation commands and full configuration options, refer to the project’s README.)

## Pricing
- Open-source GitHub project.  
- No pricing or paid plans are mentioned in the available content.