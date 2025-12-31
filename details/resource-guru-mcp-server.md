# Resource Guru MCP Server

## Overview
The Resource Guru MCP Server is an MCP (Model Context Protocol) server that connects AI tools to Resource Guru, enabling resource management, scheduling, and utilization workflows via a static MCP endpoint.

- **Type:** MCP server / integration
- **Category:** Project management / resource management
- **Provider:** Pipedream
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Static MCP Endpoint**  
  - Single, static MCP server URL (`https://mcp.pipedream.net/v2`) used for all clients.  
  - Authentication occurs when adding the server to your application.

- **Resource Guru Integration**  
  - Designed to work with Resource Guru, a resource management and scheduling platform.  
  - Intended to expose Resource Guru actions and tools (e.g., managing resources, schedules, and utilization) via MCP-compatible clients.  
  - Actions and tools are loaded dynamically from the Pipedream-powered MCP server.

- **Client-Agnostic Setup**  
  - Can be added to various chat or MCP-compatible clients.  
  - Documentation available for different chat clients via the configuration flow.

- **Configuration Flow**  
  - Connect a Resource Guru account and select a client to get started.  
  - Guided configuration through a dedicated configuration page on Pipedream.

- **Pipedream-Backed Hosting**  
  - MCP server infrastructure and configuration hosted and managed by Pipedream.

## How It Works
1. Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
2. Add this URL as an MCP server in your chosen client.  
3. Authenticate with your Resource Guru account during setup.  
4. Use the available tools/actions exposed by the server to manage Resource Guru resources and schedules through your AI client.

## Pricing
The provided content does not list any pricing or plans for the Resource Guru MCP Server. Pricing, if any, would need to be obtained from Pipedream or Resource Guru directly.