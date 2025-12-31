# Kontent.ai MCP Server

An MCP (Model Context Protocol) server that connects to Kontent.ai’s headless CMS, enabling management and governance of content experiences via MCP-compatible clients.

---

## Overview
- **Type:** MCP Server for a headless CMS
- **Platform:** Kontent.ai (headless CMS)
- **Provider / Host:** Pipedream Connect
- **Category:** Content management MCP servers
- **Primary Use Case:** Accessing and managing content stored in Kontent.ai from MCP-enabled applications (e.g., chat clients / AI tools).

---

## Features

- **MCP access to Kontent.ai**  
  Provides an MCP endpoint that exposes Kontent.ai’s headless CMS capabilities to MCP-compatible clients.

- **Static MCP Server URL**  
  - Single, static URL for all clients:  
    `https://mcp.pipedream.net/v2`  
  - The same endpoint is used regardless of which compatible client you’re using.

- **Client-agnostic integration**  
  - Designed to be added to any supported chat client or MCP-enabled application.  
  - Documentation points to per-client setup instructions.

- **Authentication at configuration time**  
  - Authentication is performed when adding the server to your client or application (specific auth methods not detailed in the provided content).

- **Headless CMS foundation (via Kontent.ai)**  
  - Built on top of Kontent.ai, a headless CMS used to:  
    - Manage structured content centrally.  
    - Govern content across channels and teams.  
    - Power content delivery for digital experiences.

- **Configuration documentation**  
  - A dedicated configuration page is referenced for full setup and usage details.

---

## Setup

1. **Copy MCP server URL**  
   Use `https://mcp.pipedream.net/v2` as the MCP endpoint.
2. **Add to your client**  
   - Open your MCP-compatible chat client or application.  
   - Add a new MCP server using the URL above.  
   - Authenticate when prompted (details depend on your client and Kontent.ai setup).
3. **Refer to configuration guide**  
   - For specific client instructions, follow the “Configuration” page linked from the product page.

---

## Pricing

- Not specified in the provided content. No plan or pricing details are available from this source.

---

## Links

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Product page:** https://mcp.pipedream.com/app/kontent_ai  
- **Configuration docs:** Linked as “Configuration page” on the product page  
- **Pipedream Connect:** https://pipedream.com/connect  
- **Pipedream Terms:** https://pipedream.com/terms  
- **Pipedream Privacy Policy:** https://pipedream.com/privacy