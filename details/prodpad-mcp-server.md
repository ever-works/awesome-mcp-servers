# ProdPad MCP Server

## Overview
ProdPad MCP Server is an MCP-compatible integration that exposes ProdPad’s product management capabilities—roadmapping, backlog management, team communication, and customer feedback—so they can be used directly from MCP-enabled tools and agents.

**MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP / Integration Capabilities
- Static MCP server URL usable across clients, with authentication handled when adding the server to an application.
- Usable from multiple chat clients and MCP-compatible applications (configured per client).
- Central configuration via a dedicated configuration page (external documentation).

### Product Management Functions Exposed as Tools
15 actions are available as tools through the MCP server:

#### Idea Management
- **Create Idea**
  - Create new product ideas in ProdPad.
- **Find Idea**
  - Search for and retrieve an existing idea.
- **Update Idea Stage**
  - Change the stage of an existing idea (e.g., for roadmap / workflow progression).

#### Feedback Management
- **Create Feedback**
  - Create new customer or user feedback entries.
- **Find Feedback**
  - Locate and retrieve existing feedback records.
- **Find or Create Feedback**
  - Search for existing feedback and, if none is found, create a new feedback entry.
- **Update Feedback**
  - Modify existing feedback records.

#### Contact Management
- **Create Contact**
  - Add new contacts into ProdPad.
- **Find Contact**
  - Search for and retrieve existing contacts.
- **Find or Create Contact**
  - Look up a contact and create one if it does not exist.
- **Update Contact**
  - Update details for existing contacts.

#### Company Management
- **Create Company**
  - Create a new company record in the ProdPad account.
  - Only available to ProdPad accounts with an **Advanced or higher** subscription; accounts below that level will receive a 403 response.
- **Find Company**
  - Find and retrieve an existing company.
- **Find or Create Company**
  - Search for an existing company and create a new one if not found.
- **Update Company**
  - Update an existing company’s details.

### Use Cases
- Manage roadmaps and idea stages directly from MCP-enabled chat or agent tools.
- Capture and update customer feedback from conversational interfaces.
- Maintain synchronized records of contacts and companies between ProdPad and other systems.

## Pricing
No pricing information is provided for the ProdPad MCP Server in the available content.

## Technical Details
- **Server Type:** MCP Server (hosted by Pipedream)
- **Endpoint:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when the server is added to the client/application.
- **Requirements for Some Actions:** "Create Company" requires a ProdPad Advanced or higher subscription (otherwise returns HTTP 403).