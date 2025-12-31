# Gainsight PX MCP Server

**Category:** Business & Commerce MCP Servers  
**Slug:** gainsight-px-mcp-server  
**Brand:** Gainsight

MCP server that connects to Gainsight PX to expose product experience and adoption analytics via MCP endpoints.

---

## Overview
The Gainsight PX MCP Server provides access to Gainsight PX product experience and adoption analytics through the Model Context Protocol (MCP). It is delivered as a static MCP endpoint you can add to compatible chat or AI clients, authenticating with your own Gainsight PX credentials.

---

## MCP Server Endpoint

- **Base URL:** `https://mcp.pipedream.net/v2`
- **Type:** Static URL (same for all clients)
- **Authentication:** Performed when adding/configuring the server in your application or chat client

---

## Features

- **Product Experience Data Access**  
  - Surfaces product experience metrics from Gainsight PX via MCP.  
  - Intended to help drive product adoption and time-to-value in downstream AI or chat applications.

- **Adoption & Engagement Analytics**  
  - Exposes adoption and user engagement analytics made available by Gainsight PX (e.g., usage and engagement context) through MCP endpoints.

- **Static MCP Endpoint**  
  - Single static URL for all clients; simplifies configuration.  
  - No per-tenant URL changes required; only credentials differ.

- **Client-Agnostic Integration**  
  - Can be added to any compatible chat client or AI application that supports MCP servers.  
  - Works with configuration flows documented in the Pipedream / Pipedream Connect configuration pages.

- **Pipedream Connect Integration**  
  - Hosted and powered by Pipedream Connect infrastructure.  
  - Benefits from Pipedream’s MCP server hosting, terms, and privacy controls.

---

## Getting Started

1. **Copy MCP Server URL**  
   - Use: `https://mcp.pipedream.net/v2`

2. **Add to Your Chat Client / App**  
   - In your MCP-capable client, add a new MCP server using the URL above.  
   - Complete authentication with your Gainsight PX account when prompted.

3. **Configure**  
   - Refer to the provider’s **Configuration** page for client-specific setup details.

---

## Pricing

No pricing information is provided in the available content. Consult the underlying Pipedream / Gainsight PX documentation or billing pages for current pricing details.