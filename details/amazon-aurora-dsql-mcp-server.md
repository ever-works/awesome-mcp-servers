# Amazon Aurora DSQL MCP Server

**Category:** Database & Messaging MCP Servers  
**Brand:** Amazon Web Services (AWS)  
**Website:** https://awslabs.github.io/mcp/servers/aurora-dsql-mcp-server

## Overview
Amazon Aurora DSQL MCP Server is a Model Context Protocol (MCP) server that connects AI agents and MCP-compatible clients to an Amazon Aurora DSQL cluster. It converts natural language questions and commands into PostgreSQL-compatible SQL, executes them against Aurora DSQL, and exposes tools for database operations and documentation access.

## Features
- Converts human-readable questions and commands into structured, Postgres-compatible SQL queries.
- Executes generated SQL against a configured Amazon Aurora DSQL database cluster.
- Read-only operation by default to protect data.
- Optional write capability via a `--allow-writes` flag to enable transactions.
- Transactional execution of write operations when writes are enabled.
- Connection reuse between requests to improve performance and reduce overhead.
- Built-in integration with Aurora DSQL documentation:
  - Documentation search.
  - Reading specific documentation pages.
  - Best-practice recommendation retrieval.
- Designed to run locally on the same host as the LLM/MCP client.
- Uses standard AWS authentication/credentials for access to Aurora DSQL and related services.

## Available Tools

### Database Operations
- **readonly_query**
  - Execute read-only SQL queries against the configured Aurora DSQL cluster.
- **transact**
  - Execute write operations within a transaction (requires `--allow-writes`).
- **get_schema**
  - Retrieve table schema information for understanding database structure.

### Documentation and Recommendations
- **dsql_search_documentation**
  - Search Aurora DSQL documentation.
  - Parameters:
    - `search_phrase` (required)
    - `limit` (optional)
- **dsql_read_documentation**
  - Read specific Aurora DSQL documentation pages.
  - Parameters:
    - `url` (required)
    - `start_index` (optional)
    - `max_length` (optional)
- **dsql_recommend**
  - Get best-practice recommendations related to Aurora DSQL.
  - Parameters:
    - `url` (required)

## Prerequisites
- AWS account with an **Aurora DSQL Cluster**.
- MCP server must run locally on the same host as the LLM client.
- AWS credentials configured with appropriate permissions, via:
  - `aws configure`, or
  - Environment variables.
- Python 3.10 installed (e.g., via `uv python install 3.10`).

## Installation

### Using `uv`
1. Install `uv` from Astral.
2. Install Python 3.10 using `uv python install 3.10`.
3. Configure the MCP server in your MCP client configuration (example shown for Amazon Q Developer CLI via `~/.aws/amazonq/mcp.json`), specifying:
   - Command: `uvx`
   - Package: `awslabs.aurora-dsql-mcp-server@latest`
   - Arguments including:
     - `--cluster_endpoint` (your DSQL cluster endpoint)
     - `--region` (e.g., `us-east-1`)
     - `--database_user` (your DSQL username)
     - `--profile` (e.g., `default`)
   - Environment variables such as `FASTMCP_LOG_LEVEL=ERROR`.

### Windows Installation
- Uses a slightly different MCP configuration format:
  - `type`: `stdio`
  - `command`: `uv`
  - `args`: typically `tool run --from awslabs.aurora-dsql-mcp-server@latest awslabs.aurora-dsql-mcp-server.exe`
  - `timeout` (e.g., `60` seconds)
  - Environment variable `FASTMCP_LOG_LEVEL=ERROR`.

## Pricing
Pricing information is not provided in the available content. Use of this server may involve standard AWS charges for Aurora DSQL and related AWS services.