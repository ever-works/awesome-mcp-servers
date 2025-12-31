# Google Sheets MCP Server

**Brand:** Google  
**Category:** Data Access & Integration – MCP Servers  
**Slug:** `google-sheets-mcp-server`

## Description
MCP Server for Google Sheets that enables creation, editing, and management of online spreadsheets via MCP-compatible tools and workflows. It uses a static MCP server URL and Google account authentication to operate on Sheets in real time from any connected client.

## MCP Server Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Google account sign-in when adding the server to an MCP-compatible application
- **Usage:** Add the server URL to your chat or MCP client, then authorize access to Google Sheets

## Features

### General Capabilities
- Create and edit Google Sheets spreadsheets via MCP tools
- Work with online spreadsheets in real time
- Secure, account-based access to Sheets
- Accessible from any MCP-compatible client or device
- 31 MCP actions available as tools for Google Sheets operations

### Available Tools (Actions)
Below are the explicitly listed actions exposed as MCP tools:

1. **Add Single Row**  
   - Add a single row of data to a Google Sheet
   - Optionally insert at a specific row index (e.g., row 2 to add below headers, shifting existing data down)

2. **Update Conditional Format Rule**  
   - Modify an existing conditional formatting rule in a sheet

3. **Set Data Validation**  
   - Add data validation rules to cells, including:
     - Dropdown lists
     - Checkboxes
     - Date validation
     - Number validation

4. **Merge Cells**  
   - Merge a specified range of cells into a single cell

5. **Delete Conditional Format Rule**  
   - Remove a conditional formatting rule by its index in the sheet

6. **Add Protected Range**  
   - Add edit protection to a cell range
   - Configure permissions for who can edit the protected range

7. **Add Conditional Format Rule**  
   - Create conditional formatting rules, including:
     - Color scales
     - Custom formula-based rules

8. **Upsert Row**  
   - Insert or update (upsert) a row of data in a Google Sheet

9. **Update Row**  
   - Update an existing row in a spreadsheet

10. **Update Multiple Rows**  
    - Update multiple rows at once, defined by a range

11. **Update Formatting**  
    - Update cell formatting in a spreadsheet (e.g., style-related properties)

12. **Update Cell**  
    - Update the contents of a specific cell in a spreadsheet

13. **Move Dimension**  
    - Move a dimension (such as rows or columns) within a spreadsheet

14. **List Worksheets**  
    - Retrieve the list of worksheets (sheets/tabs) in a spreadsheet (truncated in source, but implied by the action name)

> Note: The integration exposes a total of **31 Google Sheets actions** as MCP tools; only the above subset is explicitly listed in the provided content.

## Pricing
No pricing information is provided in the available content.
