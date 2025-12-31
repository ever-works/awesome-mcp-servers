# Neo4j AuraDB MCP Server

**Brand:** neo4j  
**Category:** Database & Messaging MCP Servers  
**Tags:** graph-database, neo4j, cloud

## Overview
Neo4j AuraDB MCP Server is an MCP-compatible service that connects AI agents and MCP clients to a fully managed Neo4j AuraDB graph database. It exposes Neo4j AuraDB capabilities through a standard MCP server endpoint so tools and chat-based clients can query and manage graph data in a cloud environment.

## Features
- **MCP-compatible graph database server**  
  - Implements an MCP server interface for use with MCP-capable clients and AI agents.
- **Connection to Neo4j AuraDB**  
  - Integrates with Neo4j’s fully managed AuraDB graph database service.  
  - Designed for querying and managing graph data in the cloud.
- **Static MCP server URL**  
  - Single endpoint for all supported clients:  
    - `https://mcp.pipedream.net/v2`  
  - URL is client-agnostic; authentication is handled when adding the server to each application.
- **Client-agnostic configuration**  
  - Works with multiple MCP-compatible chat or agent clients.  
  - Per-client setup instructions available via the configuration flow.
- **Centralized configuration page**  
  - Dedicated configuration page (on Pipedream) for setup and management of the MCP server connection.
- **Pipedream-hosted infrastructure**  
  - Hosted and operated by Pipedream, leveraging their cloud infrastructure and policies.

## Usage Notes
- You connect your Neo4j AuraDB account through Pipedream, then add the MCP server URL to your chosen MCP client.  
- Authentication occurs at the time you add or configure the server in your application.

## Pricing
- No pricing information is provided in the available content.