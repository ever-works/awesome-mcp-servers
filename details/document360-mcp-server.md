# Document360 MCP Server

An MCP server that connects MCP-compatible clients (like ChatGPT) to the Document360 knowledge base platform for managing product documentation and help content.

## Overview
- Integrates Document360 with MCP clients via a static MCP server URL
- Enables retrieval, search, and creation of documentation content stored in Document360
- Uses Pipedream’s infrastructure (`pipedream.net`) as the MCP endpoint

## Features

### MCP Server & Connectivity
- **Static MCP server URL**: `https://mcp.pipedream.net/v2` (works across all supported MCP clients)
- **Authentication at client setup**: You authenticate when adding the server to your MCP-compatible application
- **Client guides**: Specific guidance available for ChatGPT (OpenAI); additional instructions on a central configuration page

### Document360 Content & File Tools
The server exposes four main actions as MCP tools:

1. **Get File Information**
   - Retrieves metadata and information about a file stored in **Document360 Drive**
   - Useful for inspecting stored assets (e.g., attachments, supporting documents) without downloading their contents

2. **Get Article**
   - Fetches an article from Document360
   - Allows MCP clients to:
     - Read existing knowledge base articles
     - Surface help content and product documentation on demand

3. **Drive Search – Files and Folders**
   - Searches **Document360 Drive** for files and folders
   - Enables:
     - Content discovery across stored documentation assets
     - Locating specific files or structured folders by query

4. **Create Document**
   - Creates a new document in Document360 from plain text
   - Supports:
     - Programmatic or AI-assisted generation of new documentation
     - Adding new knowledge base content directly from MCP clients

## Use Cases
- Integrate ChatGPT or other MCP-compatible tools with Document360 to read and manage documentation
- Search Document360 Drive from within an MCP client to find reference material
- Auto-generate or update knowledge base documents using AI-generated text

## Setup
- Sign in with Document360 via the Pipedream MCP interface
- Copy and use `https://mcp.pipedream.net/v2` as the MCP server URL in your client configuration
- Follow the client-specific setup guide (e.g., ChatGPT / OpenAI) or the general configuration page

## Pricing
- No pricing information is provided on the referenced page for this MCP server or integration.