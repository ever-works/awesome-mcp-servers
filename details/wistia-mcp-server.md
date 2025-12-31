# Wistia MCP Server

## Overview
The Wistia MCP Server is an MCP-compatible integration that exposes Wistia’s video hosting, audience engagement, and analytics capabilities to tools and agents that support the Model Context Protocol (MCP). It is powered by Pipedream Connect and is added to MCP clients via a single static server URL.

- **Name:** Wistia MCP Server  
- **Category:** Media Processing MCP Servers  
- **Provider / Brand:** Wistia (via Pipedream Connect)  
- **Slug:** `wistia-mcp-server`  
- **Primary URL:** https://mcp.pipedream.com/app/wistia

## Features
- **MCP-compatible server** – Implements a Model Context Protocol (MCP) server endpoint that can be consumed by MCP-capable tools and agents.
- **Static server URL** – Uses a single static URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic setup** – The same server URL works across different MCP-enabled chat clients and applications.
- **Authentication at configuration time** – Authentication is handled when you add/configure the server in your MCP client or application (rather than per-URL customization).
- **Video hosting integration** – Connects MCP tools to Wistia’s video hosting platform so agents can work with hosted video content (as described: “video hosting” features).
- **Audience engagement capabilities** – Exposes Wistia’s audience engagement–related features, enabling tools/agents to interact with or reason about engagement metrics and behavior.
- **Analytics access** – Provides access to Wistia’s analytics features so MCP tools can retrieve or use video performance and audience analytics data.
- **Configuration documentation** – A dedicated configuration page is available for detailed setup instructions for different chat clients (linked as “Configuration page”).

## How to Use
1. **Copy the MCP server URL**  
   Use the static endpoint: `https://mcp.pipedream.net/v2`.
2. **Add to your MCP client/app**  
   - Open your MCP-capable chat client or tool.
   - Add a new MCP server/integration using the URL above.
   - Complete the authentication flow when prompted.
3. **Refer to configuration docs**  
   - For client-specific steps, see the linked **Configuration page** from the Wistia MCP Server app page.

## Pricing
The provided content does not list any pricing information or plans for the Wistia MCP Server. Consult the main app page or provider (Pipedream / Wistia) for current pricing, if any.