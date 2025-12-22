# MotherDuck MCP Server

## Overview
The **MotherDuck MCP Server** is an open-source Model Context Protocol (MCP) server that connects AI assistants and IDEs to data stored in **MotherDuck** and **local DuckDB** instances, enabling SQL-based querying and analytics over those databases.

- **Repository:** https://github.com/motherduckdb/mcp-server-motherduck
- **Category:** MCP server / tools directory

## Features
- **MCP server implementation for DuckDB and MotherDuck**  
  Provides a Model Context Protocol server that exposes DuckDB and MotherDuck databases to compatible AI agents and tools.

- **MotherDuck database integration**  
  Connects to MotherDuck-hosted databases so agents can run SQL queries and analyze cloud-hosted data.

- **Local DuckDB integration**  
  Supports connecting to local DuckDB files/instances, allowing analysis of on-disk or local data via the same MCP interface.

- **SQL analytics capabilities**  
  Enables AI assistants and IDEs to issue SQL queries for exploration, aggregation, and analysis of data stored in DuckDB or MotherDuck.

- **Designed for AI assistants and IDEs**  
  Intended to be embedded in development tools and AI workflows so that agents can work directly with structured data sources.

- **Configurable via environment (e.g., tokens)**  
  Uses configuration such as a `motherduck_token` environment variable (per example install config) to authenticate to MotherDuck.

## Pricing
- **Pricing model:** Not specified.  
  The project is distributed as an open-source GitHub repository; no commercial plans or pricing details are listed in the provided content.
