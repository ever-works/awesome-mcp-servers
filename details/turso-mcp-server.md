## Overview

Turso is an edge-hosted SQLite database designed for modern applications, built on LibSQL (a fork of SQLite), offering embedded replicas for ultra-low latency and simple operation. The Turso CLI includes a built-in Model Context Protocol (MCP) server that allows AI assistants to interact with your databases.

## Features

- **Built-in MCP Server**: Native MCP support in Turso CLI
- **LibSQL Foundation**: Full SQLite compatibility with extended features
- **Edge Deployment**: Deploy databases everywhere—servers, browsers, devices
- **Embedded Replicas**: Ultra-low latency with local replicas
- **File-Like Operation**: Lightweight database deployment model
- **Full Backwards Compatibility**: Same file format and API as SQLite

## LibSQL Advantages

- Fork of SQLite maintaining full compatibility
- Same file format and API
- Full backwards compatibility
- Extended features the ecosystem has long needed
- Drop-in SQLite replacement

## Community MCP Servers

Multiple community-developed MCP servers available:

### mcp-turso (nbbaier)
Provides access to Turso-hosted LibSQL databases

### turso-mcp (PramaAditya)
Read-only MCP server for querying Turso/libSQL databases, enabling AI assistants like Claude, Roo, and Cline to safely query databases without risk of data modification

### mcp-libsql (Xexr)
Comprehensive security and management tools, supporting file, local HTTP, and remote Turso databases with connection pooling, transaction support, and 6 specialized database tools

## Use Cases

- Lightweight database deployment for millions of agents
- Edge computing applications
- Browser-based data storage
- IoT and device-local databases
- Distributed applications with local-first architecture
- Agentic AI with embedded data

## Integration

Easily connect to Turso MCP server using Claude Code with built-in MCP management commands.

## Pricing

Free tier available. Usage-based pricing for production workloads.