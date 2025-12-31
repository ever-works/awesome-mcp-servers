# Xero MCP Server

**Category:** Finance & Market Data MCP Servers  
**Brand:** Xero  
**Open Source:** Yes (MIT License)  
**Repository:** https://github.com/XeroAPI/xero-mcp-server

## Overview
Xero MCP Server is an open-source Model Context Protocol (MCP) server that connects MCP-compatible clients (such as AI agents) to the Xero accounting platform APIs. It provides standardized access to accounting and business data from Xero through the MCP protocol.

## Features
- **MCP Protocol Integration**  
  - Implements the Model Context Protocol to expose Xero data and operations to MCP-compatible tools and agents.

- **Xero Accounting Platform Integration**  
  - Connects to Xero’s accounting APIs.  
  - Designed to provide access to accounting and business data from Xero (e.g., suitable for SMB/finance/accounting use cases).

- **Server Implementation**  
  - Packaged as an MCP server that can be run and connected to MCP clients.  
  - Source structure includes configuration, examples, and TypeScript/JavaScript source under `src`.

- **Examples for AI Agents**  
  - `examples/openai-agents` directory demonstrates how to use the MCP server with OpenAI agents, providing reference implementations for integrating the server into agent workflows.

- **Developer Tooling & Configuration**  
  - Example environment configuration file: `.env.example` for setting required environment variables (e.g., credentials/keys).  
  - Standard Node.js project tooling: `.npmrc`, `.npmignore`, `.gitignore`.  
  - Code style and linting support: `.prettierrc`, `eslint.config.js`.  
  - `glama.json` configuration for MCP-related or tooling metadata.

- **Open Source Licensing**  
  - Licensed under the MIT License, allowing commercial and non-commercial use, modification, and distribution.

## Pricing
No pricing info is provided. The project is open source under the MIT license and can be used at no licensing cost.

## Additional Details
- **Tags:** accounting, finance, smb  
- **Slug:** xero-mcp-server
