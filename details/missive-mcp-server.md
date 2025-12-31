# Missive MCP Server

Shared inbox and team chat MCP server that exposes Missive’s communication and collaboration features to MCP-compatible clients and agents.

- **Category:** Messaging MCP Servers  
- **Brand:** Missive  
- **Source URL:** https://mcp.pipedream.com/app/missive  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview

The Missive MCP Server connects MCP-compatible clients (such as ChatGPT) to Missive, enabling agents and applications to work with shared inbox, email, contacts, and team chat data through a unified MCP endpoint.

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable by any MCP-compatible client.
- Authentication flow handled when adding the server to your application.
- Configuration guidance available for ChatGPT (OpenAI) and other clients via the general configuration page.

### Missive Capabilities Exposed via Tools
The server currently exposes 5 Missive actions as tools:

1. **List Contacts**  
   - Retrieve a list of contacts from Missive.  
   - Useful for browsing or selecting recipients, collaborators, or customers.

2. **Get Contact**  
   - Fetch detailed information for a specific contact.  
   - Enables agents/clients to look up contact details before drafting communication.

3. **Create Contact**  
   - Create a new contact in Missive.  
   - Supports programmatic onboarding of new leads, customers, or teammates.

4. **Create Draft**  
   - Create a new email draft in Missive.  
   - Useful for agent-assisted email composition, saving drafts for later review and sending.

5. **Create Post**  
   - Create a new post in Missive (e.g., for team chat or internal discussions).  
   - Enables agents/clients to initiate or log internal conversations tied to shared inbox activity.

### Usage Context
- Designed for teams using Missive for shared inboxes, email, and team chat.
- Allows MCP-compatible agents and chat clients to:
  - Read and manage contacts.
  - Draft emails.
  - Post messages into team communication threads.

## Setup

1. **Connect Missive**  
   - Sign in to Pipedream / MCP to connect your Missive account and manage linked accounts.

2. **Add MCP Server to Your Client**  
   - Use server URL: `https://mcp.pipedream.net/v2`.  
   - Configure in your MCP-compatible client (e.g., ChatGPT) following its specific guide.

3. **Configure Tools**  
   - Enable the Missive tools (List Contacts, Get Contact, Create Contact, Create Draft, Create Post) in your client or agent configuration as needed.

## Pricing

The provided content does not list any specific pricing or plans for the Missive MCP Server on Pipedream / MCP.