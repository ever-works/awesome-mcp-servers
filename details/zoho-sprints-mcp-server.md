# Zoho Sprints MCP Server

Zoho Sprints MCP Server is an MCP-compatible server (by Pipedream) that connects AI agents and chat clients to Zoho Sprints’ agile project management capabilities.

---

## Overview
- **Category:** Project Management MCP Servers  
- **Brand:** Zoho  
- **Provider / Host:** Pipedream  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Primary Use:** Enable AI agents or MCP-compatible chat clients (e.g., ChatGPT) to interact with Zoho Sprints projects and items programmatically.

---

## Features

### MCP Integration
- Static MCP server URL that works for all clients, with authentication handled when adding the server to your application.
- Can be added to MCP-compatible chat clients such as ChatGPT (OpenAI).
- Configuration guidance available via Pipedream’s MCP configuration pages.

### Zoho Sprints Project Management Capabilities (via MCP)
- Connects to Zoho Sprints’ agile project management environment, including:
  - Scrum boards
  - Agile reports
  - Backlogs
  - Timesheets
  - Meetings
  - Dashboards

*(Note: The above are Zoho Sprints core features exposed via the integration; not all are necessarily individual MCP tools yet.)*

### Available Tools (Actions)
Currently exposes three primary actions as MCP tools:

1. **Update Project Status**
   - Changes the status of an existing project in Zoho Sprints.
   - Useful for programmatically moving projects through lifecycle stages from an AI agent or automated workflow.

2. **Delete Item**
   - Removes a specified work item from a Zoho Sprints project.
   - Supported item types: task, story, bug.

3. **Create Item**
   - Creates a new work item in an existing Zoho Sprints project.
   - Supported item types: task, story, bug.

---

## Setup & Usage
- **Connect Account:** Sign in via Pipedream to connect your Zoho Sprints account.
- **Configure Client:** Add the MCP server URL (`https://mcp.pipedream.net/v2`) to your MCP-compatible app and authenticate.
- **Select Tools:** Use the exposed actions (Create Item, Delete Item, Update Project Status) from within your AI/chat environment.

---

## Pricing
The provided content does not list any pricing or plan details for the Zoho Sprints MCP Server. Consult the Pipedream or Zoho Sprints websites for current pricing information.