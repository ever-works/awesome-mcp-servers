# Google Meet MCP Server

**Brand:** Pipedream  
**Category:** Messaging MCP Servers  
**Tags:** google-meet, meetings, video-conferencing  
**Source:** https://mcp.pipedream.com/app/google_meet

## Overview
The Google Meet MCP Server is a Model Context Protocol (MCP) server hosted on Pipedream that connects applications and chat clients to Google Meet. It is designed to enable real-time, meeting-related actions—such as scheduling and handling meeting events—directly from compatible MCP-enabled clients.

## Features
- **Static MCP Endpoint**  
  - Single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Works across different MCP-compatible chat or AI clients.

- **Google Meet Integration**  
  - Integrates with Google Meet for real-time meeting operations.  
  - Supports typical Google Meet use cases such as video meetings, screen sharing, and presentations (via the underlying Google Meet platform).

- **Real-Time Meeting Interactions**  
  - Designed for real-time meeting-related actions (e.g., creating or managing meetings, handling events) from within an MCP client.

- **Authentication Per Client**  
  - Authentication is performed when you add the server to your MCP-enabled application or chat client.

- **Client-Agnostic Setup**  
  - Usable from multiple chat clients; each client can follow its own setup instructions.  
  - Configuration is centralized through a shared configuration pattern (via a configuration page referenced by the service).

- **Built on Pipedream Connect**  
  - Runs on Pipedream’s integration platform, benefiting from its infrastructure and connectivity layer.

## Setup / Configuration
- Use the MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add this URL as an MCP server in your compatible chat or AI client.  
- Authenticate with your Google account when prompted by the client during server setup.  
- For full setup details, refer to the linked configuration documentation in the source application page.

## Pricing
The provided content does not list any pricing or plan information for the Google Meet MCP Server. Refer to the source page or Pipedream’s pricing documentation for current details.