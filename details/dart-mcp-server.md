# Dart MCP Server

AI-connected MCP server for integrating Dart, an AI-driven project management platform, into MCP-compatible chat and agent applications.

- **Category:** Project Management MCP Servers  
- **Vendor / Brand:** dart (via Pipedream)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Use Case:** Enable AI tools and chat clients to work with Dart projects, tasks, and docs through MCP tools.

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all Dart clients.
- Authenticates when the server is added to an MCP-compatible application or chat client.
- Can be configured via supported chat clients or the full configuration page on Pipedream.

### Task Management Tools
- **Create Task**  
  - Creates a new task within a specified Dart "dartboard" (project/board).
- **Find or Create Task**  
  - Searches for an existing task in a dartboard using a task name.  
  - If the task does not exist, automatically creates a new one.
- **Update Task**  
  - Updates an existing task within a dartboard.
  - Allows modifying stored task properties (details available in the linked action documentation).

### Document Management Tools
- **Create Doc**  
  - Records a new doc that the user intends to write down.  
  - Saves the doc in Dart for later access and search.  
  - By default, stores new docs in the Docs folder.  
  - Can include additional information in the text body.
- **Update Doc**  
  - Updates selected properties of an existing doc in Dart.  
  - Only specified properties are changed; unspecified properties remain as-is.  
  - Updated docs remain available for later access and search.
- **Delete Doc**  
  - Moves an existing doc to the trash.  
  - The doc can be recovered later if needed.  
  - No other properties of the doc are modified.

### Tool Coverage
- Provides **6 actions** as MCP tools:  
  1. Create Task  
  2. Find or Create Task  
  3. Update Task  
  4. Create Doc  
  5. Update Doc  
  6. Delete Doc

## Pricing

The provided content does not list any pricing or plans for the Dart MCP Server. Pricing details (if any) would need to be obtained from the main Dart or Pipedream site.