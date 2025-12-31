# Fibery MCP Server

## Overview
Fibery MCP Server is an MCP-compatible integration provided by Pipedream that connects MCP tools and workflows to a Fibery workspace. It allows applications and chat-based MCP clients to interact programmatically with Fibery’s knowledge base, documents, and work management entities via a static MCP server URL.

- **Category:** Project Management MCP Servers  
- **Provider / Brand:** Pipedream  
- **Integration Target:** Fibery (connected workspace for teams)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server endpoint**  
  - Single static MCP server URL usable across supported MCP clients.  
  - Authentication handled when the server is added to an application or client.

- **Fibery account connection**  
  - Connect a Fibery account through Pipedream to authorize MCP-based access.  
  - Manage connected Fibery accounts within Pipedream.

- **Entity type and schema inspection**  
  - **List Types**: Retrieve a list of types defined in a Fibery account.  
  - **List Fields for Entity Type**: Retrieve all fields for a given Fibery entity type.

- **Entity querying and retrieval**  
  - **List Entities**: List entities for a specified type in Fibery, enabling clients to browse or query workspace data.

- **Entity creation and upsert operations**  
  - **Create Entity**: Create a single new entity of a specified type.  
  - **Create Multiple Entities**: Batch creation of multiple entities in one operation.  
  - **Get or Create Entity**: Retrieve an existing entity or create it if it does not exist.  
  - **Create or Update Entity**: Create a new entity or update an existing one, depending on whether it is found (upsert behavior).

- **Client-agnostic configuration**  
  - Documentation and configuration guidance for adding the MCP server to different chat or MCP clients.  
  - Central configuration reference available via a dedicated configuration page.

## Pricing
The provided content does not include any pricing information for the Fibery MCP Server integration on Pipedream.