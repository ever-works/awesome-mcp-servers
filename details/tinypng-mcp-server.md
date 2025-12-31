# TinyPNG MCP Server

## Overview
TinyPNG MCP Server is an MCP-compatible integration that exposes the TinyPNG API’s image optimization capabilities—compression, resizing, and format conversion—as tools that can be used directly from MCP-enabled applications and workflows.

## Features
- **Smart lossy compression for PNG, JPEG, and WebP**  
  - Uses TinyPNG’s selective color reduction to minimize file size while maintaining near-original visual quality.  
  - Compresses WebP, JPEG, or PNG images via the TinyPNG API.

- **Image resizing**  
  - Create resized versions of uploaded images.  
  - Accessible as an MCP tool/action (`Resize Image`).

- **Image format conversion**  
  - Convert images to a desired image type using TinyPNG.  
  - Accessible as an MCP tool/action (`Convert Image`).

- **MCP server endpoint**  
  - Single static MCP server URL: `https://mcp.pipedream.net/v2`.  
  - Works for all MCP-compatible clients; authentication occurs when adding the server to the application.

- **MCP client integration**  
  - Designed to be added as a server to various chat or MCP-capable clients.  
  - Central configuration and setup via the Pipedream configuration page.

## Available Tools / Actions
- **Resize Image** – Create resized variants of an uploaded image using TinyPNG.  
- **Convert Image** – Convert images between supported types (e.g., PNG, JPEG, WebP) via TinyPNG.  
- **Compress Image** – Apply TinyPNG’s compression to WebP, JPEG, or PNG files.

## Pricing
- No specific pricing information is provided in the available content. Use of this MCP server is subject to TinyPNG and Pipedream’s underlying service and API pricing/limits.