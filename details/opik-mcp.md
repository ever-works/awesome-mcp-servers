# opik-mcp

**Category:** Monitoring  
**Brand:** Comet  
**Slug:** opik-mcp  
**Source:** https://github.com/comet-ml/opik-mcp  
**License:** Apache-2.0

## Description
opik-mcp is a Model Context Protocol (MCP) server for Comet’s Opik platform. It enables large language models and MCP-compatible tools (such as IDE plugins) to query and explore Opik’s LLM observability, traces, and monitoring data using natural language.

## Features
- **Model Context Protocol implementation**
  - Provides an MCP server compliant with the Model Context Protocol.
  - Designed for integration with MCP clients (e.g., IDEs and other MCP-enabled tools).

- **Opik platform integration**
  - Connects directly to Comet’s Opik observability platform.
  - Exposes Opik data and resources through MCP tools.

- **Observability and monitoring data access**
  - Allows querying LLM observability data.
  - Supports exploration of LLM traces and monitoring metrics.

- **Unified access to Opik resources**
  - Access to prompts stored in Opik.
  - Access to projects within Opik.
  - Access to traces captured by Opik.
  - Access to metrics related to LLM performance and monitoring.

- **Natural language interaction**
  - Enables LLMs and MCP clients to explore Opik data via natural-language queries rather than manual dashboard navigation.

- **Developer tooling and structure**
  - Includes a `client` directory for client-related code.
  - `src` directory containing the main server implementation.
  - `tests` directory with automated tests.
  - `docs` directory for project documentation.
  - Example environment configuration via `.env.example`.
  - Dockerfile for containerized deployment.
  - Project tooling configuration (ESLint, Prettier, Git ignore).

## Technical Details
- **Implementation:** JavaScript/TypeScript-based Node.js project structure (inferred from ESLint/Prettier configuration and typical MCP setups).
- **Deployment:** Can be containerized and run via the provided Dockerfile.
- **Version control:** Public GitHub repository with active commit history.

## Pricing
No pricing information is provided in the available content. The project is open source under the Apache-2.0 license.
