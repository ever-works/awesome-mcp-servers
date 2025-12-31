# Status Hero MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Pipedream  
**Source:** https://mcp.pipedream.com/app/status_hero

## Overview
The Status Hero MCP Server allows MCP-compatible clients (such as ChatGPT) to interact programmatically with Status Hero, a work communication tool focused on asynchronous status reporting. It enables teams to manage status-related workflows—like time off and holidays—directly from their MCP clients instead of relying on meetings or manual updates.

## Features
- **Static MCP Server Endpoint**  
  - Single, static server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication performed when adding the server to your MCP-compatible application.

- **MCP Client Integration**  
  - Works with MCP clients such as ChatGPT (OpenAI).  
  - Setup guidance available via a dedicated configuration guide and a broader configuration page.

- **Available Tools (Actions)**  
  The server currently exposes two primary Status Hero actions as MCP tools:
  - **Record Member Absence**  
    - Creates a vacation or leave day for an individual team member.  
    - Intended for managing personal time off / unavailability records in Status Hero.
  - **Create Team Holiday**  
    - Creates a team‑wide holiday entry.  
    - Useful for marking organization- or team-level days off.

- **Workflow & Use Cases**  
  - Programmatically manage:
    - Individual absences (vacation, leave days).  
    - Shared holidays that affect entire teams.
  - Supports asynchronous communication practices by keeping availability and holidays in sync without meetings.

## Integration & Configuration
- Sign in with a Status Hero–connected Pipedream account to configure and manage access.  
- Add the static MCP server URL to your MCP-capable chat client and authenticate during setup.  
- Client-specific setup instructions are available (e.g., for ChatGPT) via linked guides.

## Pricing
The provided content does not contain any pricing or plan information for the Status Hero MCP Server.