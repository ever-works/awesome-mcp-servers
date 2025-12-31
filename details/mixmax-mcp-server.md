# MixMax MCP Server

## Overview
MixMax MCP Server connects the Mixmax sales engagement platform for Gmail to MCP-compatible agents, enabling automated outreach, tracking, and workflow actions through a standardized MCP server endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Integrates with:** Mixmax (Gmail-based sales engagement), MCP-compatible chat/agent clients  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable by any supported client.  
- Authentication handled when the server is added to your MCP-compatible application.  
- Can be added to different chat or agent clients that support MCP, using their respective configuration flows.  
- Central configuration reference via Pipedream’s configuration documentation.

### Contact Management Tools (Actions)
The server exposes 6 Mixmax-related actions as tools for agents and clients:

1. **Update Contact**
   - Update a specific contact in Mixmax.
   - Uses Mixmax’s contact API to modify existing contact records.

2. **Search Contacts**
   - Search for matching contacts across multiple data sources:
     - Mixmax
     - Google Directory
     - Salesforce (contacts, leads, accounts, and opportunities)
   - Useful for unified lookup of people and organizations from within an MCP client.

3. **Get Contacts**
   - List all Mixmax contacts (people you’ve emailed using Mixmax).
   - Note: Does not currently return contacts that are only shared with you via shared contact groups (performance limitation).

4. **Get Contact Groups**
   - Retrieve contact groups you have access to, including:
     - Groups you created
     - Groups that have been shared with you

5. **Create Contact**
   - Create a new contact record in Mixmax.
   - Can be invoked programmatically from MCP-compatible agents to add leads/contacts.

6. **Create Contact Group**
   - Create new contact groups in Mixmax.
   - Supports organizing contacts into segments or lists via MCP workflows.

## Pricing
No pricing information is provided in the available content for the MixMax MCP Server. Pricing, if applicable, would need to be obtained from Pipedream or Mixmax directly.