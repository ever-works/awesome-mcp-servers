## Freshdesk MCP Server

**Category:** Business & Commerce · MCP Servers  
**Tags:** customer-support, tickets, helpdesk  
**Source:** https://mcp.pipedream.com/app/freshdesk

### Overview
Freshdesk MCP Server is an MCP server that connects Freshdesk’s cloud customer support platform to MCP-compatible clients. It enables AI agents and chat-based applications to work with Freshdesk tickets, contacts, agents, solution articles, and related helpdesk data and workflows.

### Connection & Configuration
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`
- Connect a Freshdesk account, then add the MCP server to your MCP-compatible app or chat client.
- Configuration is performed per client after connecting your Freshdesk account.

### Features
- **MCP Integration Layer**
  - Exposes Freshdesk operations as MCP tools/actions.
  - Designed for use by AI agents and chat clients to manage helpdesk workflows.

- **Tooling / Actions (39 tools available; examples include):**
  - **Ticket Management**
    - **Update a Ticket**: Modify ticket attributes such as status, priority, subject, description, assigned agent, and group.
    - **Set Ticket Tags**: Replace all existing tags on a ticket with a new set of tags.
    - **Remove Ticket Tags**: Remove specific tags from a ticket without replacing all tags.
    - **Set Ticket Status**: Change the status of a ticket (e.g., open, pending, resolved, etc., according to Freshdesk configuration).
    - **Set Ticket Priority**: Change the priority level of a ticket.
    - **List Ticket Fields**: Retrieve all ticket field definitions configured in Freshdesk.
    - **List Conversations of a Ticket**: Fetch all conversations associated with a given ticket.

  - **Knowledge Base & Solutions**
    - **Update Solution Article**: Edit an existing solution article’s content or metadata.
    - **List Solution Categories**: Retrieve the list of solution categories in Freshdesk.
    - **List Category Folders**: List all folders under a specific solution category.
    - **List Folder Articles**: List all articles within a specific folder.
    - **List All Canned Responses In A Folder**: Retrieve all canned responses stored in a specific folder.

  - **Contact & Agent Management**
    - **Update Contact**: Update details of an existing Freshdesk contact.
    - **Update Agent**: Update details of an existing Freshdesk agent.

### Usage
- Add the MCP server URL to any supported MCP client or chat interface.
- Authenticate with a Freshdesk account when prompted.
- Use the exposed tools to build AI-assisted workflows around ticket handling, customer communication, and knowledge base management.

### Pricing
The provided content does not list any pricing or plan information for the Freshdesk MCP Server.