# Anchor Browser MCP Server

**Category:** Web Search MCP Servers  
**Brand:** Anchor Browser  
**Slug:** anchor-browser-mcp-server  
**Source:** https://mcp.pipedream.com/app/anchor_browser

## Overview
The Anchor Browser MCP Server is a Model Context Protocol (MCP) server that provides programmatic access to Anchor Browser, a browser optimized for AI agents to navigate and interact with the web. It is delivered via Pipedream and can be added to compatible chat or AI clients using a static MCP server URL.

## Features

- **MCP Server Endpoint**
  - Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`
  - Authentication handled when adding the server to your application.

- **Integration & Configuration**
  - Connect an Anchor Browser account via Pipedream.
  - Select and configure a specific client (chat or AI application) to use the server.
  - Documentation and configuration details available via the Pipedream configuration page.

- **Browser Session Management**
  - **Start Browser**
    - Allocates a new browser session for the user.
    - Supports optional configurations, including:
      - Ad-blocking
      - Captcha solving
      - Proxy usage
      - Idle timeout

- **Profile Management**
  - **Create Profile**
    - Creates a new profile from an existing browser session.
    - Profiles store:
      - Cookies
      - Local storage
      - Cache
  - **Update Profile**
    - Updates the description or data of an existing profile using a session.
  - **Delete Profile**
    - Deletes an existing profile by its name.

- **Available Tools (Actions)**
  - Update Profile
  - Start Browser
  - Delete Profile
  - Create Profile

## Pricing
No pricing information is provided in the available content.
