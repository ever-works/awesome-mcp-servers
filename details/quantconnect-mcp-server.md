# QuantConnect MCP Server

Official Python-based MCP server that connects local AI clients (such as Claude Desktop) to the QuantConnect algorithmic trading platform and its financial data services, packaged for Docker deployment.

## Overview

- **Type:** Open-source Python MCP server
- **Purpose:** Enable local AI tools/clients to interact programmatically with the QuantConnect API, algorithmic trading environment, and market data via the MCP protocol.
- **Deployment:** Dockerized, suitable for running as a local or containerized service.
- **License:** Apache-2.0

## Features

- **MCP Server Implementation**
  - Implements a Model Context Protocol (MCP) server in Python.
  - Designed for integration with local AI clients (e.g., Claude Desktop) via MCP.
  - Exposes QuantConnect functionality as MCP tools/endpoints.

- **QuantConnect API Integration**
  - Connects to QuantConnect’s algorithmic trading platform.
  - Provides access to QuantConnect’s financial data services through the MCP interface.
  - Intended for use in algorithmic trading and quantitative research workflows.

- **Dockerized Deployment**
  - Includes a `Dockerfile` for building a containerized MCP server image.
  - Suitable for consistent local or cloud deployment environments.

- **Python Project Structure**
  - `src/` directory containing the server implementation.
  - `tests/` directory for automated tests.
  - `pyproject.toml` for Python project configuration and dependencies.

- **Tooling & Utilities**
  - `create_tool_markdown.py` for generating tool markdown documentation or definitions from the codebase.
  - `post_processing.py` for additional processing steps (e.g., result formatting or response handling) tied into the MCP workflow.

- **CI / Workflow Support**
  - `.github/workflows/` directory present, indicating GitHub Actions workflows for tasks such as testing, building, or linting (details depend on workflow definitions in the repo).

## Pricing

- No pricing information is provided in the referenced content. The repository is open-source under the Apache-2.0 license.