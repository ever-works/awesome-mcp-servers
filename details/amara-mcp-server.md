# Amara MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** Amara  
**Source:** https://mcp.pipedream.com/app/amara

## Overview
Amara MCP Server is an integration that exposes Amara’s caption and subtitle editing and collaboration capabilities as tools to MCP-compatible clients. It connects your Amara account so you can manage videos, subtitles, and teams programmatically from chat or other MCP-enabled applications.

## Features

### MCP Integration
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`
- Works with multiple MCP-compatible chat / app clients
- Authentication handled when adding the server to your application
- Central configuration via the Pipedream Amara configuration page

### Video Management
- **Add Video**: Register/add a new video in Amara.
- **List Videos**: Retrieve a list of videos associated with your Amara account or context.
- **Get Video Details**: Fetch detailed information about a single video.
- **Delete Video**: Remove a video (requires that the video belongs to a team where the user is an admin).

### Subtitle Language Management
- **Create Subtitle Language**: Create a new subtitle language entry for a video.
- **Update Subtitle Language**: Modify settings or metadata for an existing subtitle language.
- **List Video Subtitle Languages**: Get a list of all subtitle languages available for a specific video.
- **Get Subtitle Language Details**: Retrieve detailed information on a specific subtitle language.

### Subtitle Content Operations
- **Add New Subtitles**: Create and add new subtitles for a language.
- **Fetch Subtitles Data**: Retrieve structured subtitle data (e.g., metadata or parsed subtitle information).
- **Fetch Raw Subtitles**: Retrieve raw subtitle files/contents.
- **Delete Subtitles**: Delete all subtitle versions for a particular language.

### Editorial & Actions
- **Perform Action**: Trigger actions on subtitles equivalent to opening the Amara editor, leaving subtitles unchanged, and clicking an action button (e.g., workflow or editor-related operations).

### Team & Collaboration Management
- **List Teams**: List teams associated with the authenticated user or context.
- **Get Team Details**: Fetch details for a specific team.

## Pricing
No pricing information is provided in the available content.
