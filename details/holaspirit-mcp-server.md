# Holaspirit MCP Server

An open-source Model Context Protocol (MCP) server that integrates with the Holaspirit platform, enabling LLMs to access and work with Holaspirit governance and organizational data via its API.

## Features

- **Holaspirit integration**: Connects directly to the Holaspirit platform through its API.
- **Governance & organizational data access**: Allows LLMs to interact with governance structures and organizational information stored in Holaspirit (as exposed by the API).
- **MCP-compatible server**: Implements the Model Context Protocol so it can be used as a tool/server by MCP-capable LLM clients.
- **Environment-based configuration**:
  - `.env.sample` provided to guide setup of required environment variables (e.g., credentials, endpoints).
- **Containerized deployment**:
  - `Dockerfile` included for building and running the server in a containerized environment.
- **Examples provided**:
  - `examples/` directory with sample configurations or usage patterns to help get started.
- **Node.js / TypeScript stack**:
  - Source code under `src/`, using a Node.js + TypeScript toolchain (with `tsconfig`, ESLint, Prettier, etc.).
- **Automation & CI configuration**:
  - GitHub Actions workflows under `.github/workflows/` for automated tasks (e.g., build/test).

## Pricing

- **Open-source**: Available free of charge as a GitHub repository.
- **License**: Usage and redistribution subject to the terms in the included `LICENSE` file.