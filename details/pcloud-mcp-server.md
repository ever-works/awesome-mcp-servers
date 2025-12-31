# pCloud MCP Server

## Overview
pCloud MCP Server is an MCP-compatible integration that connects MCP clients to pCloud’s secure, encrypted cloud storage. It allows applications and chat-based MCP clients to access, manage, and organize files and folders in a pCloud account through standardized tools.

- **Type:** MCP Server (Developer Tool)
- **Category:** File Management MCP Servers
- **Provider / Platform:** Pipedream
- **Cloud storage backend:** pCloud
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server Integration
- Provides a single static MCP server URL that works across compatible MCP clients.
- Authentication handled when adding the server to an MCP-enabled application.
- Usable with multiple chat clients and tools that support the MCP standard.

### File & Folder Operations (Tools / Actions)
The server exposes 10 actions as tools for working with pCloud:

1. **Upload File**
   - Upload a file to a specified folder in pCloud.

2. **Rename Folder**
   - Change the name of an existing folder.

3. **Rename File**
   - Change the name of an existing file.

4. **Move Folder**
   - Move a folder to a specified destination folder.

5. **Move File**
   - Move a file to a specified destination folder.

6. **List Contents**
   - Retrieve the contents (files and subfolders) of a specified folder.

7. **Download File(s)**
   - Download one or more files into a chosen destination folder.

8. **Create Folder**
   - Create a new folder inside a specified parent folder.

9. **Copy Folder**
   - Copy a folder into a specified destination folder.

10. **Copy File**
    - Copy a file to a specified destination.

### Storage & Security Context
- Built on top of pCloud’s secure, encrypted cloud storage.
- Intended for programmatic and client-based management of files and folders in a pCloud account.

## Configuration
- Connect a pCloud account through Pipedream’s interface.
- Use the static MCP server URL: `https://mcp.pipedream.net/v2` when configuring MCP clients.
- Additional configuration details are available on the Pipedream configuration page for MCP servers.

## Pricing
- No pricing information is provided in the available content. Use of this MCP server and any associated costs would depend on Pipedream’s and pCloud’s pricing, which are not detailed here.