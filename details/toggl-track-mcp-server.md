# Toggl Track MCP Server

**Category:** Business & Commerce – MCP Servers  
**Tags:** time-tracking, productivity, reporting

## Description
The Toggl Track MCP Server is a Model Context Protocol (MCP) server that exposes Toggl Track’s time tracking capabilities to MCP-compatible tools. It enables applications (such as chat-based clients) to programmatically log, retrieve, and manage time entries, projects, and clients through a static MCP endpoint.

## MCP Server Endpoint
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- This static URL is used for all clients; authentication is handled when adding the server to your application.

## Features
- **Time Entry Management**
  - **Get Time Entry**: Retrieve details for a specific time entry by ID.
  - **Get Time Entries**: Fetch up to the last 1,000 time entries for an account.
  - **Get Current Time Entry**: Retrieve the currently running time entry, if one is active.

- **Project Management**
  - **Create Project**: Programmatically create new projects in Toggl Track.
  - **Update Project**: Modify existing project details.

- **Client Management**
  - **Create Client**: Create new clients in Toggl Track.
  - **Update Client**: Update information for existing clients.

- **Tooling & Integration**
  - Exposes 7 actions as MCP tools, enabling integration with MCP-compatible chat clients and applications.
  - Configuration via a single static MCP server URL.

## Setup & Configuration
- Connect a Toggl Track account through the Pipedream interface.
- Copy and use the static MCP server URL in your MCP-compatible application.
- Configure and manage usage via the associated configuration pages and documentation links.

## Pricing
Pricing details are not provided in the available content. Use of this MCP server may be subject to Pipedream and Toggl Track account plans and limits.