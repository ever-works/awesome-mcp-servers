# Data.Police.UK MCP Server

Open data about crime and policing in England, Wales, and Northern Ireland, exposed via the Model Context Protocol (MCP).

---

## Overview
**Data.Police.UK MCP Server** is an MCP-compatible service that connects applications (such as AI/chat clients) to the official UK Police open data API. It enables programmatic queries for crime and policing information across England, Wales, and Northern Ireland through a standardized MCP endpoint.

- **Category:** Data Access & Integration – MCP Servers  
- **Provider / Brand:** datapoliceuk (via Pipedream)  
- **Primary Region Covered:** England, Wales, Northern Ireland  
- **Use Cases:** Crime data retrieval, analytics, dashboards, research, integrations into AI/chat clients

---

## Features

- **MCP-compatible server**  
  - Exposes the UK Police open data API through the Model Context Protocol.  
  - Usable from any MCP-capable client (e.g., AI/chat apps that support MCP servers).

- **Static MCP endpoint**  
  - Single server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Endpoint is shared across clients; authentication occurs when adding the server to each application.

- **Crime and policing data access**  
  - Access to open data about crime and policing for England, Wales, and Northern Ireland (as provided by data.police.uk).  
  - Suitable for querying and analyzing crime statistics and related policing data.

- **Client-agnostic configuration**  
  - Works with multiple chat / AI clients that support MCP.  
  - Setup flow: connect account in Pipedream, copy MCP server URL, and add it to your chosen client.

- **Central configuration page**  
  - Dedicated configuration documentation available via the Pipedream configuration page for detailed setup steps.

> Note: The page references “Available tools” and “actions” being loaded dynamically, but specific tool names/endpoints are not listed in the provided content.

---

## Pricing

The provided content does not specify any pricing or plans for the Data.Police.UK MCP Server. Pricing, if applicable, would need to be obtained from the broader Pipedream or Workday/Pipedream documentation or account billing pages.

---

## Technical Details

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Data Source:** Official UK Police open data (data.police.uk)  
- **Regions Covered:** England, Wales, Northern Ireland

---

## Links

- **Source / App Page:** https://mcp.pipedream.com/app/data_police_uk  
- **Data.Police.UK Site & Logo:** https://data.police.uk/  
- **Pipedream Terms:** https://pipedream.com/terms  
- **Pipedream Privacy Policy:** https://pipedream.com/privacy
