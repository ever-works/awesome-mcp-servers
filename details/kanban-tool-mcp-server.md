# Kanban Tool MCP Server

## Overview
Kanban Tool MCP Server connects AI or automation agents to Kanban Tool, enabling programmatic access to visual Kanban boards, workflow tracking, and time tracking functionality via Pipedream’s MCP platform.

- **Category:** Project Management MCP Server  
- **Source URL:** https://mcp.pipedream.com/app/kanban_tool  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  

## Features

### Core Capabilities
- Connects to Kanban Tool accounts via MCP
- Provides access to online Kanban boards for visual workflow management
- Supports project progress tracking
- Enables interaction with tasks, subtasks (checklist items), and comments
- Integrates time tracking features available in Kanban Tool
- Can be added to compatible chat clients (e.g., ChatGPT via OpenAI) using the static MCP URL

### Available Tools (Actions)
The server exposes 12 actions as tools for agents or workflows:

1. **Create Task**  
   - Creates a new task on a Kanban board.

2. **Update Task**  
   - Updates an existing task with provided parameters (e.g., fields, status, or other properties supported by Kanban Tool).

3. **Move Task**  
   - Moves a task, typically between columns or positions on a Kanban board.

4. **Get Task Details**  
   - Retrieves details of a selected task.

5. **Find Task**  
   - Finds tasks using specified search parameters.

6. **Delete Task**  
   - Soft-deletes a task (removes it without permanent destruction, subject to Kanban Tool’s retention behavior).

7. **Archive Task**  
   - Archives a task instead of deleting it, moving it out of the active workflow.

8. **Create Subtask (Checklist Item)**  
   - Creates a subtask or checklist item associated with a task.

9. **Update Subtask (Checklist Item)**  
   - Updates an existing subtask with new parameters.

10. **Complete Subtask (Checklist Item)**  
    - Marks a subtask as completed.

11. **Delete Subtask (Checklist Item)**  
    - Soft-deletes a subtask or checklist item.

12. **Create Comment**  
    - Creates a comment, typically attached to a specific task.

### Configuration & Integration
- Uses a **static MCP server URL** (`https://mcp.pipedream.net/v2`) for all clients; authentication occurs when adding the server.
- Can be configured through Pipedream’s MCP configuration flow.
- Supports integration into chat clients (e.g., ChatGPT) where agents can call the above tools.

## Pricing
Pricing information for the Kanban Tool MCP Server is **not provided** in the available content.