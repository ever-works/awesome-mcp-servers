# MCPJungle

## Overview
MCPJungle is a self-hosted MCP gateway and registry for AI agents. It acts as an internal directory and management layer for discovering and operating multiple MCP servers in an enterprise or self-managed environment.

- **Category:** MCP server directories & lists
- **Type:** Open-source self-hosted software
- **License:** MPL-2.0
- **Source:** https://github.com/mcpjungle/MCPJungle

## Features
- **MCP Gateway**
  - Acts as a central gateway for AI agents to connect to multiple MCP servers.
  - Provides a single endpoint instead of configuring each MCP server individually.

- **Server Registry / Directory**
  - Maintains a registry of available MCP servers.
  - Enables discovery of multiple MCP servers from one place.
  - Suitable for internal/enterprise environments where many MCP servers are deployed.

- **Self-Hosted Deployment**
  - Can be deployed in your own infrastructure.
  - Includes a `Dockerfile` for containerized deployment.

- **Client and CLI Components**
  - `client` directory indicates a client library or tooling for interacting with the gateway/registry.
  - `cmd` directory suggests one or more command-line binaries for running and managing the service.

- **Configurable / Extensible Architecture**
  - `internal` and `pkg` directories imply a modular Go codebase that can be extended or integrated into other systems.

- **Automation & Tooling**
  - `scripts` for build or operational automation.
  - `.golangci.yml` for linting and code quality.
  - `.goreleaser.yaml` for building and releasing binaries.

- **Development & Contribution Docs**
  - `DEVELOPMENT.md` with guidance for local development and project structure.
  - `CONTRIBUTION.md` describing how to contribute code or improvements.

## Pricing
- Open source under the **MPL-2.0** license; no commercial pricing information is provided.

## Tags
- directory
- enterprise
- mcp

## Links
- **Repository:** https://github.com/mcpjungle/MCPJungle