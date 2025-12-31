# Amazon Q Business Anonymous MCP Server

**Category:** AI Integration MCP Servers  
**Brand:** Amazon Web Services  
**Website:** https://awslabs.github.io/mcp/servers/amazon-qbusiness-anonymous-mcp-server

## Overview
The Amazon Q Business Anonymous MCP Server is an AWS Labs Model Context Protocol (MCP) server that connects AI assistants to an Amazon Q Business application configured in anonymous mode. It lets tools and agents query a Q Business knowledge base and retrieve responses grounded in the ingested content, without requiring user-level authentication details.

## Features
- **Anonymous mode support**
  - Works with Amazon Q Business applications created using anonymous access.
  - Allows querying the knowledge base without passing user-level authentication.

- **MCP-compatible server**
  - Implements the Model Context Protocol so it can be used by MCP-capable clients (e.g., compatible IDEs, CLIs, and AI assistants).

- **Knowledge base querying**
  - Sends natural language queries to Amazon Q Business.
  - Returns responses based on content ingested into the associated Q Business application (useful for RAG-style workflows).

- **Provided tool: `QBusinessQueryTool`**
  - Exposes a tool for AI assistants to request context from Q Business.
  - Example usage pattern: “Use the QBusinessQueryTool to get the context.”

- **Environment-based configuration**
  - Uses environment variables to connect to the correct Q Business application and AWS account/region:
    - `QBUSINESS_APPLICATION_ID` (or `QBUSINESS_APP_ID` as used by some clients)
    - `QBUSINESS_USER_ID` (when required by client config examples)
    - `AWS_PROFILE`
    - `AWS_REGION`
    - `FASTMCP_LOG_LEVEL` (e.g., `ERROR`)

- **Cross-platform installation examples**
  - Installation via `uvx` / `uv` for MCP clients.
  - Example configurations for:
    - Amazon Q Developer CLI via `~/.aws/amazonq/mcp.json`.
    - VS Code (via MCP integration / install link).
    - Cursor IDE (via MCP install link and config).
  - Windows-specific `mcpServers` configuration using `command: "uv"` and `args` to run the server binary.

- **AWS integration**
  - Uses AWS IAM permissions such as `qbusiness:ChatSync` for interaction with Amazon Q Business.
  - Integrates with standard AWS credential/config flows (e.g., `aws configure`, named profiles).

- **Python/uv-based runtime**
  - Uses `uv` for managing and running the Python environment.
  - Requires Python 3.10 (installed via `uv python install 3.10`).

## Prerequisites
- `uv` installed.
- Python 3.10 available via `uv python install 3.10`.
- AWS account and credentials configured (e.g., via `aws configure`).
- An Amazon Q Business application created with anonymous mode enabled.
- Appropriate IAM permissions (e.g., `qbusiness:ChatSync`).

## Pricing
No pricing information is provided in the available content. The server is published by AWS Labs; any underlying AWS service charges (e.g., for Amazon Q Business usage) are governed by their respective AWS pricing, not described here.