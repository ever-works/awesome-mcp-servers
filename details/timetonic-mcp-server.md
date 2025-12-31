# TimeTonic MCP Server

## Overview
TimeTonic MCP Server is an MCP (Model Context Protocol) integration that connects TimeTonic’s no-code business app and workflow automation platform to compatible chat or AI clients. It exposes TimeTonic table operations as tools, enabling apps and workflows to read and manipulate TimeTonic data programmatically.

- **Type:** MCP server integration
- **Platform:** TimeTonic (no-code business and workflow automation)
- **Category:** Workflow automation MCP servers
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL that works for all TimeTonic clients.
- Authentication performed when adding the server to an MCP-compatible application.
- Usable with multiple chat clients / applications that support MCP.

### Data & Table Operations (Available Tools)
The server provides 4 actions as tools for interacting with TimeTonic tables:

1. **Create Row**
   - Create a new row within an existing TimeTonic table.
   - Useful for adding new records, entries, or items via automations or chat-based workflows.

2. **Update Row**
   - Update values within a specified row in a TimeTonic table.
   - Supports modifying existing records without manual changes in the UI.

3. **Search Rows**
   - Perform searches across table rows based on specified criteria.
   - Enables retrieval and filtering of TimeTonic records directly from MCP-compatible clients.

4. **Delete Row**
   - Delete a row in an existing TimeTonic table.
   - Allows automated cleanup or removal of records.

### Use Cases
- Centralized management of business data stored in TimeTonic via AI or chat clients.
- Workflow automation that creates, updates, searches, and deletes rows in TimeTonic tables.
- Integration of TimeTonic into broader MCP-based automation or assistant setups.

## Pricing
No pricing information is provided in the available content for the TimeTonic MCP Server. Pricing, if any, would depend on TimeTonic and/or Pipedream service plans.