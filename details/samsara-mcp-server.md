# Samsara MCP Server

**Category:** Business & Commerce / MCP Servers  
**Brand:** Samsara  
**Source:** https://mcp.pipedream.com/app/samsara

Samsara MCP Server is a Model Context Protocol (MCP) server that connects AI applications to Samsara’s Connected Operations Cloud. It allows AI agents or chat clients to interact with Samsara data and workflows, particularly around fleet and operations management.

---

## Features

### MCP Server & Integration
- Provides a static MCP server endpoint: `https://mcp.pipedream.net/v2`.
- Designed to be added to compatible chat clients or AI applications as a Model Context Protocol server.
- Authentication handled when adding the server to the application (per-client authentication flow).
- Works across different clients using the same base MCP server URL.

### Samsara Account Connection
- Connects to a Samsara account to access organization-level data.
- Requires signing in and selecting the relevant client / organization to manage.
- Intended to integrate Samsara’s Connected Operations Cloud with AI-driven workflows.

### Available Tools (Actions)
Currently exposes 3 actions as MCP tools:

1. **Create Route**
   - Generates a new route to an existing address in Samsara.
   - Requires a destination address and related route properties.
   - Prerequisite: address must already exist in the address book.
   - If the location does not exist, it must be created first using the `create-address` action.

2. **Create Contact**
   - Adds a new contact to the organization.
   - Uses Samsara’s contacts model; details configured via action props (as defined in the GitHub component).

3. **Create Address**
   - Adds a new address to the organization’s address book.
   - Requires key properties such as:
     - Formatted address
     - Geofence information (where applicable)
     - Name of the address/location

### Operational Context
- Built to interface with Samsara’s Connected Operations Cloud, which covers fleet, safety, and broader operations data.
- Intended for use in AI-driven workflows, such as assistant-style tools that need to:
  - Create and manage fleet routes.
  - Maintain address books and geofences.
  - Manage contacts associated with operations.

---

## Pricing

The provided content does not include any pricing information or plan details for the Samsara MCP Server via Pipedream.