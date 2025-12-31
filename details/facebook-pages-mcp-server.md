# Facebook Pages MCP Server

**Category:** Business & Commerce · MCP Servers  
**Brand:** Meta  
**Integration Provider:** Pipedream  
**Slug:** `facebook-pages-mcp-server`

## Overview
Facebook Pages MCP Server is a Model Context Protocol (MCP) integration that exposes Facebook Page management capabilities through a standardized server interface. It allows MCP-compatible tools and chat clients to interact with and manage Facebook Pages, including posts and comments, via a static MCP server URL.

**MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Standardized MCP server endpoint usable across multiple MCP-compatible clients.
- Authentication handled when adding the server to your application or chat client.
- Works with various chat clients that support MCP (configured via each client’s MCP settings).

### Facebook Page Data Access
- **Get Page**: Retrieve details of a specific Facebook Page.

### Post Management
- **Create Post**: Create new posts on a Facebook Page.
- **Update Post**: Update existing posts on a Facebook Page.
- **Get Post**: Retrieve a single post from a Facebook Page.
- **List Posts**: Retrieve a list of posts from a Facebook Page.

### Comment Management
- **Create Comment**: Create new comments on posts on a Facebook Page.
- **Update Comment**: Update existing comments on posts.
- **Get Comment**: Retrieve a specific comment on a Facebook Page post.
- **List Comments**: Retrieve a list of comments on a specific post.

### Tooling
- Exposes **9 actions** as MCP tools that can be invoked programmatically from MCP-compatible environments:
  1. Create Post  
  2. Update Post  
  3. Get Post  
  4. List Posts  
  5. Create Comment  
  6. Update Comment  
  7. Get Comment  
  8. List Comments  
  9. Get Page

## Typical Use Cases
- Manage and schedule posts on Facebook Pages directly from MCP-enabled chat clients or developer tools.
- Review and moderate comments on Page posts through a unified MCP interface.
- Build automations or assistants that can read and write Facebook Page content via MCP.

## Pricing
The provided content does not include any pricing information for the Facebook Pages MCP Server or related Pipedream usage. Pricing, if applicable, would need to be obtained from Pipedream’s main site or account billing pages.