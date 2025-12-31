# People Data Labs MCP Server

## Overview
The People Data Labs MCP Server is an MCP-compatible connector that lets tools and chat clients access People Data Labs’ large-scale person and B2B data. It enables querying, searching, and enriching people and company records directly from MCP-enabled applications via Pipedream.

- **Category:** Business & Commerce – MCP Servers  
- **Provider:** Pipedream / People Data Labs  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Exposes People Data Labs functionality as an MCP server for use in compatible chat and agent clients (e.g., ChatGPT via OpenAI’s MCP support).
- Uses a single static server URL (`https://mcp.pipedream.net/v2`) for all clients; authentication is handled when adding the server to an application.
- Can be added and configured via Pipedream’s MCP configuration interface.

### Available Tools (Actions)
The server provides three main tools/actions backed by People Data Labs APIs:

1. **Search People**  
   - Find specific segments of people to support projects and products.  
   - Uses People Data Labs’ person search capabilities to query large-scale person data.

2. **Enrich a Person (Person Enrichment API)**  
   - One-to-one person enrichment based on an input identifier (e.g., known attributes).  
   - Returns up-to-date information on a unique individual from People Data Labs’ database.

3. **Enrich a Company (Company Enrichment API)**  
   - One-to-one company enrichment using company identifiers or attributes.  
   - Retrieves current information on a specific company.

### Configuration & Access
- Connects via a People Data Labs account managed through Pipedream. 
- Requires signing in to Pipedream to connect People Data Labs and manage accounts.
- Once connected, tools are callable from supported MCP clients according to the client’s integration guide.

## Pricing
Pricing information for the People Data Labs MCP Server is not provided in the available content. Use of this server may be subject to:
- People Data Labs’ own API/data pricing, and/or
- Pipedream’s platform pricing.

For exact pricing and plan details, consult People Data Labs and Pipedream directly.