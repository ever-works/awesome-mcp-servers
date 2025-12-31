# Agiliron MCP Server

MCP Server for Agiliron, connecting MCP clients to its inventory management and multi-channel retail POS capabilities.

- **Category:** Business & Commerce → MCP Servers  
- **Brand:** Agiliron  
- **Source:** https://mcp.pipedream.com/app/agiliron  
- **Slug:** `agiliron-mcp-server`  
- **Tags:** inventory, pos, e-commerce

## Overview
The Agiliron MCP Server is a Model Context Protocol (MCP) endpoint provided via Pipedream that allows chat-based clients (such as ChatGPT) and other MCP-compatible applications to interact with Agiliron. It focuses on CRM- and sales-related operations within the broader Agiliron inventory management and multi-channel retail POS platform.

## Features

### MCP Server & Connectivity
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- Authentication handled when adding the MCP server to your application.  
- Usable from MCP-compatible chat clients (e.g., ChatGPT via the Pipedream configuration guide).  
- Managed and hosted by Pipedream Connect.

### Core Agiliron Actions (Tools)
The MCP server exposes Agiliron operations as tools/actions:

1. **Create Lead**  
   - Establishes a new lead within Agiliron.  
   - Intended for capturing prospective customer information in the Agiliron system.  
   - Action implementation documented at:  
     `https://github.com/PipedreamHQ/pipedream/blob/master/components/agiliron/actions/create-lead/create-lead.mjs`

2. **Create Event**  
   - Creates a new event within Agiliron.  
   - Suitable for logging activities or calendar-style records associated with leads or contacts.  
   - Action implementation documented at:  
     `https://github.com/PipedreamHQ/pipedream/blob/master/components/agiliron/actions/create-event/create-event.mjs`

3. **Create Contact**  
   - Generates a new contact record in Agiliron.  
   - Used to add people or organizations to the Agiliron CRM database.  
   - Action implementation documented at:  
     `https://github.com/PipedreamHQ/pipedream/blob/master/components/agiliron/actions/create-contact/create-contact.mjs`

### Platform Context
- Integrates with the broader **Agiliron** platform, which provides:  
  - Inventory management capabilities.  
  - Multi-channel retail POS (point-of-sale) software.  
  - Business management tooling.  
- MCP server acts as a bridge between MCP clients and Agiliron’s business data (leads, contacts, events, etc.).

### Configuration & Setup
- Users connect their Agiliron account from the Pipedream MCP interface.  
- After sign-in, users select a client and configure the MCP server connection.  
- Additional configuration details are available on Pipedream’s MCP **Configuration** page.

## Pricing
No pricing information for the Agiliron MCP Server is provided in the available content. Pricing may depend on Pipedream and/or Agiliron plans and should be checked on their respective websites.