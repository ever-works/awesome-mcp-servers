# Microsoft OneDrive MCP Server

**Category:** File Management MCP Servers  
**Brand:** Microsoft  
**Source:** https://mcp.pipedream.com/app/microsoft_onedrive

## Overview
The Microsoft OneDrive MCP Server integrates Microsoft OneDrive with the Pipedream MCP ecosystem so AI tools and clients can store, access, search, and share files directly in OneDrive. It exposes a set of OneDrive file and folder operations as MCP tools accessible via a static MCP server URL.

## Features

### MCP Server & Connectivity
- **Static MCP server endpoint:** `https://mcp.pipedream.net/v2` used to connect from any compatible MCP client.
- **Client-agnostic configuration:** Same MCP server URL works for all supported chat / MCP clients; authentication occurs when adding the server to the application.
- **Account-based configuration:** Connect a Microsoft OneDrive account and link it to your chosen MCP client.

### File & Folder Operations (Available Tools)
1. **Upload File**
   - Upload a file to OneDrive.
   - Makes the uploaded file accessible to AI tools through the MCP ecosystem.

2. **List Files in Folder**
   - Retrieve a list of files and/or folders directly within a specified OneDrive folder.
   - Supports inspection of directory contents for browsing or processing.

3. **Get File by ID**
   - Retrieve a specific file using its OneDrive file ID.
   - Useful for precise access when the file identifier is known.

4. **Get Table (Excel in OneDrive)**
   - Retrieve a table from an Excel spreadsheet stored in OneDrive.
   - Enables structured data access (e.g., rows/columns) from Excel workbooks for AI-driven analysis or automation.

5. **Find File by Name**
   - Search for a file or folder in OneDrive by name.
   - Helps locate content without needing explicit IDs or paths.

6. **Download File**
   - Download a file stored in OneDrive.
   - Allows AI tools or clients to read file contents for further processing.

7. **Create Link**
   - Create a sharing link for a OneDrive `DriveItem` (file or folder).
   - Supports sharing and collaboration scenarios where a public or shareable URL is needed.

8. **Create Folder**
   - Create a new folder in a OneDrive drive.
   - Enables programmatic organization of files and directory structures.

## Pricing
No pricing information is provided in the available content.
