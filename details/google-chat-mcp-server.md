# Google Chat MCP Server

**Brand:** Pipedream  
**Category:** Messaging MCP Servers  
**Source:** https://mcp.pipedream.com/app/google_chat

## Description
The Google Chat MCP Server is an integration on Pipedream that exposes Google Chat operations as MCP tools, enabling automation of 1:1 and group collaboration workflows through a static MCP server endpoint.

## Features
- **Static MCP Server URL**
  - Single shared MCP endpoint: `https://mcp.pipedream.net/v2`
  - URL works for all supported MCP clients
  - Authentication occurs when adding the server to your application

- **Account Connection & Configuration**
  - Connect a Google Chat account via Pipedream
  - Configure Google Chat access as part of MCP setup
  - Option to follow client-specific setup flows or use a general configuration page

- **Available Tools (Actions)**
  - **List Spaces**
    - Lists spaces the caller is a member of
    - Group chats and DMs are not listed until the first message is sent
  - **List Messages**
    - Lists messages in a space the caller is a member of
    - Includes messages from blocked members and blocked spaces
  - **List Members**
    - Lists memberships in a given space
  - **Get Space**
    - Returns details and metadata for a specific space
  - **Get Message**
    - Returns details about a specific message
  - **Get Member**
    - Returns details about a specific membership in a space
  - **Create Message**
    - Creates and posts a text message in a specified space

- **Use Cases**
  - Automate 1:1 messaging in Google Chat
  - Automate messages and operations in group spaces
  - Build workflows that list, inspect, and manage spaces, messages, and members via MCP-aware clients

## Integration & Access
- Accessible via MCP-compatible clients by adding the static server URL
- Configuration guidance available per client and via a general configuration page

## Pricing
- Not specified in the provided content.