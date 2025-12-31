# Search API MCP Server

**Category:** Web Search MCP Servers  
**Brand:** search-api  
**Slug:** `search-api-mcp-server`

Search API MCP Server provides MCP-compatible access to a real-time SERP API. It handles infrastructure concerns like proxy management, CAPTCHAs, and JSON parsing so applications can focus on consuming structured search result data.

---

## Features

- **MCP-Compatible SERP Access**  
  - Exposes a search API through the Model Context Protocol (MCP) for integration with MCP-capable chat clients and applications.

- **Real-Time Search Results**  
  - Retrieves up-to-date SERP (search engine results page) data for live web search use cases.

- **Proxy Management**  
  - Manages proxies behind the scenes to improve reliability and reduce friction when accessing search engines.

- **CAPTCHA Handling**  
  - Automatically deals with CAPTCHAs encountered during search requests, minimizing failed or blocked requests.

- **Structured JSON Output**  
  - Parses SERP responses into JSON, providing structured search result data suitable for programmatic consumption.

- **Static MCP Server Endpoint**  
  - Uses a single static MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication is performed when adding the server to your application.

- **Client-Agnostic Integration**  
  - Designed to be added to different chat or MCP-compatible clients using the same endpoint, with configuration handled per client.

---

## Configuration & Integration

- **Server URL**: `https://mcp.pipedream.net/v2` (static for all clients).  
- **Authentication**: Performed during server addition to your app or chat client.  
- **Setup Guidance**: Integration flows are provided per supported chat client, with additional details available on the platform’s configuration page.

---

## Pricing

No pricing information is provided in the available content.