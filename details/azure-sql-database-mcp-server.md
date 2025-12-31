# Azure SQL Database MCP Server

## Overview
The Azure SQL Database MCP Server is an MCP (Model Context Protocol) server that lets MCP-compatible clients interact with managed Microsoft Azure SQL Databases in the cloud. It is provided and hosted via Pipedream Connect.

- **Type:** MCP server (database integration)
- **Service:** Microsoft Azure SQL Database
- **Category:** Databases / MCP servers
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Static MCP Server Endpoint**
  - Single static base URL (`https://mcp.pipedream.net/v2`) used across all supported MCP clients.
  - Authentication occurs when the server is added to the client / application.

- **MCP Client Integration**
  - Can be added to various chat or MCP clients (e.g., ChatGPT via OpenAI), using the provided configuration guides.
  - Configuration documentation is available via the Pipedream MCP configuration page.

- **Azure SQL Database Connectivity**
  - Connects to managed Microsoft Azure SQL Databases in the cloud.
  - Supports working with SQL queries and table data from within MCP-compatible clients.

- **Available Tools / Actions**
  1. **Query SQL Database**  
     - Execute SQL queries against the connected database.  
     - Uses Pipedream’s generic SQL querying capabilities.

  2. **Insert Row**  
     - Insert a new row into a specified table in Azure SQL Database.  
     - Parameters (from linked docs, implied typical usage): table selection and column values for insertion.

  3. **Execute SQL Query (Raw)**  
     - Execute a custom SQL query (raw query) against the Azure SQL Database.  
     - Suitable for advanced or ad-hoc SQL operations beyond predefined templates.

  4. **Execute Query (Return Results)**  
     - Execute a SQL query and return the results to the MCP client.  
     - Designed for read/query operations where the response data is needed in the client.

## Authentication & Setup
- Sign-in required via Pipedream to connect a Microsoft Azure SQL Database account.
- After sign-in, users can:
  - Configure the MCP server.
  - Select and configure their preferred client (such as ChatGPT) to use the server.

## Pricing
The provided content does not list any pricing or plan information for the Azure SQL Database MCP Server. Pricing (if any) would need to be obtained from Pipedream or Microsoft Azure directly.