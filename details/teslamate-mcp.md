# teslamate-mcp

## Overview
`teslamate-mcp` is an open-source Model Context Protocol (MCP) server that connects to a TeslaMate database and exposes Tesla vehicle and charging data so AI assistants and tools can query transportation and EV-related information.

- **Category:** data-access-integration-mcp-servers  
- **Developer / Brand:** cobanov  
- **Source Code:** https://github.com/cobanov/teslamate-mcp

## Features
- **Model Context Protocol (MCP) server**  
  - Implements an MCP-compatible server to expose TeslaMate data to AI assistants and other MCP clients.

- **TeslaMate database integration**  
  - Connects directly to an existing TeslaMate database.  
  - Uses predefined queries (in the `queries` directory) to access structured EV data.

- **Vehicle data access**  
  - Provides endpoints/tools for querying Tesla vehicle information stored in TeslaMate (e.g., state, historical data, and analytics, as available in the TeslaMate schema).

- **Charging and trip analytics**  
  - Exposes charging sessions, energy usage, and related analytics computed or stored by TeslaMate.  
  - Suitable for transportation and EV-related use cases such as trip summaries, efficiency insights, and charging patterns, depending on the underlying TeslaMate data.

- **AI assistant integration**  
  - Designed so LLM-based assistants can call MCP tools to fetch real-time or historical EV data during conversations.

- **Containerized deployment**  
  - **Dockerfile** included for building a container image of the MCP server.  
  - **docker-compose.yml** for running the service with configuration and environment variables.

- **Configurable environment**  
  - `env.example` file documents expected environment variables (e.g., database connection settings) for connecting to TeslaMate.

- **Local and remote entrypoints**  
  - `main.py` and `main_remote.py` provide different run modes (e.g., local vs. remote MCP server usage).

- **Python-based implementation**  
  - Managed via `pyproject.toml` and `uv.lock` for dependencies and reproducible environments.  
  - Includes `test_server.py` for basic server testing.

- **Assets and utilities**  
  - `assets` directory contains visual/demo assets (e.g., animated GIF showing usage).  
  - `utils` directory contains helper modules used across the server implementation.

- **Open-source licensing**  
  - Distributed with a `LICENSE` file (exact license type available in the repository) for open-source use and modification.

## Pricing
- The project is an open-source GitHub repository.  
- No pricing or paid plans are specified; usage is implied to be free under the terms of the included open-source license.
