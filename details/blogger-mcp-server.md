# Blogger MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Google  
**Platform:** Pipedream / Model Context Protocol (MCP)

## Overview
The **Blogger MCP Server** exposes Google’s Blogger platform to MCP-compatible clients, enabling programmatic blogging and content management operations (such as creating, publishing, updating, reverting, and deleting posts) directly from chat-based or other MCP-enabled applications.

## MCP Server Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
  This is a static URL usable across supported MCP clients; authentication occurs when adding the server in your application.
- **Usage:** Add this server URL to your MCP-compatible client (e.g., ChatGPT with MCP support) and authenticate with your Blogger account.

## Features

### Blogger Integration
- Connect a Google Blogger account through Pipedream’s Blogger MCP Server.
- Manage blog posts programmatically from MCP clients.
- Supports both draft and published posts.

### Available Tools (Actions)
The server currently exposes **5 actions** as tools:

1. **Create a Post**
   - Creates and publishes a new post, **or**
   - Creates a new post as a draft.

2. **Publish a Post**
   - Publishes an existing draft post.

3. **Update a Post**
   - Updates an existing published post.

4. **Revert a Post**
   - Reverts a published or scheduled post back to **draft** state.

5. **Delete a Post**
   - Permanently removes a post.
   - Deleted posts **cannot be restored**.

### Client Compatibility & Configuration
- Designed for MCP clients (e.g., ChatGPT with MCP support).
- Static MCP server URL works across clients; configuration details available via Pipedream’s configuration docs.
- Authentication handled when connecting your Blogger account after adding the server.

## Use Cases
- Drafting and publishing blog posts directly from a chat interface.
- Programmatically updating or reverting scheduled posts.
- Automated content workflows that create drafts then publish after review.
- Safely managing post lifecycle (create → draft → publish → update → revert → delete).

## Pricing
The provided content does **not** specify any pricing or plans for the Blogger MCP Server. Consult the main Pipedream platform or billing documentation for current pricing details, if any apply.