# Linear MCP Server

An MCP server that connects to Linear via API key, enabling issue tracking, project management, and sprint/bug workflows for software teams.

## Overview

- **Type:** MCP server / integration
- **Category:** Project management MCP servers
- **Authentication:** Linear API key
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### Connectivity & Setup
- Connects to a Linear workspace using an API key.
- Single static MCP server URL that works for all clients.
- Can be added to any compatible chat or MCP-enabled application.

### Issue Management
- **Create Issue**
  - Create new Linear issues.
  - Required: team ID and title.
  - Optional fields: description, assignee, project, state.
  - Returns success status and full issue details.
  - Authenticated via API key.

- **Update Issue**
  - Update existing Linear issues.
  - Supports modifying:
    - Title
    - Description
    - Assignee
    - State
    - Project
    - Team
    - Labels
    - Priority
    - Dates
  - Returns updated issue details.
  - Authenticated via API key.

- **Get Issue**
  - Retrieve a single issue by ID.
  - Returns detailed issue data including:
    - Title and description
    - State
    - Assignee
    - Team
    - Project
    - Labels
    - Timestamps
  - Authenticated via API key.

- **Search Issues**
  - Search issues with multiple filters:
    - Team
    - Project
    - Assignee
    - Labels
    - State
    - Text query
  - Supports:
    - Pagination
    - Ordering
    - Inclusion of archived issues
  - Returns an array of matching issues.
  - Authenticated via API key.

### Team & Project Management
- **Get Teams**
  - Retrieve all teams in a Linear workspace.
  - Returns team objects with details such as ID, name, and key.
  - Supports pagination with configurable limit.
  - Authenticated via API key.

- **List Projects**
  - List projects in Linear.
  - Uses API key authentication (via MCP server).

- **Create Project**
  - Create new projects in Linear.
  - Uses API key authentication (via MCP server).

## Use Cases

- Manage software project issues (create, update, search) directly from MCP-enabled tools.
- Inspect and retrieve detailed issue information by ID.
- Browse and manage teams and projects within a Linear workspace.
- Support sprint planning, bug tracking, and task management workflows through MCP actions.

## Pricing

- No pricing information is provided in the available content. Pricing, if applicable, would need to be checked on the provider’s site.