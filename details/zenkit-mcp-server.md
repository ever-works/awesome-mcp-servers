# Zenkit MCP Server

Productivity and Collaboration Software Suite MCP server that exposes Zenkit’s project and task data to MCP-compatible clients.

- **Category:** Project Management MCP Servers  
- **Provider / Brand:** Pipedream  
- **Source URL:** https://mcp.pipedream.com/app/zenkit  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

---

## Overview
The Zenkit MCP Server provides MCP-based access to Zenkit, enabling AI/chat clients and other MCP-compatible applications to manage Zenkit workspaces, lists (collections), and entries (items) for productivity and collaboration use cases.

---

## Features

### MCP Server & Connectivity
- Static MCP server URL usable across supported MCP clients (`https://mcp.pipedream.net/v2`).
- Authentication handled when adding the server to your client/application.
- Configuration and integration guidance available for ChatGPT (OpenAI) and other MCP-compatible clients via Pipedream’s configuration docs.

### Zenkit Data & Workspace Operations (Tools / Actions)
The server exposes 6 actions as MCP tools:

1. **Update Entry**  
   - Update an existing entry/item in a Zenkit list.  
   - Useful for modifying task details, statuses, fields, or other item properties.

2. **Get User**  
   - Retrieve a user from a Zenkit workspace.  
   - Supports scenarios like checking user information or referencing workspace members.

3. **Get List**  
   - Retrieve a list/collection from a Zenkit workspace.  
   - Enables access to list metadata and structure for project or task boards.

4. **Get Entry**  
   - Retrieve an entry/item from a list on Zenkit.  
   - Useful for reading task or data item details by reference.

5. **Create Entry**  
   - Create a new entry/item in a Zenkit list.  
   - Supports adding new tasks, records, or data items into existing collections.

6. **Add Entry Comment**  
   - Add a comment to an entry/item within a Zenkit list/collection.  
   - Enables collaboration features like discussion or activity logging directly from MCP clients.

---

## Typical Use Cases
- Managing Zenkit tasks and projects from within MCP-enabled chat or agent interfaces.  
- Creating and updating Zenkit entries programmatically via MCP tools.  
- Retrieving lists, entries, and user data to power AI workflows and assistants.  
- Adding comments to Zenkit items for collaboration and activity tracking through chat clients.

---

## Pricing
No specific pricing information for the Zenkit MCP Server is provided in the referenced content. Pricing, if applicable, would follow Pipedream and/or Zenkit account terms.