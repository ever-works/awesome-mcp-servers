# Google Photos MCP Server

## Overview
The Google Photos MCP Server is a Model Context Protocol (MCP) server that connects AI agents and chat clients to Google Photos via Pipedream. It enables browsing, managing, and organizing photo and video libraries directly from compatible MCP-enabled applications.

- **Category:** File Management MCP Servers
- **Brand:** Google
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP integration for Google Photos**
  - Exposes Google Photos functionality as MCP tools/actions.
  - Usable from multiple MCP-compatible chat clients via a single static server URL.

- **Account connection & configuration**
  - Connect a Google Photos account through Pipedream.
  - Configure the MCP server once and reuse it across supported clients.

- **Upload Item**
  - Upload photos or videos to a connected Google Photos library.
  - Uses the `upload-item` action.

- **Share Album**
  - Make an album shareable.
  - Returns a share token and shareable URL for the album.
  - Uses the `share-album` action.

- **List Library Contents**
  - Retrieve contents of the Google Photos library.
  - Useful for browsing or programmatically inspecting available media.
  - Uses the `list-library-contents` action.

- **Get Media Item**
  - Retrieve details of a specific media item (photo or video).
  - Uses the `get-media-item` action.

- **Create Album**
  - Create a new album in Google Photos.
  - Uses the `create-album` action.

- **Add Items to Album**
  - Add selected media items to a specified album.
  - Uses the `add-items-to-album` action.

## Technical Details
- **Server URL:** `https://mcp.pipedream.net/v2` (static for all clients; authentication handled when adding to the application).
- **Client setup:** Add the MCP server URL to an MCP-compatible chat client and authenticate with Google Photos via Pipedream.

## Pricing
No pricing information is provided in the available content.