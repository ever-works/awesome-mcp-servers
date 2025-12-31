# Twenty MCP Server

**Category:** Business & Commerce – MCP Servers  
**Tags:** CRM, open-source, workflow automation

## Overview
Twenty MCP Server connects the Twenty open-source CRM platform with MCP-compatible agents (such as chat-based clients), allowing you to manage and automate customer relationship management (CRM) workflows programmatically.

## Features
- **MCP-compatible endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL used for all clients; authentication occurs when adding the server to your application.

- **Chat client integration**  
  - Can be added to supported chat clients (e.g., ChatGPT via the provided guide).  
  - Uses MCP to expose CRM operations as tools within your chat environment.

- **Twenty CRM connection**  
  - Connects directly to your Twenty account.  
  - Operates on your selected Twenty client / workspace to manage CRM data.

- **Available tools (actions)**  
  - **Create, Update, or Delete a Record in Twenty**  
    - Perform create, update, or delete on a single record.  
    - Action type is specified dynamically at runtime.  
    - Supports flexible handling of records in the Twenty CRM (e.g., contacts, companies, or other CRM objects as defined in Twenty).  
    - Documentation available via the linked action file in the Twenty integration repository.

## Usage
1. Sign in to Pipedream / MCP and connect your Twenty account.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this server URL to your MCP-compatible client (e.g., ChatGPT) following its configuration guide.  
4. Use the exposed tools to programmatically manage Twenty CRM records from within your client.

## Pricing
No pricing information is provided in the available content.