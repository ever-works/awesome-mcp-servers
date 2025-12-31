# MongoDB MCP Server

## Overview
MongoDB MCP Server is a Model Context Protocol (MCP) server that provides programmatic access to MongoDB NoSQL databases via a static MCP endpoint. It exposes common MongoDB operations as tools that can be invoked from compatible MCP clients and chat applications.

- **Type:** MCP server / database integration
- **Database:** MongoDB (open source NoSQL database)
- **MCP endpoint:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server & Connectivity
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across different MCP clients.
- Authentication handled when adding the server to an MCP-compatible application.
- Works with multiple chat or MCP clients (client-specific setup is done in each app using the same URL).

### MongoDB Data Operations (Tools)
The server exposes 8 MongoDB actions as MCP tools:

1. **Create New Document**
   - Create a new document in a chosen MongoDB collection.

2. **Find Document**
   - Find a document using a query filter.

3. **Find Document by ID**
   - Retrieve a single document by its MongoDB document ID.

4. **Search Documents**
   - Search for specific documents based on criteria.
   - Can also return all documents when desired.

5. **Update a Document**
   - Update a single document by its ID.

6. **Update Documents**
   - Update many documents at once using a query filter.

7. **Execute Aggregation**
   - Run an aggregation pipeline on a MongoDB collection.

8. **Delete a Document**
   - Delete a single document by its ID.

## Configuration
- Connect a MongoDB account and configure it through the Pipedream interface.
- Add the MCP server URL to the chosen client, then authenticate within that client.
- Additional setup details are available on the provider’s configuration page (referenced as “Configuration page” in the source content).

## Pricing
The provided content does not specify any pricing or plans for MongoDB MCP Server.