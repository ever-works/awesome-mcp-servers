# Twitch MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** Twitch  
**Slug:** `twitch-mcp-server`

Twitch MCP Server exposes Twitch’s livestreaming and channel-management APIs as MCP tools, allowing MCP-compatible applications (such as AI assistants or chat clients) to interact programmatically with Twitch.

---

## Overview

- **Description:** An MCP Server for Twitch that lets MCP-compatible clients integrate with Twitch’s livestreaming platform and related APIs through a single static MCP endpoint.
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the server to your MCP-compatible application (via your Twitch account connection).

---

## Features

### MCP Integration
- Single static MCP server URL usable across different MCP clients.
- Designed for chat and agent-style clients that support MCP.
- Uses your authenticated Twitch account to perform actions on your behalf.

### Available Tools / Actions (17 total)

Below are the documented actions exposed as tools by the Twitch MCP Server:

1. **Update Channel**  
   - Update metadata for the channel owned by the authenticated user.  
   - At least one parameter must be provided (e.g., title, category/game, language, etc.).

2. **Unblock User**  
   - Remove a specified target user from the authenticated user’s block list.

3. **Search Games**  
   - Search games using a query string.  
   - Matches on full or partial text in game name or channel description.

4. **Search Channels**  
   - Return channels whose name or description partially or fully matches a query.  
   - Includes both live and offline channels.  
   - Limited to users who have streamed within the last 6 months.

5. **Get Videos**  
   - Retrieve video information by:
     - Video ID
     - User ID
     - Game ID

6. **Get Users**  
   - Fetch user objects for specified Twitch login names.

7. **Get Top Games**  
   - List games sorted by current viewer count (most popular first).

8. **Get Stream By User**  
   - Get stream information (stream object) for a specified user.

9. **Get Followed Channels**  
   - Retrieve a list of channels followed by the authenticated user.

10. **Get Clips**  
    - Retrieve clip information by:
      - Clip ID
      - User ID
      - Game ID

11. **Get Channel Teams**  
    - Get a list of teams that a specified channel belongs to.

12. **Get Channel Information**  
    - Retrieve detailed information about a specific broadcaster’s channel.

13. **Get Channel Followers**  
    - Retrieve a list of users who follow the authenticated user.

14. **Get Channel Editors**  
    - Get a list of users who are editors for the authenticated user’s channel.

> Note: The page states **17 actions available as tools**. Only 13 are explicitly listed in the provided content; additional actions may exist but are not visible in the supplied text.

---

## Configuration

- Connect your Twitch account within the hosting platform (Pipedream MCP environment) to authorize API access. 
- Add the MCP server URL to your MCP-compatible application and complete the authentication flow.
- Client-specific setup instructions are available via the “Configuration” page referenced in the source.

---

## Pricing

- No pricing information is provided in the supplied content.

---

## Links & Assets

- **Source / App URL:** https://mcp.pipedream.com/app/twitch  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Brand Logo:** https://static.twitchcdn.net/assets/favicon-32-e29e246c157142c94346.png  
- **Image:** https://static.twitchcdn.net/assets/og-image-fb.png

---

## Tags

- `streaming`
- `social-media`
- `api-integration`