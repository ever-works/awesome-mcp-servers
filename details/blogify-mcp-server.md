# Blogify MCP Server

## Overview
Blogify MCP Server is an MCP-compatible integration that connects AI chat clients and tools to Blogify, enabling automatic transformation of content (such as YouTube videos) into blog posts using AI. It is provided via Pipedream as a static MCP server endpoint that can be added to any supported MCP client.

## Key Details
- **Name:** Blogify MCP Server  
- **Category:** Content Management MCP Servers  
- **Provider / Brand:** Blogify (via Pipedream)  
- **Purpose:** Turn various content sources (e.g., YouTube videos) into AI-generated blog posts  
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server**  
  - Exposes a static MCP server URL that can be used with different MCP-capable clients and chat applications.
- **Blogify integration**  
  - Connects an authenticated Blogify account so AI tools can create blog posts via Blogify.
- **Content-to-blog conversion**  
  - Designed to convert content such as YouTube videos into structured blog posts using AI.  
- **Account-based configuration**  
  - Requires connecting a Blogify account, then selecting the appropriate client within the Pipedream interface.
- **Client-agnostic setup**  
  - Same server URL works across supported MCP clients; authentication occurs when the server is added to a given app.
- **Configuration guidance**  
  - Step-by-step instructions available via a configuration page on Pipedream to help add the MCP server to various chat clients.

## Technical Setup
1. **Connect Blogify account** in the Pipedream Blogify MCP interface.  
2. **Copy MCP server URL:** `https://mcp.pipedream.net/v2`.  
3. **Add server to MCP client** (e.g., compatible chat app) using the copied URL.  
4. **Authenticate** when prompted by the client to complete the connection.

## Pricing
No pricing information is provided in the available content.