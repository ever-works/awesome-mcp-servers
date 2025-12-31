# Paymo MCP Server

## Overview
Paymo MCP Server is an MCP-compatible integration that exposes Paymo’s work and project management capabilities (tasks, time tracking, projects) through an MCP interface, allowing use within compatible chat or agent applications.

- **Name:** Paymo MCP Server  
- **Category:** Project Management MCP Servers  
- **Brand:** Paymo  
- **Integration Host:** Pipedream  
- **Primary Use Cases:** Access and manage tasks, projects, and time tracking data from Paymo via MCP-enabled clients.

## Features
- **MCP Interface for Paymo**  
  - Provides an MCP server endpoint for interacting with Paymo.  
  - Static MCP server URL usable across clients: `https://mcp.pipedream.net/v2`.

- **Authentication Flow**  
  - Connect a Paymo account through Pipedream.  
  - Account verification step (“Checking your account…”) prior to use.  
  - Authentication handled when adding the MCP server to the client application, not via per-client URLs.

- **Client Integration**  
  - Designed to be added as a server to compatible chat or agent applications.  
  - Configuration guidance available per supported chat client (via the configuration page).

- **Access to Paymo Work Management Functions** *(via MCP tools/actions)*  
  - Intended to expose Paymo features such as:  
    - Tasks (task management operations).  
    - Time tracking (recording and accessing tracked time).  
    - Projects (project-level operations and data).  
  - Tools / actions are dynamically loaded (“Available tools – Loading actions…” indicates tool-based access model).

- **Centralized Configuration**  
  - Single static MCP endpoint for all clients, simplifying configuration.  
  - Additional configuration details available from a dedicated configuration page (`/configuration`).

## Pricing
Pricing information for the Paymo MCP Server is not provided in the available content.