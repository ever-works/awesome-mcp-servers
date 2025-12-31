# File Store MCP Server

**Category:** File Management MCP Servers  
**Tags:** file-storage, cloud-storage, file-management

## Overview
File Store MCP Server is an MCP server that provides access to File Store cloud storage. It allows MCP-aware applications and workflows to upload, download, and retrieve files as part of automated processes.

## Features
- **MCP server for file storage**: Exposes File Store cloud storage via the Model Context Protocol (MCP) for integration with MCP-aware clients and projects.
- **Cloud file storage backend**: Stores files in a simple cloud-based file store managed by Pipedream.
- **Upload files**: Supports uploading files from MCP-aware projects and workflows to cloud storage.
- **Download files**: Enables retrieval and downloading of previously stored files.
- **Retrieve file data in workflows**: Designed for use in automated workflows that need access to stored files.
- **Static MCP server endpoint**: Uses a single static base URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic URL**: The same URL works for every supported client; configuration is done at the client level.
- **Authentication at configuration time**: Authentication is performed when adding/configuring the MCP server in an application or chat client.
- **Works with multiple chat clients**: Can be added to compatible chat-based or MCP-capable applications (instructions differ per client).
- **Central configuration reference**: A dedicated configuration page provides full setup details for different environments.

## Usage
- Add the MCP server to your MCP-capable app or chat client using the static URL: `https://mcp.pipedream.net/v2`.
- Authenticate when prompted by your client during configuration.
- Use the server within workflows to upload, download, and retrieve files from File Store.

## Pricing
- Not specified in the provided content.