# Lightdash MCP Server

## Overview
Lightdash MCP Server is a Model Context Protocol (MCP) server that integrates with the Lightdash business intelligence (BI) platform. It allows language models to interact with Lightdash in order to explore and query analytics data programmatically.

- **Project type:** Open-source MCP server
- **Ecosystem:** Lightdash (BI / analytics)
- **Repository:** https://github.com/syucream/lightdash-mcp-server

## Features
- **MCP integration layer for Lightdash**  
  Provides an MCP-compliant server that connects LLMs to a Lightdash instance.

- **LLM-to-BI interaction**  
  Enables LLMs to interact with the Lightdash BI tool, so analytical workflows can be driven through natural language via the MCP interface.

- **Analytics exploration and querying**  
  Designed to support exploring and querying analytics data available in Lightdash.

- **Node.js / TypeScript implementation**  
  Implemented in a Node.js/TypeScript stack (as indicated by `package.json`, `.node-version`, and TypeScript tooling).

- **Environment-based configuration**  
  Uses environment variables for configuration (sample config in `.env.sample`).

- **Containerization support**  
  Includes a `Dockerfile` for building and running the MCP server in a containerized environment.

- **Examples provided**  
  The `examples` directory contains sample usage or reference configurations to help set up and experiment with the server.

## Pricing
- Open-source project. No pricing information is specified in the repository.

## License
- A license file (`LICENSE`) is included in the repository. Refer to it for full licensing terms.