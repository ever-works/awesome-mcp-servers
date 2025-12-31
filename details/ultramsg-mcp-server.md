# UltraMsg MCP Server

## Overview
UltraMsg MCP Server is an MCP-compatible integration for UltraMsg’s WhatsApp API, providing a messaging gateway to automate WhatsApp communications from MCP-enabled chat clients and applications.

- **Category:** Messaging MCP Servers  
- **Provider / Brand:** UltraMsg (via Pipedream)  
- **Source URL:** https://mcp.pipedream.com/app/ultramsg  
- **Slug:** `ultramsg-mcp-server`  
- **Tags:** whatsapp, messaging, api-integration

## Features

### MCP Server & Configuration
- MCP-compatible server exposing UltraMsg’s WhatsApp API as tools.
- Single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- Server is added to any supported MCP client; authentication occurs when adding the server to the application.
- Account connection flow to link an UltraMsg account via Pipedream.

### Available Tools / Actions
The MCP server exposes 7 actions as tools for automated WhatsApp messaging:

1. **Send a Message**  
   - Send a text message to a specified WhatsApp number.

2. **Send a Document**  
   - Send a document file to a specified WhatsApp number.

3. **Send a Video**  
   - Send a video file to a specified WhatsApp number.

4. **Send an Image**  
   - Send an image file to a specified WhatsApp number.

5. **Send Audio**  
   - Send an audio file to a specified WhatsApp number.

6. **Send a Location**  
   - Send a geographic location to a specified WhatsApp number.

7. **Send a Link**  
   - Send a URL/link to a specified WhatsApp number.

Each tool is implemented as a Pipedream action (with corresponding source files in the Pipedream GitHub repository) and can be invoked from MCP-aware clients.

## Integration Details
- Designed for use within MCP-enabled chat clients and applications.
- Uses UltraMsg as the underlying WhatsApp API provider and gateway.
- Configuration guidance and additional setup instructions are available on the Pipedream Configuration page.

## Pricing
- No pricing information is provided in the supplied content. Pricing for UltraMsg or Pipedream usage would need to be obtained from their respective official sites.