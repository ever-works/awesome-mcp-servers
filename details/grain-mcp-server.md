# Grain MCP Server

MCP Server integration for Grain, allowing MCP clients to access meeting notes, next steps, and automated documentation from recorded calls.

---

## Overview
The Grain MCP Server (via Pipedream) connects MCP-compatible clients (such as ChatGPT) to your Grain account so they can retrieve information from recorded calls, including transcripts and intelligence notes. Grain captures call notes, next steps, and automated meeting documentation and can sync them to tools like Slack and HubSpot.

---

## Features

### MCP Server Endpoint
- Static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- Authentication is handled when you add the server to your MCP-compatible application.

### Integration with MCP Clients
- Works with MCP-enabled chat clients such as ChatGPT (OpenAI).
- Configuration guidance available for adding the server to supported clients.
- Central configuration via Pipedream’s configuration page.

### Grain Call Data Access
- Connects to your Grain account to access recorded calls.
- Supports retrieval of meeting assets such as:
  - Meeting notes
  - Next steps / action items
  - Automated meeting documentation
- Designed to work with downstream tools (e.g., Slack, HubSpot) via Grain’s existing workflows.

### Available Tooling (Actions)
Currently exposes 1 primary action as a tool:

1. **Get Recording**
   - Fetch a specific recording by its Grain recording ID.
   - Optional inclusion of:
     - Full transcript
     - Intelligence notes (Grain-generated insights/notes about the meeting).
   - Implemented via Pipedream’s `get-recording` action.

### Account Connection & Management
- Sign-in flow via Pipedream to connect and manage your Grain account.
- Once connected, your Grain resources become accessible through the MCP server tools.

---

## Category
- Content Extraction & Summarization MCP Server

Tags: `transcript`, `meetings`, `summarization`

---

## Pricing
No pricing information is provided in the available content. Use of this MCP server may depend on pricing and plans for Grain and/or Pipedream, which are not specified here.