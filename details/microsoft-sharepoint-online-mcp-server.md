# Microsoft SharePoint Online MCP Server

## Overview
The Microsoft SharePoint Online MCP Server is an MCP-compatible integration (via Pipedream) that allows AI agents and MCP-enabled clients to interact with SharePoint Online and related OneDrive-backed content. It focuses on sharing and managing content, knowledge, and applications and supports common file, folder, list, and item operations.

- **Category:** Content Management MCP Servers  
- **Brand:** Microsoft  
- **Server URL (MCP endpoint):** `https://mcp.pipedream.net/v2`  
- **Source URL:** https://mcp.pipedream.com/app/sharepoint

## Features

### MCP Integration
- Exposes SharePoint and OneDrive operations as MCP tools/actions.  
- Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.  
- Authentication occurs when adding/configuring the server in your MCP-compatible application or chat client.

### Content & File Management
- **Upload File**  
  - Upload a file to OneDrive (backing storage for SharePoint content in many scenarios).
- **List Files in Folder**  
  - Retrieve a list of files and/or folders directly within a specified folder.  
- **Get File by ID**  
  - Retrieve a file from SharePoint by its unique ID.  
- **Find File by Name**  
  - Search for a file or folder by name in SharePoint.  
- **Download File**  
  - Download a SharePoint file to the `/tmp` directory (useful for processing within automations or agents).
- **Create Folder**  
  - Create a new folder in SharePoint.

### List & Item Management
- **Create List**  
  - Create a new list in Microsoft SharePoint.  
- **Create Item**  
  - Create a new item in a SharePoint list or library.  
- **Update Item**  
  - Update an existing item in Microsoft SharePoint.

### Sharing & Collaboration
- **Create Link**  
  - Create a sharing link for a `DriveItem` (file or folder), enabling controlled sharing/collaboration scenarios.

### Excel Integration
- **Get Excel Table**  
  - Retrieve a table from an Excel spreadsheet stored in SharePoint, enabling structured data access for agents.

## Configuration
- Connect a Microsoft SharePoint account within Pipedream.  
- Use the provided static MCP server URL when adding the server to your MCP-compatible chat client or application.  
- Client-specific setup instructions are available via Pipedream’s configuration documentation.

## Pricing
Pricing information is not provided in the available content. Refer to the source URL or Pipedream’s website for current pricing details.