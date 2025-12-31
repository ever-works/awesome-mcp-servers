## n8n MCP Server

**Category:** Workflow Automation MCP Servers  
**Brand:** n8n  
**Source:** https://github.com/leonardsellem/n8n-mcp-server  
**License:** MIT

### Overview
n8n MCP Server is a Model Context Protocol (MCP) server that exposes tools and resources for interacting with the n8n API. It allows AI assistants and agents to manage n8n workflows and executions programmatically, including listing, creating, updating, deleting workflows, and monitoring their execution status.

### Features
- **MCP server for n8n**
  - Implements a Model Context Protocol server for integration with AI assistants/agents.
  - Provides tools for interacting with the n8n API.

- **Workflow management**
  - List existing n8n workflows.
  - Create new workflows via the MCP interface.
  - Update existing workflows.
  - Delete workflows.

- **Execution management & monitoring**
  - List workflow executions.
  - Monitor execution status of workflows.
  - Access execution-related data via n8n’s API.

- **Configuration & environment**
  - Uses environment variables (example configuration in `.env.example`).
  - Dockerfile provided for containerized deployment.
  - Babel and ESLint configuration files (`.babelrc`, `.eslintrc.json`) for building and linting.

- **Documentation & examples**
  - `AGENTS.md` and `CLAUDE.md` provide guidance for integrating with agent frameworks / Claude.
  - `docs/` directory for additional documentation.
  - `tests/` directory for automated tests.

### Pricing
- Open-source project under the **MIT License**.  
- No paid plans are listed in the repository content provided.