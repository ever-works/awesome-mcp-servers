# Klipy MCP Server

## Overview
Klipy MCP Server exposes Klipy’s library of localized GIFs, stickers, and clips through an MCP (Model Context Protocol) interface, allowing agents and applications to search and retrieve rich media content programmatically.

- **Category:** Media Processing MCP Servers
- **Provider / Brand:** Klipy (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL usable across clients; authentication handled when adding the server to an application.
- Can be added to various chat or agent clients that support MCP.

### Media Search & Discovery
- Access to a large, localized library of:
  - GIFs
  - Stickers
  - Clips
- Search capabilities exposed as MCP tools/actions:
  - **Search Stickers** – search and retrieve stickers from Klipy’s database.
  - **Search GIFs** – search and retrieve GIFs from Klipy’s database.
  - **Search Clips** – search and retrieve clips from Klipy’s database.

### Direct Media Retrieval by Slug
- Lookup of specific media assets using their slug identifiers:
  - **Get Sticker by Slug** – retrieve a specific sticker by slug.
  - **Get GIF by Slug** – retrieve a specific GIF by slug.
  - **Get Clip by Slug** – retrieve a specific clip by slug.

### Tooling
- Total of **6 actions available as MCP tools**:
  - 3 search actions (stickers, GIFs, clips).
  - 3 slug-based retrieval actions (sticker, GIF, clip).

## Configuration
- Connect a Klipy account via Pipedream and select a client to start using the MCP server.
- Full configuration guidance is available on Pipedream’s configuration page (external documentation).

## Pricing
- No pricing information is provided in the available content.

## Links
- **Source / App Page:** https://mcp.pipedream.com/app/klipy
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Action Docs:**
  - Search Stickers: https://github.com/PipedreamHQ/pipedream/blob/master/components/klipy/actions/search-stickers/search-stickers.mjs
  - Search GIFs: https://github.com/PipedreamHQ/pipedream/blob/master/components/klipy/actions/search-gifs/search-gifs.mjs
  - Search Clips: https://github.com/PipedreamHQ/pipedream/blob/master/components/klipy/actions/search-clips/search-clips.mjs
  - Get Sticker by Slug: https://github.com/PipedreamHQ/pipedream/blob/master/components/klipy/actions/get-sticker-by-slug/get-sticker-by-slug.mjs
  - Get GIF by Slug: https://github.com/PipedreamHQ/pipedream/blob/master/components/klipy/actions/get-gif-by-slug/get-gif-by-slug.mjs
  - Get Clip by Slug: https://github.com/PipedreamHQ/pipedream/blob/master/components/klipy/actions/get-clip-by-slug/get-clip-by-slug.mjs