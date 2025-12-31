# Zoho Projects MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Pipedream  
**Source:** https://mcp.pipedream.com/app/zoho_projects

## Overview
Zoho Projects MCP Server is an MCP (Model Context Protocol) server that lets AI agents and chat-based applications interact with Zoho Projects, Zoho’s online project management platform. It enables programmatic management of projects, tasks, milestones, bugs, files, and time logs within Zoho Projects.

The server is accessed via a static URL and is authenticated when added to a compatible MCP client or application.

- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server & Connection
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable for all Zoho Projects clients.
- Authentication handled when adding the server to your MCP-compatible application or chat client.
- Designed to integrate Zoho Projects capabilities into AI agents and chat-based workflows.

### Available Tools / Actions (9 total)
The Zoho Projects MCP Server exposes 9 actions as tools that AI agents or applications can call:

1. **Upload File**
   - Add a document/file to Zoho Projects.
   - Supports attaching documents to the appropriate context in Zoho Projects (e.g., projects or tasks, as defined by the underlying Zoho API/component).

2. **Update Project**
   - Update an existing project in Zoho Projects.
   - Allows modification of project attributes (such as name, description, or other supported project fields as defined in the Zoho Projects API).

3. **Find Project**
   - Search for projects across the Zoho Projects portal using a search term.
   - Returns both active and archived projects.
   - Results include only projects visible to users with admin privileges, in line with Zoho Projects permissions.

4. **Create Task**
   - Create a new task within a Zoho Projects project.
   - Enables AI agents to add work items and action points directly from conversations or workflows.

5. **Create Task List**
   - Create a new task list in Zoho Projects.
   - Useful for organizing related tasks into structured lists within a project.

6. **Create Project**
   - Create a new project in Zoho Projects.
   - Enables automated or AI-assisted project setup from within an MCP-compatible client.

7. **Create Milestone**
   - Create a milestone within a Zoho Projects project.
   - Allows defining major project checkpoints for planning and tracking.

8. **Create Bug**
   - Create a bug (issue) in Zoho Projects.
   - Supports bug/issue logging as part of a project’s tracking and QA process.

9. **Add Log Time**
   - Add time for a general log entry.
   - Adds time logs to other tasks, supporting time tracking and reporting within projects.

## Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible app or chat client.
- Authenticate with Zoho Projects when prompted by your client.
- Use the exposed tools (actions) to manage projects, tasks, milestones, bugs, files, and time logs programmatically.

## Pricing
No pricing information is provided in the available content.