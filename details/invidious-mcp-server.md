# Invidious MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** invidious  
**Slug:** `invidious-mcp-server`

Invidious MCP Server exposes the Invidious open‑source YouTube front‑end via the Model Context Protocol (MCP), enabling applications and AI assistants to perform video search and retrieval against YouTube content through an Invidious instance.

---

## Features

- **Invidious integration**
  - Connects to Invidious, an open‑source alternative front‑end for YouTube.
  - Enables interaction with YouTube content without using the official YouTube front‑end directly.

- **MCP-compatible server**
  - Implements the Model Context Protocol (MCP) for standardized tool access from compatible clients.
  - Exposes Invidious video search and retrieval capabilities as MCP tools.

- **Video search & retrieval**
  - Supports video search tasks via Invidious.
  - Supports retrieval of video information/metadata using Invidious as the backend.

- **Static MCP endpoint**
  - Server URL: `https://mcp.pipedream.net/v2` (static for all MCP clients).
  - Same endpoint usable across different MCP‑compatible chat or agent clients.

- **Client-agnostic setup**
  - Can be added to any MCP‑compatible chat client or application.
  - Configuration guidance available via a central configuration page (client-specific instructions).

- **Hosted by Pipedream Connect**
  - Runs as a managed MCP server hosted on Pipedream’s infrastructure.
  - Authentication is handled when adding the server to your application.

---

## Setup & Usage

1. Configure `https://mcp.pipedream.net/v2` as an MCP server in your compatible client.
2. Authenticate when prompted by the client or application.
3. Use the provided MCP tools to perform Invidious-backed video search and video data retrieval.

---

## Pricing

The provided content does not specify any pricing or plans for the Invidious MCP Server. Pricing details, if any, are not available in the supplied information.