# Motion MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Motion  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview
Motion MCP Server is an MCP-compatible server that exposes Motion’s calendars, meetings, projects, and tasks to MCP clients. It allows chat-based or MCP-enabled applications to manage Motion tasks and schedules through a set of predefined actions.

## Features
- **MCP protocol integration**
  - Static MCP server URL usable across different MCP clients.
  - Authentication handled when adding the server to an application.

- **Task management actions**
  - **Create Task**
    - Create a new task in Motion via the MCP server.
  - **Retrieve Task**
    - Retrieve a specific task by ID.
  - **Update Task**
    - Update properties of an existing task.
  - **Delete Task**
    - Delete a specific task by ID.
  - **Move Workspace**
    - Move a specific task to another workspace.
    - When moving between workspaces, the task’s project, status, labels, and assignee are reset.

- **Scheduling actions**
  - **Retrieve Schedules**
    - Get a list of schedules for the authenticated user.

- **Client-agnostic setup**
  - Same MCP server URL works for every supported client.
  - Configuration instructions available per chat client via the Pipedream configuration page.

## Use Cases
- Integrate Motion tasks and schedules into MCP-enabled chatbots or assistants.
- Automate task creation, updates, and deletions from conversations.
- Programmatically move tasks across workspaces while managing resets of project/status/labels/assignee.
- Pull user schedules from Motion into other tools or workflows via MCP.

## Pricing
No pricing information for Motion MCP Server is provided in the available content.