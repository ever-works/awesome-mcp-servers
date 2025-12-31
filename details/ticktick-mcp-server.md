# TickTick MCP Server

## Overview
The TickTick MCP Server exposes TickTick’s task and productivity modules to MCP-based AI clients and workflows. It lets you connect a TickTick account and control tasks and projects directly from compatible chat or MCP-enabled applications.

- **Category:** Project Management MCP Server
- **Provider / Brand:** Pipedream
- **Integrates with:** TickTick
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across supported MCP clients.
- Authentication handled when adding the server to an MCP-enabled application.
- Configuration guidance available for multiple chat clients (e.g., ChatGPT / OpenAI) via Pipedream’s configuration docs.

### TickTick Capabilities Exposed
The server surfaces core TickTick modules and data for AI workflows, including:
- Tasks
- Calendar
- Eisenhower Matrix
- Pomodoro
- Habit Tracker

> Note: The UI and description explicitly mention these modules as part of TickTick; the current MCP tools focus on task and project operations.

### Available Tools (Actions)
The following actions are available as tools in MCP-compatible clients:

1. **Create a Task**  
   - Create a new task in a connected TickTick account.

2. **Update a Task**  
   - Modify properties of an existing TickTick task.

3. **Complete a Task**  
   - Mark an existing TickTick task as completed.

4. **List Projects**  
   - Retrieve all projects in a TickTick account.

These tools allow AI agents or workflows to programmatically manage tasks and projects within TickTick.

## Pricing
No pricing information is provided on the referenced page for the TickTick MCP Server specifically. Pricing, if any, would need to be obtained from Pipedream or TickTick directly.