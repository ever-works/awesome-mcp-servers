# Metabase MCP Server

**Category:** Data Analysis & Exploration MCP Servers  
**Brand:** Metabase  
**Source:** https://mcp.pipedream.com/app/metabase

Metabase MCP Server is an MCP-compatible integration that connects Metabase to chat or agent clients, enabling fast analytics and self-service BI queries and dashboards directly through MCP-compatible tools.

---

## Features

### MCP Server & Connectivity
- Static MCP server URL: `https://mcp.pipedream.net/v2` (works for all MCP-compatible clients).
- Connects Metabase to various chat clients and agent applications.
- Authentication handled when adding the server to your application.
- Central configuration via a shared configuration page.

### Analytics & BI Capabilities (Available Tools / Actions)
1. **Run Query**
   - Execute a saved Metabase question/card.
   - Returns query results for further analysis or use in agents.

2. **Get Database**
   - Retrieve information about a Metabase-connected database.
   - Useful for schema discovery and understanding available data sources.

3. **Get Dashboard**
   - Retrieve dashboard details and its associated cards.
   - Enables agents to inspect and reference existing dashboards.

4. **Export Query with Format**
   - Execute a saved question/card with parameters.
   - Export results in multiple formats: **CSV**, **JSON**, **XLSX**, or **API**.
   - Supports parameterized queries for flexible analytics output.

5. **Create Dashboard**
   - Programmatically create new Metabase dashboards.
   - Allows automated or agent-driven dashboard generation.

### Use Cases
- Run existing Metabase questions from within chat or agent interfaces.
- Explore database and dashboard metadata via MCP tools.
- Export analytics results in common data formats for downstream processing.
- Automatically create dashboards based on agent or user workflows.

---

## Configuration
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible chat client or app.
- Authentication is completed as part of the app integration flow.
- Additional setup details are available on the configuration page linked from the app.

---

## Pricing
- No pricing information is provided in the available content.