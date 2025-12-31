# Sendfox MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** SendFox  
**Source:** https://mcp.pipedream.com/app/sendfox_personal_access_token

## Overview
SendFox MCP Server is an email marketing integration that connects SendFox to MCP-compatible chat or agent clients using a personal access token. It exposes SendFox’s email marketing capabilities as tools that can be called from your application.

## Authentication
- Uses SendFox personal access tokens for authentication.
- Authentication is performed when adding the MCP server to your client/application.
- Works through a static MCP server URL: `https://mcp.pipedream.net/v2`.

## Features
- **MCP Server Endpoint**  
  - Static, reusable MCP URL for all supported clients.  
  - Centralized configuration via the provided endpoint.

- **Personal Access Token Integration**  
  - Uses SendFox personal access tokens rather than OAuth in this configuration.  
  - Tokens link your SendFox account to the MCP server.

- **Chat / Client Integration**  
  - Designed to be added as an MCP server in compatible chat or AI clients.  
  - Instructions available per client type via the configuration interface.  
  - Supports multiple clients using the same endpoint.

- **Email Marketing Tool Access**  
  - Provides access to SendFox email marketing functionality through MCP tools (tools list is dynamically loaded in the UI).  
  - Tools are exposed as actions that can be invoked by your client once the server is configured.

- **Configuration Page**  
  - Central configuration page for managing how the MCP server is added to different clients.  
  - Guides you through copying the server URL and linking your account.

## Pricing
- Not specified in the provided content. Use the source link or vendor site for current pricing details.