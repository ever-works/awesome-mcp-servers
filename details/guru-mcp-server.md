# Guru MCP Server

**Category:** Documentation & Learning Resources  
**Tags:** knowledge-base, documentation, searchable

MCP (Model Context Protocol) server integration for Guru that lets MCP-based agents access and manage verified team knowledge and Guru cards.

---

## Overview

Guru MCP Server exposes Guru’s verified knowledge base to MCP-compatible clients (such as ChatGPT), enabling agents to retrieve, create, and manage Guru cards directly from within chat or other MCP-enabled applications.

---

## Features

### MCP Server Access
- **Static MCP endpoint:** `https://mcp.pipedream.net/v2` (single URL usable across supported clients).  
- **Authentication at client setup:** You authenticate when adding the server to your chosen MCP client.
- **Client setup guidance:** Instructions available for ChatGPT (OpenAI) and a dedicated configuration page for other MCP clients.

### Guru Knowledge Integration
- Connects to your Guru account to expose organizational documentation and verified team knowledge as MCP-accessible resources.
- Allows MCP-based agents to leverage Guru cards as a trusted knowledge source within workflows and conversations.

### Available Tools (Actions)
1. **Export Card to PDF**  
   - Export a specific Guru card, identified by its ID, to a PDF file.  
   - Useful for sharing, archiving, or offline access to individual cards.

2. **Create Card**  
   - Create a new card in your Guru account via MCP.  
   - Enables automated or agent-driven knowledge capture from within chat or other MCP clients.

3. **Add Tag to Card**  
   - Link an existing tag to a specified Guru card.  
   - Supports organizing and categorizing knowledge programmatically through MCP tools.

---

## Integration & Configuration
- **Sign-in based connection:** Users sign in through Pipedream to connect their Guru account and manage MCP access.
- **Works with multiple clients:** Designed for use with any MCP-compatible client, with specific guides for ChatGPT and a general configuration reference page.

---

## Pricing

No pricing information is provided in the available content for the Guru MCP Server. Use of this server may depend on the pricing and plans of Guru and/or Pipedream, which are not detailed in the provided material.