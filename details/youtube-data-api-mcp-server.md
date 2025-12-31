# YouTube Data API MCP Server

## Overview
The **YouTube Data API MCP Server** (via Pipedream) exposes YouTube Data API operations as MCP tools so applications and chat-based clients can programmatically upload and manage videos, playlists, comments, and channel settings.

- **Type:** MCP server / integration for YouTube Data API
- **Category:** media-processing-mcp-servers
- **Brand:** YouTube
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### General Capabilities
- Connect a YouTube account and use it via MCP-enabled clients.
- Authenticate once when adding the server to your application.
- Provides 18 actions as MCP tools (a subset is listed explicitly below).

### Available Tools / Actions (explicitly listed)
- **Upload Video**  
  Post a video to an authenticated channel.

- **Upload Thumbnail**  
  Upload a custom video thumbnail image and set it for a specific video.  
  • Requires a verified YouTube account.

- **Upload Channel Banner**  
  Upload a channel banner image for the authenticated YouTube channel.

- **Update Video Details**  
  Update a video’s metadata, such as title, description, or other supported properties.

- **Update Playlist**  
  Modify a playlist’s metadata. Examples include:  
  • Change playlist title  
  • Change playlist description  
  • Change playlist privacy status

- **Update Channel**  
  Update channel-level metadata (e.g., channel details/settings exposed by the YouTube Data API).

- **Search Videos**  
  Return a list of videos that match given search parameters.

- **Reply To Comment**  
  Create a reply to an existing comment on YouTube content.

- **List Videos**  
  Return a list of videos matching specified API request parameters.

- **List Playlists**  
  Return a collection of playlists that match specified request parameters.

- **List Playlist Videos**  
  List videos contained in a specified playlist.

- **List Activities**  
  Return a list of channel activity events (e.g., actions or events associated with a channel) that match given criteria.

- **Delete Playlist**  
  Delete a specified playlist (description truncated in source, but identified as a delete action for playlists).

> Note: The page indicates **18 total tools**, but only the above subset is explicitly listed in the provided content.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2` (static for all supported clients).  
- Add this server URL in your MCP-compatible client and authenticate with your YouTube account when prompted.
- Further configuration details are available via the referenced “Configuration” page in the original source.

## Pricing
Pricing information is not provided in the supplied content.