# Eventee MCP Server

## Overview
Eventee MCP Server is a Model Context Protocol (MCP) server integration for Eventee, enabling MCP-compatible clients (such as AI chat applications) to programmatically work with Eventee-hosted events and attendee experiences.

- **Category:** Business & Commerce – MCP Servers
- **Provider / Brand:** Eventee (via Pipedream MCP infrastructure)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP server integration for Eventee**  
  - Exposes Eventee-related capabilities to MCP-compatible clients.
  - Intended to help manage and enhance attendee experiences for events programmatically (based on integration description).

- **Static server endpoint**  
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) for all clients.
  - Authentication occurs when adding the server to each client application.

- **Client-agnostic setup**  
  - Can be added to different MCP chat clients or applications.  
  - Documentation / prompts in UI for: “Select your chat client to learn how to get started.”

- **Configuration via Pipedream**  
  - Connect your Eventee account and select your client in the Pipedream UI.  
  - Central configuration page available (via a “Configuration” link) for managing MCP server settings.

- **Tool / action discovery (MCP tools)**  
  - Supports listing and loading available tools/actions exposed by the Eventee MCP server (shown in UI as “Loading actions… Loading available tools…”).

> Note: The source content does not enumerate specific Eventee actions (e.g., create event, list attendees). The integration description indicates programmatic attendee-experience and event-related management, but individual tool names and parameters are not detailed.

## Intended Use Cases
- Use from compatible MCP chat or agent clients to interact with Eventee data and workflows (e.g., event and attendee-related operations).
- Centralize configuration and authentication to Eventee via Pipedream, then consume the server from multiple clients.

## Pricing
- The provided content does not include any pricing or plan information for the Eventee MCP Server or its usage via Pipedream.

## Technical Details
- **MCP Protocol:** Model Context Protocol server accessed via HTTPS.
- **Endpoint:** `https://mcp.pipedream.net/v2` (static for all clients; per-client authentication required).
- **Host Platform:** Pipedream MCP environment.

## Links
- **Integration page:** https://mcp.pipedream.com/app/eventee
- **Configuration page:** (linked from the UI as “Configuration page”; exact URL not shown in content)
- **Pipedream Terms:** https://pipedream.com/terms
- **Pipedream Privacy Policy:** https://pipedream.com/privacy