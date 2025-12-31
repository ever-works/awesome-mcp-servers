# Pushbullet MCP Server

## Overview
Pushbullet MCP Server is a Model Context Protocol (MCP) server that integrates Pushbullet with MCP-compatible clients. It allows applications (such as chat-based clients) to connect to Pushbullet in order to send cross-device notifications and data, effectively linking multiple devices through a single interface.

- **Name:** Pushbullet MCP Server  
- **Category:** Messaging MCP Servers  
- **Brand:** Pushbullet  
- **Slug:** `pushbullet-mcp-server`  
- **Primary Function:** Connect devices and enable cross-device notifications and data transfer via Pushbullet through an MCP server endpoint.

## Features
- **MCP Server Endpoint**  
  - Provides a static MCP server URL usable by any compatible MCP client:  
    - `https://mcp.pipedream.net/v2`
  - Centralized endpoint so the same URL can be reused across different clients.

- **Pushbullet Integration**  
  - Connects to Pushbullet to leverage its capabilities for:  
    - Cross-device notifications.  
    - Device-to-device data sharing / sync.

- **Client-Agnostic Usage**  
  - Designed to work with multiple MCP-capable chat or automation clients.  
  - Authentication happens when adding the server to the client application.

- **Configuration Support**  
  - Documented configuration flow via a dedicated configuration page (linked from the product page) to help set up the server in various clients.

## Setup Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when you add the MCP server to your application/client.

## Pricing
No pricing information is provided in the available content.