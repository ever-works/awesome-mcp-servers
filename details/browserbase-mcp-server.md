# Browserbase MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Tags:** browser-automation, web-scraping, web

## Overview
The Browserbase MCP Server provides a controllable web browser environment for AI agents and MCP-based applications. It is exposed as a static MCP endpoint that tools and chat clients can connect to in order to programmatically manage Browserbase resources and sessions.

- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Provider:** Pipedream (Browserbase integration)

## Features

### MCP Integration
- Static MCP server URL that works for all compatible MCP clients.
- Authentication handled when adding the server to your application or client.
- Compatible with chat-based clients such as ChatGPT (OpenAI) via configuration guides.

### Browserbase Resource Management Tools
The MCP server exposes 3 primary actions as tools:

1. **List Projects**  
   - Lists all projects in your Browserbase account.  
   - Useful for discovering available Browserbase projects programmatically.  
   - Action reference: `list-projects` (see linked component file in the docs).

2. **Create Session**  
   - Creates a new browser session with specified settings.  
   - Enables AI agents and applications to spin up a controllable browser environment on demand.  
   - Supports configuration of session parameters (per Browserbase API / action definition).

3. **Create Context**  
   - Creates a new context in Browserbase.  
   - Allows separation or scoping of browser work (e.g., different tasks, environments, or logical groupings) via contexts.  

### AI & Application Use Cases
- Operate a web browser environment programmatically from AI agents.  
- Integrate Browserbase capabilities into MCP-based applications and workflows.  
- Use for tasks such as browsing, automation, and web-based interactions within an AI-driven context (subject to Browserbase capabilities and configuration).

## Configuration & Setup
- Connect a Browserbase account via the Pipedream MCP interface.  
- Sign in to manage Browserbase accounts and link them to your MCP client.  
- Add the MCP server URL to your client configuration and follow the relevant setup guide (e.g., ChatGPT / OpenAI guide or general MCP configuration page).

## Pricing
The provided content does not include any pricing information for the Browserbase MCP Server or Browserbase usage. Refer to Browserbase and/or Pipedream documentation or billing pages for details on plans and costs.