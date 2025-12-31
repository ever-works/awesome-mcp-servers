# Shutterstock MCP Server

Shutterstock MCP Server is an MCP integration for Shutterstock’s stock media library, allowing MCP clients to search and retrieve images, vectors, videos, and music.

## Overview
- **Category:** Media Processing MCP Servers
- **Provider / Brand:** Shutterstock (via Pipedream)
- **Slug:** `shutterstock-mcp-server`
- **Integration Type:** Model Context Protocol (MCP) server
- **Primary Use Case:** Access Shutterstock stock media assets from MCP-compatible clients.

## Features
- **Shutterstock stock media integration**  
  - Connects MCP clients to Shutterstock’s stock media library.  
  - Supports searching and retrieving:  
    - Images  
    - Vectors  
    - Videos  
    - Music

- **Static MCP server URL**  
  - Uses a single, static endpoint that works for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication occurs when adding the server to your application.

- **Client-agnostic setup**  
  - Designed to be added to various MCP-compatible chat or developer clients.  
  - Documentation available per client type via the configuration flow.

- **Configuration via Pipedream**  
  - Connects through your Shutterstock/Pipedream configuration.  
  - Centralized configuration page for setup instructions.

## Setup
1. Configure Shutterstock via Pipedream.  
2. Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add the server URL to your MCP-compatible app or chat client.  
4. Authenticate when prompted in your application.

## Pricing
- No specific pricing information is provided in the available content. Use of Shutterstock assets may still be subject to Shutterstock’s own licensing and pricing terms.
