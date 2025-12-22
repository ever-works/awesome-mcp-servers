# Neon MCP Server

- **Name:** Neon MCP Server  
- **Category:** MCP server / AI tools integration  
- **Source:** https://github.com/neondatabase/mcp-server-neon  
- **License:** MIT

## Description

Neon MCP Server is an open-source Model Context Protocol (MCP) server that allows AI agents to interact with the Neon serverless Postgres platform. It connects to the Neon Management API and Neon databases so agents can perform database-related operations in a programmatic, structured way.

## Features

- **MCP-compatible server** for integrating with AI agents and MCP-capable clients.  
- **Neon Management API integration** to interact with Neon’s management layer (e.g., projects, branches, databases) via an MCP server interface.  
- **Database operations support** against Neon serverless Postgres databases, enabling AI agents to work with data programmatically.  
- **Example/client implementation** under the `mcp-client` directory to demonstrate how to connect to and use the server.  
- **Scripts and tooling** (via the `scripts` directory) to support development and operational workflows.  
- **Bun-based setup** indicated by `.bun-version`, aligning the project with the Bun JavaScript runtime ecosystem.  
- **Container-friendly project layout** (e.g., presence of `.dockerignore`) to facilitate Docker-based workflows.  
- **Environment-based configuration** using `.env.example` for defining required environment variables.

## Pricing

- **Cost:** Free and open source under the MIT License.  
- **Paid plans:** None listed; no commercial pricing information is provided in the repository.