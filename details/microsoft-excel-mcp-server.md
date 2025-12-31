# Microsoft Excel MCP Server

**Category:** Data Analysis & Exploration MCP Servers  
**Brand:** Microsoft  
**Slug:** `microsoft-excel-mcp-server`

## Overview
The Microsoft Excel MCP Server exposes Microsoft Graph–powered tools that let MCP-compatible clients read and modify Excel workbooks stored in OneDrive for Business, SharePoint sites, or Group drives. It provides a static MCP server URL that can be added to supported chat or MCP clients to work with Excel data programmatically.

- **Server URL:** `https://mcp.pipedream.net/v2`
- **Data sources:**
  - OneDrive for Business
  - SharePoint sites
  - Microsoft 365 Group drives
- **Use cases:** reading, querying, and updating Excel worksheets, tables, columns, cells, and rows via MCP-aware applications.

## Features

### Connectivity & Access
- Uses **Microsoft Graph** to access Excel workbooks.
- Supports **Excel workbooks stored in**:
  - OneDrive for Business
  - SharePoint sites
  - Microsoft 365 Group drives
- Single **static MCP server URL** used across clients (`https://mcp.pipedream.net/v2`).
- Authentication occurs when adding the server to the client/application.

### Available Tools / Actions
The server exposes 8 actions as MCP tools:

1. **Update Worksheet Tablerow**
   - Updates the properties of a `tablerow` object in a worksheet table.
   - Limited to **work or school accounts**.

2. **Update Cell**
   - Updates the value of a specific cell in an Excel worksheet.
   - Suitable for changing single-cell values (e.g., metrics, flags, statuses).

3. **Get Table Rows**
   - Retrieves rows from a specified table in an Excel worksheet.
   - Useful for reading structured table data for analysis or reporting.

4. **Get Spreadsheet**
   - Gets the values of a specified Excel worksheet.
   - Enables pulling full-sheet or range-based data into MCP clients.

5. **Get Columns**
   - Retrieves the values of specified columns in an Excel worksheet.
   - Supports column-level data access for targeted queries.

6. **Find Row**
   - Finds a row by a specified column and value.
   - Enables lookups such as “find the record where column X = value Y.”

7. **Add Row**
   - Inserts a new row into a specified Excel worksheet.
   - Can be used to append records to non-table ranges or structured sheets.

8. **Add a Worksheet Tablerow**
   - Adds rows to the end of a specific table in a worksheet.
   - Supports appending new records to Excel tables.

### Client Integration
- Designed for **MCP-compatible chat and automation clients**.
- Users connect a Microsoft account and then add the server URL to their client.
- Additional client-specific setup guidance is available via the configuration documentation (not included here).

## Pricing
Pricing information is not provided in the available content. Users should refer to the source or platform (Pipedream / Microsoft Graph / Microsoft 365 licensing) for any associated costs.