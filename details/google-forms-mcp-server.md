# Google Forms MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Google  
**Source:** https://mcp.pipedream.com/app/google_forms

## Overview
Google Forms MCP Server exposes Google Forms functionality through the Model Context Protocol (MCP), allowing MCP-aware applications and agents to create, modify, and analyze Google Forms and their responses via a standardized server endpoint.

## Features
- **MCP Server Endpoint**
  - Static MCP server URL: `https://mcp.pipedream.net/v2`
  - Same URL works for all clients; authentication occurs when adding the server to your application.

- **Google Account Integration**
  - Connect a Google account to access and manage Google Forms.
  - Works with multiple chat or MCP-aware clients (client-specific setup handled outside the server itself).

- **Form Management Actions (Tools)**
  The server exposes 6 actions as MCP tools:
  1. **Create Form**
     - Create a new Google Form programmatically.
  2. **Update Form Title**
     - Change the title of an existing Google Form.
  3. **Create Text Question**
     - Add a new text-based question to a Google Form.
  4. **Get Form**
     - Retrieve metadata and information about a specific Google Form.
  5. **List Form Responses**
     - List all responses submitted to a given form.
  6. **Get Form Response**
     - Retrieve a specific response from a form.

- **Use Cases**
  - Build and update surveys and forms from chat-based or MCP-aware agents.
  - Automate adding questions and changing titles without using the Google Forms UI.
  - Programmatically list and fetch responses for analysis or downstream processing.

## Pricing
The provided content does not specify any pricing or plan information for the Google Forms MCP Server.