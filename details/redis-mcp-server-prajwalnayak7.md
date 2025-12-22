# Redis MCP Server (prajwalnayak7)

## Overview
- **Type:** Model Context Protocol (MCP) server
- **Purpose:** Enable LLM tools to interact with Redis Server and AWS MemoryDB for caching and other in-memory key–value storage use cases
- **Ecosystem:** Redis, AWS MemoryDB
- **Source:** [GitHub – prajwalnayak7/mcp-server-redis](https://github.com/prajwalnayak7/mcp-server-redis)

## Features
- **Redis / MemoryDB integration**  
  - Connects to Redis-compatible backends such as Redis Server and AWS MemoryDB  
  - Designed for caching and other in-memory, key–value storage workflows from within MCP-compatible LLM tools

- **Structured project layout**  
  - `src/main.py`: Main entry point for running the MCP server  
  - `src/config.py`: Centralized configuration management  
  - `src/connection.py`: Redis connection handling and management

- **Resource-based API inside MCP**  
  - `resources/status.py`: Resources for querying connection/health status  
  - `resources/keys.py`: Resources focused on key-related operations

- **Tool implementations for Redis operations**  
  - `tools/basic.py`: Basic Redis operations (e.g., simple key–value interactions)  
  - `tools/lists.py`: Redis list operations (e.g., interacting with list data structures)  
  - `tools/hashes.py`: Redis hash operations (e.g., working with hash fields/values)

- **Testing and configuration assets**  
  - `tests/` directory for automated tests  
  - `.env.example` for environment variable configuration examples  
  - `pyproject.toml` and `uv.lock` for Python project and dependency management

- **Containerization & deployment helpers**  
  - `Dockerfile` for containerized deployment of the MCP server

- **Open-source licensing**  
  - `LICENSE` file included in the repository (see repository for exact license terms)

## Technology Stack
- **Language:** Python (managed via `pyproject.toml` / `uv.lock`)
- **Data Stores:** Redis Server, AWS MemoryDB (Redis-compatible)
- **Protocol:** Model Context Protocol (MCP)
- **Containerization:** Docker

## Pricing
- **Model:** Open-source project  
- **Cost:** Free to use (subject to the terms of the license in the `LICENSE` file)