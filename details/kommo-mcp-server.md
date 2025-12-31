# Kommo MCP Server

Messenger-based sales CRM integration for the MCP framework.

## Overview
Kommo MCP Server connects the Kommo messenger-based sales CRM with MCP-compatible clients, exposing CRM functionality (such as conversations, contacts, and pipelines) via a standardized server endpoint.

**MCP Server URL:**
```text
https://mcp.pipedream.net/v2
```
This is a static URL used by all clients; authentication occurs when you add the server to your application.

## Features
- **MCP-compatible server endpoint**  
  - Single static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - Designed to be added to MCP-capable chat or agent clients.

- **Kommo CRM integration**  
  - Programmatic access (via MCP) to Kommo’s:  
    - Messenger-based conversations.  
    - Contacts and customer records.  
    - Sales pipelines and related CRM data.

- **Client-agnostic setup**  
  - Works with multiple MCP-enabled chat clients.  
  - Authentication is handled during server addition in the client, not via a custom URL.

- **Configuration resources**  
  - Additional configuration details available via a dedicated configuration page (linked from the app page).

## Pricing
No pricing information is provided in the available content.