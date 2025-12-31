# 7todos MCP Server

**Category:** Project Management MCP Servers  
**Brand:** 7todos  
**Source:** https://mcp.pipedream.com/app/seventodos

## Overview
The 7todos MCP Server exposes the 7todos task board platform—designed for indie makers, content creators, and freelancers—through the Model Context Protocol (MCP). It enables applications and chat clients to interact with 7todos for tracking and managing multiple projects and tasks.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for every client; authentication is handled when adding the server to an application.

- **7todos integration**  
  - Connects to a 7todos account to access task boards.  
  - Supports tracking and managing multiple projects.  
  - Oriented toward use cases for indie makers, content creators, and freelancers.

- **Client configuration workflow**  
  - Flow to connect a 7todos account and select a client to get started.  
  - Instructions for adding the MCP server to different chat clients.  
  - Links to a configuration page for more detailed setup.

- **Tool availability via MCP**  
  - Exposes “available tools” (actions) from 7todos through MCP (listed dynamically as “Loading actions / tools…” in the UI).  
  - Designed so applications can call these tools programmatically through the MCP server.

## Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server URL to an MCP-compatible app or chat client.  
- Authenticate when prompted to link your 7todos account.  
- Use the exposed tools/actions to work with tasks and projects stored in 7todos.

## Pricing
No pricing information is provided in the available content.