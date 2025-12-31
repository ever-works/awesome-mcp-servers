# OneDesk MCP Server

An MCP server integration that connects OneDesk’s helpdesk and project management platform into MCP-compatible applications for unified customer support and project workflows.

## Overview
- **Type:** MCP Server / Integration
- **Category:** Project Management MCP Servers
- **Integrates:** OneDesk (helpdesk + project management)
- **Provider:** Pipedream
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### Unified Helpdesk & Project Management
- Brings OneDesk’s helpdesk and project management capabilities into MCP environments.
- Enables managing customer support and project tasks from a single MCP-compatible client.

### Available Tools (Actions)
The OneDesk MCP Server exposes 7 actions as tools:

1. **Update Item**
   - Updates an existing item in OneDesk.
   - Supports modifying fields/properties of items such as tasks, tickets, or other work items (per OneDesk’s item model).

2. **Find Project**
   - Searches for a project/space by name or ID.
   - Useful for locating and referencing existing projects from within MCP clients.

3. **Find Item**
   - Searches for an existing item.
   - Helps retrieve tickets, tasks, or other items for viewing or further automation.

4. **Create User**
   - Creates a new user or customer in OneDesk.
   - Supports onboarding new end-users or internal users via MCP workflows.

5. **Create Project**
   - Creates a new project/space.
   - Enables automated project/space creation from MCP clients.

6. **Create Message**
   - Creates a message or comment on an item or relevant entity in OneDesk.
   - Facilitates discussion, notes, or communication directly from MCP workflows.

7. **Create Item**
   - Creates a new item in OneDesk (e.g., task, ticket, or other work item type).
   - Supports capturing new work from chats, agents, or automated flows.

### Configuration & Access
- Uses a static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.
- Authentication occurs when adding the server to the MCP-compatible application.
- Can be added to different chat or MCP clients following their configuration instructions.

## Pricing
- No pricing information is provided in the available content.

## Links
- **Source / Setup Page:** https://mcp.pipedream.com/app/onedesk
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Action Documentation (examples):**
  - Update Item: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/update-item/update-item.mjs
  - Find Project: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/find-project/find-project.mjs
  - Find Item: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/find-item/find-item.mjs
  - Create User: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/create-user/create-user.mjs
  - Create Project: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/create-project/create-project.mjs
  - Create Message: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/create-message/create-message.mjs
  - Create Item: https://github.com/PipedreamHQ/pipedream/blob/master/components/onedesk/actions/create-item/create-item.mjs