# Productive.io MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Productive.io  
**Source:** https://mcp.pipedream.com/app/productive_io

## Overview
The Productive.io MCP Server integrates the Productive agency management platform into MCP-compatible chat clients and applications. It lets you connect a Productive account and perform key operations like creating tasks, contacts, and bookings directly from your MCP environment.

## Features
- **Static MCP Server URL**  
  - Single endpoint for all clients: `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to your application.

- **Account Connection**  
  - Connect a Productive.io account via the Pipedream interface.  
  - Select a client within Productive after connecting.  
  - Sign-in-based authorization flow for managing accounts.

- **Available Tools (Actions)**  
  - **Create Task**  
    - Create a new task in Productive from your MCP client.  
    - Uses Productive’s task creation API (details in linked documentation).  
  - **Create Contact**  
    - Create a new contact entry in Productive.io.  
    - Suitable for adding people or client contacts from chat-based workflows.  
  - **Create Booking**  
    - Create a new booking in Productive (e.g., for scheduling or resource allocation).  
    - Integrates resource planning actions into MCP workflows.

- **Client Integration**  
  - Can be added to supported MCP-compatible chat clients such as ChatGPT (OpenAI).  
  - Configuration guidance available via the Pipedream configuration page.

## Integration & Configuration
- Use the static URL `https://mcp.pipedream.net/v2` when registering the MCP server in your client.  
- Authenticate via the Pipedream sign-in flow to connect your Productive.io account.  
- After connection, select the appropriate client/account to operate against.  
- Additional configuration instructions are provided on Pipedream’s configuration page.

## Pricing
The provided content does not list any pricing or plan details for the Productive.io MCP Server. Pricing information is not available in the source content.