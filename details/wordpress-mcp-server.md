# WordPress MCP Server

**Brand:** Pipedream  
**Category:** Content Management MCP Servers  
**Tags:** wordpress, cms, content-management

## Overview
The WordPress MCP Server connects self-hosted WordPress.org sites to Model Context Protocol (MCP) clients. It exposes WordPress content and user management operations as tools, allowing programmatic interaction with posts, users, and media from compatible chat or agent applications.

Static MCP server URL (for all clients):
```text
https://mcp.pipedream.net/v2
```

## Features
- **MCP server for self-hosted WordPress.org**
  - Connects a self-hosted WordPress.org site to MCP-compatible clients.
  - Uses a single static server URL for all clients; authentication occurs when adding the server to each application.

- **Media management**
  - **Upload Media**
    - Upload a media item (e.g., images, files) to the WordPress media library.
    - Returns a media ID that can be used when creating or updating posts.

- **Post management**
  - **Create Post**
    - Programmatically create new WordPress posts.
  - **Update Post**
    - Update an existing post by specifying its post ID.
  - **Search Posts**
    - Search for specific posts based on query parameters.

- **User management**
  - **Create User**
    - Create new WordPress users via the MCP server.
  - **Get User**
    - Retrieve information for a specific user.
  - **Update User**
    - Update information for an existing user.

- **Client integration**
  - Works with multiple MCP-compatible chat or agent clients.
  - Setup flow:
    - Configure your WordPress.org connection in Pipedream.
    - Copy and use the static MCP server URL in your client.

## Available Tools (Actions)
1. Upload Media  
2. Update User  
3. Update Post  
4. Search Posts  
5. Get User  
6. Create User  
7. Create Post

## Pricing
Pricing information is not provided in the available content.