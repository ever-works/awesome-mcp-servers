# Dropbox MCP Server

An MCP server that connects to Dropbox to provide secure file storage, access, and management from MCP-aware applications and agents.

---

## Overview

- **Category:** File Management MCP Servers  
- **Provider / Brand:** Dropbox (via Pipedream MCP)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Purpose:** Enable applications and agents to securely access, upload, download, search, and organize Dropbox files and folders through MCP tools.

---

## Features

### MCP Integration
- Static MCP server URL usable across compatible clients.
- Authentication occurs when adding the server to the client/application.
- Designed for MCP-aware chat and agent clients (configuration guided per client).

### File Upload & Creation
- **Upload Multiple Files**  
  Upload multiple files into a selected Dropbox folder in one operation.
- **Upload a File**  
  Upload a single file to a specified Dropbox folder.

### File & Folder Discovery
- **Search Files and Folders**  
  Search for files and folders by name within Dropbox.
- **List All Files/Subfolders in a Folder**  
  Retrieve a list of files and/or subfolders in a specified folder.

### File Versioning & Recovery
- **List File Revisions**  
  Retrieve a list of revisions for a file, useful for recovering previous content.
- **Restore a File**  
  Restore a previous version of a file using available revisions.

### File & Folder Management
- **Rename a File/Folder**  
  Rename an existing file or folder in the user’s Dropbox.
- **Move a File/Folder**  
  Move a file or folder to a different location/path in Dropbox.
- **Delete a File/Folder**  
  Permanently remove a file or folder from Dropbox.

### Sharing & Link Management
- **List Shared Links**  
  Retrieve all shared links associated with a given path.
- **Get Shared Link Metadata**  
  Retrieve metadata for a specific shared link (e.g., target, type).
- **Get Shared Link File**  
  Download or access the file referenced by a shared link.
- **Create/Update a Share Link**  
  Create a new public share link or update an existing one for a file or folder, allowing it to be shared with others.

### File Download
- **Download File to TMP**  
  Download a specific file from Dropbox into a temporary directory for use by the client or agent.

> Note: The site states there are **17 actions available as tools**; only those explicitly listed above are described in the provided content.

---

## Configuration

- Connect a Dropbox account via Pipedream’s MCP integration.
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server in your MCP-aware client and authenticate when prompted.
- Additional client-specific setup instructions are available on the referenced configuration page (not included in the provided content).

---

## Pricing

- No pricing information for the Dropbox MCP Server is provided in the supplied content.