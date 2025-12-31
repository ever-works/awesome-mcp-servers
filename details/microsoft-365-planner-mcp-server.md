# Microsoft 365 Planner MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Microsoft  
**Source:** https://mcp.pipedream.com/app/microsoft_365_planner

## Overview
Microsoft 365 Planner MCP Server exposes Microsoft 365 Planner’s simple, visual task and teamwork organization capabilities through the Model Context Protocol (MCP). It allows MCP-compatible clients (e.g., AI chat applications) to interact with Planner via a static MCP endpoint.

## Features
- **MCP-based access to Microsoft 365 Planner**  
  - Integrates Planner with any MCP-compatible client or application.  
  - Provides a uniform interface for Planner data and actions through MCP.

- **Static MCP server endpoint**  
  - Single URL for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Same endpoint can be reused across different MCP-enabled tools and chat clients.

- **Authentication at client setup**  
  - Authentication occurs when adding the server to the application/client (exact auth mechanism depends on the client and configuration).

- **Planner-oriented task and teamwork organization**  
  - Designed for working with Microsoft 365 Planner’s task boards and visual planning workflows.  
  - Suitable for organizing and managing team tasks in a structured, visual way from within MCP-aware tools.

- **Client-agnostic integration**  
  - Can be added to multiple chat or MCP clients.  
  - Documentation and setup guidance available via the provider’s configuration page.

## Usage
- Use the static MCP URL `https://mcp.pipedream.net/v2` as the server endpoint when configuring your MCP-compatible client.
- Complete authentication during the add/connect flow in your chosen client.
- Once connected, interact with Microsoft 365 Planner resources via the MCP server according to your client’s capabilities.

## Pricing
- Not specified in the provided content. Refer to the source page or provider for current pricing details.