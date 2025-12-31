# Hologres MCP Server

**Category:** database-messaging-mcp-servers  
**Brand:** Alibaba Cloud Hologres  
**Source:** https://github.com/aliyun/alibabacloud-hologres-mcp-server

## Overview
Hologres MCP Server is an MCP (Model Context Protocol) server that connects AI agents to Alibaba Cloud Hologres instances. It allows agents to inspect table metadata and execute analytical SQL queries against Hologres, integrating Hologres’ data warehouse/analytics capabilities into MCP-compatible tools and workflows.

## Features
- **MCP server implementation**
  - Implements the Model Context Protocol to expose Hologres as a tool to MCP-compatible AI agents.
- **Hologres connectivity**
  - Connects to Alibaba Cloud Hologres instances using configured connection parameters (e.g., endpoint, database, credentials).
- **Metadata access**
  - Allows AI agents to discover and access table and schema metadata from Hologres (e.g., tables, columns, types).
- **Analytical query execution**
  - Supports running analytical SQL queries against Hologres from within AI agent contexts.
- **Node.js/TypeScript project structure**
  - Distributed as a Node.js package (includes `package-lock.json` and `src` directory) suitable for integration into JavaScript/TypeScript environments.
- **Test suite**
  - Includes a `tests` directory for validating behavior and integrations.
- **Open-source licensing**
  - Released under the Apache-2.0 license.
- **Release notes**
  - `RELEASE_NOTES.md` documents version history and changes.

## Pricing
No pricing information is provided in the available content. The MCP server itself is open source under Apache-2.0; usage of Alibaba Cloud Hologres is subject to Alibaba Cloud’s separate service pricing.
