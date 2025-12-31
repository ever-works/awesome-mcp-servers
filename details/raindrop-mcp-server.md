# Raindrop MCP Server

## Overview
Raindrop MCP Server is a Model Context Protocol (MCP) integration for Raindrop.io provided by Pipedream. It enables AI agents and MCP-compatible chat clients to access and manage Raindrop.io bookmarks, collections, and saved content via a static MCP server URL.

- **Type:** MCP server integration
- **Category:** Content management MCP servers
- **Provider:** Pipedream
- **Service integrated:** Raindrop.io
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration & Access
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across compatible clients.
- Authentication occurs when adding the server to an MCP-enabled application.
- Designed to work with multiple chat / AI clients that support MCP.

### Bookmark Management
- **Get Bookmark** – Retrieve detailed information for a bookmark by ID.
- **Update Bookmark** – Modify properties of an existing bookmark.
- **Delete Bookmark** – Remove a bookmark from Raindrop.io.
- **Save to Raindrop Collection** – Receive a URL and save it directly into a specified collection.
- **Retrieve Bookmarks from Collection** – List all bookmarks contained in a given collection.

### Collection Management
- **Retrieve All Collections** – Fetch all collections in a Raindrop.io account.
- **Get Collection** – Retrieve details of a specific collection.
- **Create New Collection** – Create an additional Raindrop.io collection.
- **Update Collection** – Edit an existing collection’s properties.
- **Delete Collection** – Remove a collection from Raindrop.io.

### Import & Parsing
- **Parse HTML Bookmark File** – Convert an HTML bookmark export file to JSON.
  - Supports Netscape-format bookmark files.
  - Supports Pocket and Instapaper bookmark export formats.

## Tags
- bookmark-management  
- collections  
- content-organization

## Pricing
Pricing information is not provided in the available content. Users should refer to Pipedream or Raindrop.io directly for any pricing or usage limits related to this MCP server.