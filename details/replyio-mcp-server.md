# Reply.io MCP Server

**Category:** Business & Commerce · MCP Servers  
**Slug:** `replyio-mcp-server`

## Overview
The Reply.io MCP Server exposes key Reply.io sales engagement capabilities as MCP tools, enabling AI agents and chat-based applications to automate contact and campaign operations across multichannel sales workflows.

## Features
- **Static MCP endpoint**  
  - Single server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Authentication performed when adding the server to an MCP-compatible application.

- **Account connection & configuration**  
  - Connect a Reply.io account to the MCP server.  
  - Select and manage the associated client/account after connection.  
  - Works with multiple chat clients that support MCP.  
  - Additional configuration details available via the linked configuration page (e.g., client-specific setup).

- **Available tools (actions)**  
  Five Reply.io actions are exposed as MCP tools:
  - **Remove Contact From Campaign**  
    - Remove an existing contact from a selected Reply.io campaign.
  - **Mark Contact as Replied**  
    - Mark a contact as “replied” in all campaigns where that contact appears, identified by email address.
  - **Mark Contact as Finished**  
    - Mark a contact as “finished” in all campaigns by their email address.
  - **Create or Update Contact**  
    - Create a new contact in Reply.io.  
    - If the contact already exists, update their data instead of creating a duplicate.
  - **Create or Update Contact and Push to Campaign**  
    - Create a new contact or update an existing one.  
    - Automatically add (push) that contact to a selected campaign after creation or update.

- **Sales engagement coverage (via Reply.io platform)**  
  While not all channels are directly exposed as separate tools here, the server is designed for workflows built on Reply.io’s multichannel sales engagement platform, which supports:  
  - Email outreach  
  - LinkedIn outreach  
  - Personal emails  
  - SMS and WhatsApp messages  
  - Calls  
  - Tasks

## Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server to an MCP-compatible chat or agent application.  
- Authenticate with Reply.io when prompted.  
- Use the exposed tools to manage contacts and campaign participation programmatically.

## Pricing
No pricing information is provided in the available content for the Reply.io MCP Server or its usage via Pipedream.