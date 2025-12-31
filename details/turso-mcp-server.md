## Turso MCP Server

**Description**  
MCP server that exposes Turso’s libSQL-powered, production-grade SQLite-as-a-service to MCP-aware tools and agents for data storage and querying.

**Category**  
- Database & Messaging MCP Servers

**Tags**  
- database  
- sql  
- cloud

**Integration & Access**  
- Static MCP server URL: `https://mcp.pipedream.net/v2`  
- Authenticate when adding the server to an MCP-compatible application or chat client.

## Features

- **MCP Server for Turso**  
  - Connects MCP-aware tools and agents to Turso’s managed, libSQL-based SQLite databases.  
  - Suitable for using SQLite in production environments.

- **Account & Organization Management**  
  - **Get Organizations**: Retrieve a list of organizations that the authenticated user owns or is a member of.  
  - **Get Groups**: Retrieve groups belonging to a specific organization or user.

- **Database Management**  
  - **Get Databases**: List databases belonging to the authenticated user or organization.  
  - **Create Database**: Create a new database within a chosen group for a user or organization.

- **Data Querying**  
  - **Execute SQL Query (SQLite-specific)**: Run custom SQLite queries directly against Turso databases.  
  - **Query SQL Database**: Execute generic SQL queries through the provided action.

- **Client-Agnostic Endpoint**  
  - Single static MCP server URL works with all supported MCP clients.  
  - Configuration guidance available per client (via the referenced configuration page).

## Pricing

- Not specified in the provided content.