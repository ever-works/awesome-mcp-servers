# Postgres MCP Server

## Overview
An AWS Labs Model Context Protocol (MCP) server that connects MCP clients to Amazon Aurora PostgreSQL databases. It lets LLM-based tools issue Postgres-compatible SQL queries against a configured Aurora Postgres instance.

**Source:** https://awslabs.github.io/mcp/servers/postgres-mcp-server

## Features
- **Natural language to Postgres SQL**  
  - Converts human-readable questions and commands into structured, Postgres-compatible SQL queries.  
  - Executes the generated SQL against the configured Aurora PostgreSQL database.

## Prerequisites
1. **uv** installed (from Astral or the uv GitHub README).
2. **Python 3.10** installed via `uv python install 3.10`.
3. The MCP server must run **locally on the same host** as your LLM client.
4. **Docker runtime** available (for Docker-based usage/builds).
5. **AWS credentials** configured with access to required AWS services:
   - An AWS account with appropriate permissions.
   - Credentials configured via `aws configure` or environment variables.

## Installation & Setup

### 1. Configure in MCP client (general)
Configure the server in your MCP client (e.g., Amazon Q Developer CLI `~/.aws/amazonq/mcp.json`) to run the `awslabs.postgres-mcp-server` via `uvx`, typically including:
- `command`: `uvx`
- `args`: `["awslabs.postgres-mcp-server@latest", "--allow_write_query"]`
- `env` (examples):
  - `AWS_PROFILE`: your AWS profile
  - `AWS_REGION`: e.g., `us-east-1`
  - `FASTMCP_LOG_LEVEL`: e.g., `ERROR`
- `disabled`: `false`
- `autoApprove`: `[]`

### 2. Windows installation
On Windows, configuration differs slightly, typically using `uv tool run`:
- `type`: `stdio`
- `command`: `uv`
- `args`: `["tool", "run", "--from", "awslabs.postgres-mcp-server@latest", "awslabs.postgres-mcp-server.exe"]`
- `env` (examples):
  - `FASTMCP_LOG_LEVEL`: `ERROR`
  - `AWS_PROFILE`: your AWS profile
  - `AWS_REGION`: e.g., `us-east-1`
- `timeout`: e.g., `60`
- `disabled`: `false`

### 3. Build and run via Docker (local)
1. Clone the repository:  
   `git clone https://github.com/awslabs/mcp.git`
2. Go to the Postgres MCP server subdirectory:  
   `cd src/postgres-mcp-server/`
3. Build the Docker image locally:  
   `docker build -t awslabs/postgres-mcp-server:latest .`

(Usage and connection options such as “Option 1: Using RDS Data API Connection (for Aurora Postgres)” are referenced but not fully detailed in the provided content.)

## Environment & Configuration Notes
- Designed to run **on the same host as the LLM client**.
- Uses AWS credentials and region configuration (e.g., `AWS_PROFILE`, `AWS_REGION`).
- Logging level can be controlled via `FASTMCP_LOG_LEVEL` (e.g., `ERROR`).
- `--allow_write_query` can be passed to enable write queries (based on example args).

## Pricing
Pricing information is **not specified** in the provided content. (Typical costs, if any, would depend on your underlying AWS and Aurora PostgreSQL usage, not on this MCP server itself.)