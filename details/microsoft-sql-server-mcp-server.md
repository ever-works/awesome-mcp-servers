# Microsoft SQL Server MCP Server

## Description
An MCP (Model Context Protocol) server that connects AI/chat clients to Microsoft SQL Server databases hosted on‑premises or in the cloud. It exposes database operations as tools that can be called from compatible clients via a static MCP endpoint.

## Category
- Databases
- MCP Servers

## Features
- **Static MCP Endpoint**  
  - Single URL for all clients: `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to your application or client.

- **Client Integration**  
  - Can be added to MCP‑compatible chat clients (e.g., ChatGPT via OpenAI).  
  - Uses the same static URL regardless of client; configuration handled per‑client.

- **Microsoft SQL Server Connectivity**  
  - Connects to Microsoft SQL Server instances on‑premises, in the cloud, or at the edge.  
  - Uses account connection flow within Pipedream to authorize and manage database access.

- **Available Tools (Actions)**  
  Four database operations are exposed as MCP tools:
  - **Insert Row**  
    - Inserts a new row into a specified table.  
    - Configurable with table and column values.
  - **Execute SQL Query (Raw)**  
    - Executes a custom SQL query string.  
    - Intended for advanced / ad‑hoc SQL operations.  
    - Referenced as `execute-raw-query` in underlying component.
  - **Execute Query**  
    - Executes a SQL query and returns the results.  
    - Wraps query execution with structured output handling.
  - **Query SQL Database**  
    - Executes a SQL query against a database, similar to general SQL query tooling in Pipedream’s database components.

- **Configuration Resources**  
  - Dedicated configuration and setup documentation via the Pipedream MCP configuration page.

## Pricing
No pricing information is provided in the available content.