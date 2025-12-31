# SmugMug MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** SmugMug

## Overview
SmugMug MCP Server is an MCP-compatible server that connects to SmugMug’s online photo application. It allows MCP clients (such as chat-based tools or other MCP-enabled applications) to programmatically manage and interact with SmugMug photo libraries, images, and albums.

- **Server URL:** `https://mcp.pipedream.net/v2` (static URL, works for all clients; authentication is handled when adding the server to your application)
- **Primary Use Cases:** managing photo and video assets, organizing albums, retrieving user and image data from SmugMug.

## Features

### MCP Integration
- Static MCP server URL usable from any compatible client.
- Designed to be added to chat clients or other MCP-enabled apps for programmatic control of SmugMug resources.

### Available Tools / Actions (7)
1. **Upload Image**  
   - Uploads an image to a specified SmugMug album.
   - Works with photo or video assets stored on SmugMug.

2. **Update Album Image**  
   - Updates an existing image within a SmugMug album.
   - Suitable for modifying or replacing album images programmatically.

3. **Get User Profile**  
   - Retrieves a SmugMug user profile.
   - Profile data can include:
     - Social networking links
     - Biographical text
     - Bio image
     - Cover image

4. **Get Image**  
   - Fetches details for a specific image stored on SmugMug.
   - Supports both photos and videos.

5. **Get Authenticated User**  
   - Returns details about the currently authenticated SmugMug user.
   - Useful for context-aware operations tied to the active account.

6. **Get Album**  
   - Retrieves an album by its ID.
   - Enables inspection or use of album metadata and contents in workflows.

7. **Create Album**  
   - Creates a new SmugMug album programmatically.
   - Useful for automated organization of image libraries.

## Pricing
No pricing information is provided in the available content.

## Integration Notes
- Requires connecting a SmugMug account via the Pipedream-hosted MCP server.
- Configuration guidance is available through the SmugMug MCP configuration page on Pipedream (referenced as the “Configuration page”).