# UK Gov Vehicle Enquiry API MCP Server

## Overview
The **UK Gov Vehicle Enquiry API MCP Server** exposes the UK DVLA Vehicle Enquiry REST API through the Model Context Protocol (MCP). It allows MCP-enabled tools and applications to retrieve detailed information about UK vehicles using their registration number.

- **Name:** UK Gov Vehicle Enquiry API MCP Server  
- **Provider / Brand:** DVLA (via Pipedream Connect)  
- **Category:** Data access & integration – MCP servers  
- **Primary use case:** Look up vehicle details from the UK DVLA by registration number within MCP-compatible clients.

## Features
- **DVLA Vehicle Enquiry Integration**  
  - Connects to the official UK DVLA Vehicle Enquiry RESTful API.  
  - Uses the vehicle registration number as the main input to query vehicle data.

- **RESTful Vehicle Data Access**  
  - Retrieves vehicle details associated with a given UK registration plate.  
  - Designed for programmatic access via MCP-compatible chat clients and tools.

- **MCP Server Endpoint**  
  - Static MCP server base URL: `https://mcp.pipedream.net/v2`.  
  - Same URL works across all supported MCP clients.  
  - Authentication is handled when adding the server to the client/application.

- **Client-agnostic Usage**  
  - Can be added to multiple MCP-enabled chat clients.  
  - Configuration is documented via a central configuration page (on the provider site).

## Integration & Configuration
- **Server URL**: `https://mcp.pipedream.net/v2` (static across clients).  
- **Setup flow**:  
  - Add the MCP server URL to your MCP-compatible app or chat client.  
  - Authenticate as instructed by the client or provider.  
  - Use tools exposed by this MCP server to query vehicle details by registration number.

## Pricing
The provided content does **not** contain any pricing information or plan details for the UK Gov Vehicle Enquiry API MCP Server.