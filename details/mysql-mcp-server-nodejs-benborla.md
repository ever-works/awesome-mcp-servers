# MySQL MCP Server (NodeJS, benborla)

## Overview
A Node.js-based Model Context Protocol (MCP) server that provides secure, read-only access to MySQL databases. It enables LLMs to inspect database schemas and execute read-only queries via MCP.

## Features
- **Model Context Protocol server** for integrating MySQL access into MCP-compatible LLM tools.
- **Node.js implementation**, suitable for JavaScript/TypeScript and modern tooling ecosystems.
- **Read-only access to MySQL databases**, preventing write, update, or destructive operations.
- **Configurable access controls** to restrict what the LLM can see or query within the database.
- **Schema inspection capabilities**, allowing LLMs to view and understand database structure (tables, columns, etc.).
- **Execution of read-only SQL queries** against configured MySQL databases.
- **Secure LLM database access pattern**, isolating models from direct full-privilege database connections.
- **Open-source** with an MIT license.

## Pricing
- **Free & open-source**: Available at no cost under the MIT license; self-host and run on your own infrastructure.