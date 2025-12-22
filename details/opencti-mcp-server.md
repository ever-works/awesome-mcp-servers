# OpenCTI MCP Server

## Overview
OpenCTI MCP Server is a Model Context Protocol (MCP) server that integrates with the OpenCTI (Open Cyber Threat Intelligence) platform to query and retrieve threat intelligence data through a standardized interface.

## Features
- **OpenCTI integration**: Connects to an OpenCTI instance to access cyber threat intelligence data.
- **Threat intelligence queries**: Supports querying and retrieving entities such as:
  - Reports
  - Indicators
  - Malware
  - Threat actors
- **Standardized MCP interface**: Exposes OpenCTI data via the Model Context Protocol for use with MCP-compatible clients and tools.
- **Environment-based configuration**: Includes a `.env.example` file for configuring connection and runtime settings via environment variables.
- **Containerization support**: Provides a `Dockerfile` for running the server in a containerized environment.
- **TypeScript/Node.js project setup**: Includes `package.json` and `tsconfig.json` for dependency management, compilation, and build configuration.
- **MCP registry metadata**: Includes `smithery.yaml` for MCP server metadata and integration with Smithery.
- **Multilingual documentation**: Documentation available in English and Traditional Chinese (`README.md`, `README.zh-TW.md`).

## Pricing
- Open-source GitHub project. No pricing or commercial plans are listed; usage is governed by the terms in the repository’s `LICENSE` file.

## Links
- Source code: https://github.com/Spathodea-Network/opencti-mcp
- Smithery listing: https://smithery.ai/server/opencti-server
- Glama MCP directory entry: https://glama.ai/mcp/servers/ml61kiz1gm