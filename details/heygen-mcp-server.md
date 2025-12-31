# HeyGen MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** HeyGen  
**Slug:** `heygen-mcp-server`

AI-powered video creation MCP server that lets agents and applications generate and manage HeyGen videos programmatically via a standard MCP endpoint.

---

## Overview

The HeyGen MCP Server exposes HeyGen’s AI video capabilities through a static MCP endpoint hosted by Pipedream. Once connected with a HeyGen account, clients (such as ChatGPT with MCP support) can create and retrieve AI-generated videos directly via tools/actions.

**MCP Server URL**
- Base endpoint (static for all clients):
  - `https://mcp.pipedream.net/v2`

Authentication is performed when adding the server to your MCP-compatible application.

---

## Features

### MCP Integration
- Static MCP server URL usable across different MCP-compatible clients.
- Authentication handled when you add the server to your application.
- Configuration guides available for specific chat clients (e.g., ChatGPT / OpenAI) and a general configuration page.

### Available Tools / Actions
Three actions are exposed as MCP tools:

1. **Retrieve Video Link**
   - Fetches a link for a specific HeyGen video.
   - Intended for accessing or sharing completed HeyGen videos programmatically.

2. **Create Video From Template**
   - Generates a new video from a selected HeyGen template.
   - Lets agents produce templated AI videos at scale using predefined layouts and settings.

3. **Create Talking Photo**
   - Creates a talking photo from a provided image.
   - Converts a static image into an AI-generated talking avatar-style video.

---

## Use Cases
- Programmatic creation of templated marketing or communication videos.
- Automated generation of talking-avatar clips from profile or product images.
- Retrieval and management of existing HeyGen video links inside workflows or chat environments.

---

## Pricing

No specific pricing information for the HeyGen MCP Server is provided in the available content. Use of the server likely depends on:
- HeyGen account/subscription terms, and
- Any applicable Pipedream/Workday usage or platform limits.

For exact pricing, refer to HeyGen and Pipedream official pricing pages.