# SingleStore MCP Server

**Category:** MCP Servers / Directories & Lists  
**Brand:** SingleStore  
**Repository:** https://github.com/madhukarkumar/singlestore-mcp-server

## Overview

SingleStore MCP Server is a Model Context Protocol (MCP) server for the SingleStore database. It exposes structured tools that allow LLMs and MCP-compatible clients to query and manage data stored in SingleStore.

## Features

- **MCP server for SingleStore**  
  - Implements a Model Context Protocol server dedicated to interacting with a SingleStore database.  
  - Enables LLMs to perform structured queries and data management operations via MCP tools.

- **TypeScript implementation**  
  - Core server implemented in TypeScript (`src/` directory).  
  - TypeScript configuration included (`tsconfig.json`, `tsconfig.tsbuildinfo`).

- **Environment-based configuration**  
  - `.env.example` provided as a template for required environment variables.  
  - Centralized configuration for connecting to SingleStore and controlling server behavior via environment variables.

- **Containerization and deployment**  
  - `Dockerfile` included for building and running the server in a containerized environment.

- **MCP Inspector integration**  
  - `MCP_INSPECTOR.md` included with documentation and/or instructions for using the server with an MCP Inspector tool.  
  - `run_with_inspector.sh` script to simplify running the server together with an MCP Inspector.

- **Diagnostics and testing utilities**  
  - `debug_headers.sh` script for inspecting or debugging HTTP headers during development or integration.  
  - `test_sse_connection.sh` script to test SSE (Server-Sent Events) connection behavior to the server.

- **Tool/registry configuration**  
  - `smithery.yaml` configuration file, suitable for integration with tool registries or automation (e.g., Smithery/CLI-based MCP tooling setup).

- **Project scaffolding and dependencies**  
  - `package.json` and `package-lock.json` for Node.js dependencies and scripts.  
  - `.gitignore` and `.git_disabled` for repository and VCS configuration.

## Pricing

- The project is available as a public GitHub repository.  
- No pricing information, paid tiers, or commercial plans are listed in the provided content.