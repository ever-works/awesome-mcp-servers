# Cloze MCP Server

**Category:** Business & Commerce · MCP Servers  
**Website:** https://mcp.pipedream.com/app/cloze

## Overview
Cloze MCP Server connects Cloze’s relationship management and communication tracking platform to MCP‑enabled agents. It lets your applications interact with Cloze data (projects, companies, notes) through a standard MCP server endpoint hosted by Pipedream.

Cloze automatically keeps track of:
- Email
- Phone calls
- Text messages
- Meetings
- Documents
- Evernote
- LinkedIn
- Facebook
- Twitter

## MCP Server Details
- **Server URL:** `https://mcp.pipedream.net/v2`  
  - Static URL used for all clients
  - Authentication is handled when adding the server to your MCP‑compatible application
- **Integration Flow:**
  - Connect your Cloze account
  - Configure Cloze in Pipedream
  - Add the MCP server URL to your chat client / MCP‑enabled app

## Features

### General Capabilities
- Connects Cloze CRM / relationship management data to MCP‑enabled agents
- Supports business and account management workflows via MCP tools
- Uses a single static MCP server URL for all clients
- Authentication occurs at the time you add/configure the server in your application

### Available Tools (Actions)
1. **Create or Update Project**  
   - Create a new project in Cloze  
   - Or merge updates into an existing project  
   - Action is backed by the `create-update-project` component in Pipedream

2. **Create or Update Company**  
   - Create a new company in Cloze  
   - Enhance or update an existing company  
   - Companies can be created with:
     - Just a domain name, or
     - A name plus another unique identifier (e.g., phone number, email address)  
   - Action is backed by the `create-update-company` component in Pipedream

3. **Create Note**  
   - Create notes within Cloze  
   - Useful for logging interactions, comments, or context tied to Cloze records  
   - Action is backed by the `create-note` component in Pipedream

## Integration / Usage
- Add the MCP server URL to supported chat clients or MCP‑enabled applications
- Use the available tools (actions) from within your agent or client to manage Cloze data:
  - Create/update projects
  - Create/update companies
  - Create notes
- Further configuration details are available on Pipedream’s configuration page (not specific to pricing or support).

## Pricing
The provided content does not specify any pricing or plans for the Cloze MCP Server on Pipedream.