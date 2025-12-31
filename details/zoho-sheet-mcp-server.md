# Zoho Sheet MCP Server

## Overview
Zoho Sheet MCP Server is an MCP-compatible integration that connects Zoho Sheet spreadsheets to chat-based or MCP-enabled applications. It enables collaborative spreadsheet use, automated data processing, and AI-assisted analytics through a standard MCP server endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Provider / Brand:** Pipedream  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible Zoho Sheet server**  
  - Exposes Zoho Sheet functionality as tools/actions via the MCP protocol.  
  - Single static MCP server URL usable across clients, with authentication handled in the client.

- **Collaborative spreadsheets**  
  - Designed to work with Zoho Sheet’s collaborative spreadsheets so teams can work on shared data.

- **Automated data processing**  
  - Integrates with Zoho Sheet’s automated data processor to streamline data handling workflows.

- **AI-assisted analytics**  
  - Supports workflows that leverage Zoho Sheet’s AI-assisted data analysis capabilities.

- **Available tools (actions)**  
  1. **Update Row**  
     - Finds a specific row by its index in a worksheet.  
     - Updates the row’s content with new values.
  
  2. **Search and Delete Row**  
     - Searches for a row using specified criteria.  
     - Deletes the matching row once found.
  
  3. **Create Row**  
     - Creates a new row in a specified worksheet.  
     - Appends data into the sheet programmatically.

- **Integration-oriented design**  
  - Built to be used from multiple chat or MCP-enabled clients.  
  - Documentation available for each action via linked source files.

## Setup
- Connect a Zoho Sheet account through Pipedream.  
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible app.  
- Select your chat or MCP client and follow its specific configuration steps (as described on the configuration page).

## Pricing
The provided content does not list any pricing or plans for the Zoho Sheet MCP Server.