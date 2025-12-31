# Followup MCP Server

## Overview
Followup MCP Server exposes FollowUp’s email reminder and follow-up capabilities as an MCP (Model Context Protocol) server, enabling chat clients and MCP-compatible tools to manage email-related productivity workflows via a standard interface.

- **Name:** Followup MCP Server  
- **Category:** Workflow Automation MCP Servers  
- **Tags:** email, reminders, productivity  
- **Source URL:** https://mcp.pipedream.com/app/followup  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-accessible actions** for FollowUp’s email tooling, designed to be called from MCP-compatible clients.  
- **Email reminder management** (via FollowUp’s underlying functionality) to help ensure important messages are revisited.  
- **Follow-up scheduling and tracking** for email conversations so tasks and replies do not slip through the cracks.  
- **Productivity workflow support** focused on email-based tasks and conversation management.  
- **Static MCP server URL** (`https://mcp.pipedream.net/v2`) that works across supported clients, with authentication handled when adding the server.  
- **Client-agnostic integration**: can be added to various chat clients that support MCP, using the same base URL.  
- **Centralized configuration** via the Pipedream MCP configuration flow (referenced “Configuration page”).

> Note: The site content references FollowUp’s general capabilities (email reminders, follow-ups, productivity workflows) and this MCP server as an interface to those capabilities, but does not list more granular, specific actions.

## Integration & Setup
- Use the static MCP server URL in your MCP-compatible application:  
  - **Server URL:** `https://mcp.pipedream.net/v2`  
- Authentication occurs when you add the server to your chosen client.  
- Additional configuration details are available on Pipedream’s MCP configuration page (not reproduced here).

## Pricing
- The provided content does not specify any pricing or plans for the Followup MCP Server or FollowUp itself.