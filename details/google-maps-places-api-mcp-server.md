## Google Maps Places API MCP Server

**Category:** Search & Discovery MCP Servers  
**Brand:** Google Maps Platform  
**Slug:** `google-maps-places-api-mcp-server`

### Overview
The Google Maps (Places API) MCP Server, provided via Pipedream, exposes Google Maps Places functionality as MCP tools so AI models and MCP-compatible clients can search and retrieve up-to-date business and place information (e.g., grocery stores, restaurants, pharmacies, and other points of interest).

MCP server URL (static for all clients):
```text
https://mcp.pipedream.net/v2
```

### Features
- **MCP Server for Google Maps Places API**  
  - Wraps Google Maps Places API for use as MCP tools.  
  - Works with multiple MCP-compatible chat clients (e.g., ChatGPT via OpenAI).

- **Authentication & Connection**  
  - Connects to a Google Maps (Places API) account through Pipedream.  
  - Authentication occurs when adding the server to your MCP-compatible application.  
  - Central account management via Pipedream.

- **Available Tools (Actions)**  
  1. **Search Places**  
     - Searches for places based on:  
       - Location (coordinate-based or area-based input).  
       - Search radius.  
       - Optional filters such as:  
         - Keywords,  
         - Place type,  
         - Place name.  
     - Returns lists of nearby or matching places using current Google Maps Places data.

  2. **Get Place Details**  
     - Retrieves detailed information for a specific place using its **Place ID**.  
     - Intended for obtaining richer metadata about a selected place after search (e.g., after using Search Places).

- **Client Integration Guidance**  
  - Static MCP server URL usable by any compatible client.  
  - Documentation and guides available for adding the server to specific chat clients (e.g., ChatGPT) via the Pipedream configuration pages.

### Pricing
The provided content does not list any pricing details or plans for the Google Maps (Places API) MCP Server. Pricing information would need to be obtained from the Pipedream or Google Maps Platform documentation/pages directly.