# azure-mcp

**Category:** cloud-devops-mcp-servers  
**Brand:** Microsoft Azure  
**Source:** https://github.com/Azure/azure-mcp

## Overview
`azure-mcp` is the official Microsoft Model Context Protocol (MCP) server for Azure services. It exposes Azure resources—such as Azure Storage, Cosmos DB, Azure Monitor, and related services—through an MCP-compatible interface so that AI agents and tools can interact with Azure programmatically.

## Features
- **Official Azure MCP server** implementing the Model Context Protocol for Azure.
- **Access to Azure services via MCP**, including (per project description):
  - Azure Storage
  - Azure Cosmos DB
  - Azure Monitor
  - Other related Azure resources (as provided by the repository’s area modules).
- **Modular codebase** organized into:
  - `areas/` for service-specific or feature-specific components.
  - `core/` for shared MCP server logic and infrastructure.
- **Containerized deployment** via a provided `Dockerfile` for running the server in container environments.
- **Editor and tooling configuration**:
  - `.devcontainer/` for development container setups.
  - `.vscode/` for recommended VS Code configuration.
- **.NET solution structure** using `AzureMcp.sln`, `Directory.Build.props`, and `Directory.Packages.props` for centralized build and package management.
- **Documentation and processes**:
  - `README.md` for usage and setup instructions (not fully visible in provided content).
  - `CHANGELOG.md` for version and change tracking.
  - `CONTRIBUTING.md` for contribution guidelines.
  - `TROUBLESHOOTING.md` for diagnosing and resolving common issues.
  - `SECURITY.md` and `NOTICE.txt` for security and legal notices.

## Licensing
- Distributed under the license specified in `LICENSE` in the repository (exact terms not fully visible in the provided content).

## Pricing
- No pricing information is provided in the available content. The repository appears to be an open-source project hosted on GitHub; any Azure usage costs are determined separately by the Azure services you connect to.