# pgmcp

**Category:** Database Messaging MCP Servers  
**Website:** https://github.com/subnetmarco/pgmcp  
**License:** Open source (see repository LICENSE)

## Overview
pgmcp is a Model Context Protocol (MCP) server for PostgreSQL that lets clients perform natural language queries against Postgres databases. It focuses on safe, read‑only access, automatic streaming of results, and broad compatibility across PostgreSQL databases.

## Features
- **Natural language to SQL for PostgreSQL**  
  - Accepts natural language prompts and converts them into SQL queries for Postgres databases.  
- **MCP server implementation**  
  - Exposes database querying capabilities via the Model Context Protocol for use with compatible MCP clients.  
- **Read‑only query safety**  
  - Designed to run in read‑only mode so that generated queries do not modify database state (e.g., no INSERT/UPDATE/DELETE).  
- **Automatic streaming of query results**  
  - Streams query results back to the client rather than waiting for full completion, enabling responsive, incremental output.  
- **Broad PostgreSQL compatibility**  
  - Works with standard PostgreSQL databases; intended to be usable across different Postgres deployments.  
- **Configurable server** (inferred from repo structure)  
  - Server implementation located under a `server` directory, suggesting configuration options for connecting to target Postgres instances.  
- **Client components** (inferred from `client` directory)  
  - Includes client-side code for interacting with the MCP server.  
- **Containerization support**  
  - Dockerfile provided for containerized deployment.  
- **Kubernetes examples**  
  - `examples/k8s` directory with example manifests for running pgmcp on Kubernetes.  
- **Go-based implementation**  
  - Implemented in Go (Go modules present), benefiting from a single binary build and standard Go tooling.  
- **Release tooling**  
  - `.goreleaser.yaml` included for automated builds and releases.  

## Pricing
- Not specified. The project is open source; usage is governed by the repository’s license.
