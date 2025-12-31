# ServiceNow MCP Server

## Overview
ServiceNow MCP Server is an open-source Model Context Protocol (MCP) server that connects Large Language Models (LLMs) to a ServiceNow instance. It enables LLMs to query and manage ServiceNow data and workflows programmatically via MCP.

- **Category:** Workflow Automation MCP Servers  
- **Brand:** ServiceNow  
- **Source:** https://github.com/osomai/servicenow-mcp

## Features
- **MCP server for ServiceNow**  
  - Implements a Model Context Protocol server dedicated to interacting with ServiceNow.
- **ServiceNow instance integration**  
  - Connects to an existing ServiceNow instance using configuration from environment variables (e.g., `.env.example`).
- **Data access and querying**  
  - Allows LLMs to query ServiceNow data (such as records, tickets, or related tables) through MCP tools.
- **Workflow and ticket management**  
  - Supports managing ServiceNow workflows and ticketing operations (e.g., IT management and service desk use cases) via LLM-driven actions.
- **LLM-oriented interface**  
  - Exposes ServiceNow functionality as structured MCP tools for use by LLM clients.
- **Configuration and examples**  
  - `config/` directory for server and integration configuration files.  
  - `examples/` directory to demonstrate how to use the server with different MCP/LLM setups.  
  - `prompts/` folder containing example prompts tailored for ServiceNow interactions.
- **Documentation and scripts**  
  - `docs/` directory with project and usage documentation.  
  - `scripts/` directory, likely including helper utilities (e.g., setup, run, or utility scripts).  
  - `debug_workflow_api.py` for debugging or inspecting ServiceNow workflow API behavior.
- **Testing and quality**  
  - `tests/` directory with automated tests for the MCP server’s functionality.
- **Containerization and deployment**  
  - `Dockerfile` for building and running the ServiceNow MCP server in a containerized environment.
- **Python project setup**  
  - Managed via `pyproject.toml` and `uv.lock` for dependencies and build configuration.
- **Open-source licensing**  
  - Distributed under an open-source license (see `LICENSE` file in the repository).

## Pricing
- No pricing information is provided in the available content. The project appears to be open-source, but users should refer to the repository’s LICENSE and documentation for any usage terms.
