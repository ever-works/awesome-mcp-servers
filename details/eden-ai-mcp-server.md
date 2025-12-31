# Eden AI MCP Server

An MCP server that exposes Eden AI’s unified multi‑provider AI APIs (vision, NLP, speech, and more) to MCP-compatible clients, allowing access to many AI engines through a single Model Context Protocol endpoint.

## Basic Info
- **Name:** Eden AI MCP Server  
- **Category:** AI Integration – MCP Servers  
- **Provider / Brand:** Eden AI (via Pipedream Connect)  
- **Slug:** `eden-ai-mcp-server`  
- **Source URL:** https://mcp.pipedream.com/app/eden_ai

## MCP Endpoint
- **Universal MCP Server URL:** `https://mcp.pipedream.net/v2`  
  - Static URL used across supported MCP clients.  
  - Authentication is performed when adding the server to your application/client.

## Features
- **Unified AI Access via MCP**  
  - Exposes Eden AI’s multi‑provider AI APIs through the Model Context Protocol.  
  - Provides a single integration point for multiple AI engines.

- **Multi‑Provider AI Platform**  
  - Access to a variety of AI engines (e.g., vision, NLP, speech, and other modalities) behind a single MCP server.  
  - Designed to simplify switching or combining providers without changing client‑side MCP integration.

- **Static, Reusable Server URL**  
  - Uses one static MCP endpoint (`https://mcp.pipedream.net/v2`) that can be reused across different MCP clients and applications.  
  - Server configuration is handled once per client; credentials are applied during setup.

- **Client‑Agnostic Integration**  
  - Intended to work with any compatible MCP chat or tooling client.  
  - Documentation is organized by client type (e.g., “Select your chat client to learn how to get started”).

- **Configuration Documentation**  
  - Full configuration details available via a dedicated **Configuration** page on Pipedream (how to add the MCP server, authenticate, and manage settings).

## Pricing
- No pricing details are provided in the available content.

## Additional Notes
- The MCP server is powered and hosted by **Pipedream Connect**.  
- Legal and policy references (Terms, Privacy Policy, Cookies) are handled through Pipedream’s platform, not the MCP API itself.