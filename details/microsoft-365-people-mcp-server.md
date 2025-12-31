# Microsoft 365 People MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Microsoft  
**Slug:** microsoft-365-people-mcp-server

## Overview
The Microsoft 365 People MCP Server is an MCP-compatible service that connects to Microsoft 365 People, enabling MCP clients and chat-based tools to create, view, and manage contacts, contact lists, and groups within a Microsoft 365 account.

## Features
- **Microsoft 365 People integration**
  - Interfaces directly with Microsoft 365 People APIs
  - Operates within a Microsoft 365 account context

- **Contact management**
  - Create new contacts
  - View existing contacts
  - Edit/update contact details

- **Contact list management**
  - Create contact lists
  - View existing contact lists
  - Manage membership in contact lists (via create/edit capabilities)

- **Group management**
  - Create groups in Microsoft 365
  - View existing groups
  - Edit group details and membership (via create/edit capabilities)

- **MCP server compatibility**
  - Exposes functionality as an MCP Server for use by MCP-compatible clients
  - Suitable for chat-based and tool-using applications that support MCP

- **Static server URL**
  - Single static MCP endpoint for all clients: `https://mcp.pipedream.net/v2`
  - Same URL reused across different MCP clients

- **Authentication at client setup**
  - Authentication performed when the server is added to an application/client
  - Works with each user’s Microsoft 365 account context

## Technical Details
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Protocol:** MCP Server (Model Context Protocol)  
- **Integration scope:** Microsoft 365 People (contacts, lists, groups)

## Tags
- contacts  
- microsoft-365  
- directory

## Pricing
Pricing information is not provided in the available content.