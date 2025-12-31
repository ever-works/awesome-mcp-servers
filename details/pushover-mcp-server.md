# Pushover MCP Server

## Overview
The Pushover MCP Server is an integration that exposes Pushover’s push notification capabilities as MCP tools, allowing MCP‑compatible clients (such as ChatGPT) and automations to send standard and emergency push notifications to Pushover devices.

- **Category:** Messaging MCP Servers  
- **Brand:** Pushover  
- **Source URL:** https://mcp.pipedream.com/app/pushover  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server endpoint**  
  - Single static MCP server URL (`https://mcp.pipedream.net/v2`) used across supported clients.  
  - Authentication handled when adding the server inside the client/application.

- **Account and client configuration**  
  - Connect a Pushover account via the Pipedream MCP interface.  
  - Select and configure your preferred MCP client (e.g., ChatGPT/OpenAI) to use the Pushover server.  
  - Access a detailed configuration page for additional setup information.

- **Available tools (actions)**  
  1. **Push Notification**  
     - Sends a standard push notification to Pushover‑registered devices.  
     - Uses Pushover’s standard message sending API ("Pushing Messages").

  2. **Emergency Push Notification**  
     - Sends an emergency‑priority push notification to Pushover devices.  
     - Notifications are repeatedly sent until the user acknowledges them.  
     - Uses Pushover’s emergency message priority features ("Pushing Messages and Message Priority").

- **Integration scope**  
  - Suitable for web apps, automations, monitoring systems, scripts, and other MCP‑enabled tools that need to trigger Pushover notifications.

## Pricing
Pricing details for this MCP server are not provided in the available content.