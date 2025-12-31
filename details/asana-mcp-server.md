# Asana MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Asana  
**Website:** https://developers.asana.com/docs/using-asanas-mcp-server  
**MCP Endpoint:** `https://mcp.asana.com/sse`

![Asana Logo](https://asana.com/assets/svg/logo-color.svg)

---

## Overview

Asana MCP Server is an experimental Model Context Protocol (MCP) server that exposes Asana’s Work Graph (projects, tasks, goals, teams, and related data) to external AI assistants and MCP-compatible applications over SSE. It enables AI tools to access and act on Asana data using OAuth 2.1-based authentication.

Typical use cases include:
- Accessing Asana tasks, projects, and related data from compatible AI clients.
- Creating and managing tasks and projects via natural language.
- Generating summaries, reports, and status overviews from Asana data.
- Analyzing project information and obtaining AI-generated suggestions.

Example natural-language requests from an MCP client:
- “Find all my incomplete tasks due this week.”
- “Create a new task in the Marketing project assigned to me.”
- “List all sections in the Product Launch project.”
- “Show me the status of the Q2 Planning project.”

> Note: This is a beta, experimental integration and may contain bugs or unexpected behavior. It is provided on an “as is” basis.

---

## Requirements

To use the Asana MCP Server you need:

1. **MCP-compatible client**  
   - Any client that implements the Model Context Protocol and supports SSE connections.  
   - A partial list of MCP clients is available in Asana’s documentation.

2. **Asana MCP app allowed in your workspace**  
   - The app “Asana MCP” must not be blocked via Asana’s app management settings.  
   - If blocked, users will be prompted to request admin approval when attempting to authorize.

3. **Asana account and authorization**  
   - You must authenticate with your Asana account and grant the integration access to your Asana data via the OAuth-based flow.

4. **OAuth redirect URI allowlist (for client maintainers)**  
   - Some third-party MCP clients may require their redirect URI to be registered in Asana’s allowlist.  
   - Client maintainers should follow the “Integrating with Asana’s MCP Server” guide to register the OAuth redirect URI if needed.

---

## Features

### MCP Server Capabilities

- **Access to Asana Work Graph**  
  Provides structured access to projects, tasks, goals, teams, and related objects in Asana from outside the Asana UI.

- **SSE-based MCP endpoint**  
  - Server available at `https://mcp.asana.com/sse` for MCP clients that use Server-Sent Events.

- **OAuth 2.1 authentication**  
  - Connects an MCP client to a specific Asana user account.  
  - Uses an authorization flow where the user grants the app permission to read and modify their Asana data.

### Available Tools (Tooling Surface)

Asana’s MCP server exposes 30+ tools covering:

1. **Project tracking and status updates**
   - Retrieve project status and metadata.  
   - Fetch current state of specific projects for reporting or dashboards.  
   - Use from AI assistants to answer project health or progress questions.

2. **Task creation and management**
   - Create new tasks via natural-language prompts.  
   - Update existing tasks (e.g., assignee, due date, completion state).  
   - Filter and fetch tasks (e.g., incomplete tasks, tasks due within a time range).  
   - Associate tasks with specific projects or sections.

3. **User information**
   - Query user-related data (e.g., tasks assigned to a given user).  
   - Identify the current user’s workspace context.

4. **Goals and objectives**
   - Retrieve updates related to Asana Goals.  
   - Use AI tools to summarize or report on goal progress.

5. **Team organization**
   - Access team structures and related data used in Asana.  
   - Enable AI-driven workflows that depend on teams and organizational context.

6. **Typeahead and object search**
   - Quick search for Asana objects via typeahead (e.g., finding projects, tasks, sections by partial name).  
   - Useful for resolving natural language references like “Marketing project” or “Product Launch project” into concrete IDs.

### Tool Discovery

- **Dynamic tools listing**  
  - After authentication, clients can call the `tools/list` MCP command.  
  - This returns the current, authoritative list of Asana endpoints and operations available via MCP.  
  - Ensures clients always operate against the latest supported tools without needing static documentation.

- **Alignment with MCP best practices**  
  - Follows the Model Context Protocol’s recommendation to expose tools programmatically rather than hard-coding them.

### Example Integrations

- **Use with Claude.ai**  
  - Supported in Claude’s MCP ecosystem (requires Claude Enterprise or Teams).  
  - Connection typically needs to be set up by a Workspace Owner or Primary Owner in Claude before members can use it.

---

## Authentication & Connection

- **Endpoint:** `https://mcp.asana.com/sse`
- **Protocol:** Model Context Protocol over SSE.
- **Auth:** OAuth-based connection tied to a specific Asana account.
- **App management:**
  - If the “Asana MCP” app is blocked in a domain, users will encounter a prompt to request admin approval when attempting to connect.
- **Redirect URI allowlist:**
  - Some third-party MCP clients must have their OAuth redirect URIs registered with Asana to complete the auth flow.

---

## Pricing

No specific pricing information for the Asana MCP Server is provided in the available content. Usage is subject to the user’s existing Asana plan and any terms associated with the beta MCP integration.

---

## Tags

- project-management  
- tasks  
- collaboration
