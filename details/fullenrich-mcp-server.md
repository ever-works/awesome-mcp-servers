# FullEnrich MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** FullEnrich  
**Slug:** `fullenrich-mcp-server`

## Overview
The FullEnrich MCP Server is a Model Context Protocol (MCP) server that integrates FullEnrich’s B2B email and phone waterfall enrichment into MCP-compatible applications and workflows. It is hosted via Pipedream and exposes enrichment functionality as MCP tools that can be used by chat or other MCP clients.

## Features
- **B2B Contact Enrichment**  
  - Focused on business-to-business (B2B) data.  
  - Provides enrichment of email and phone details for leads and contacts.

- **Waterfall Enrichment Logic**  
  - Uses a “waterfall” approach to enrichment (e.g., sequentially trying multiple data sources/providers or strategies to obtain valid email and phone data).  
  - Aims to maximize match and fill rates for email and phone fields.

- **MCP Server Integration**  
  - Exposed as an MCP server endpoint: `https://mcp.pipedream.net/v2`.  
  - Designed to plug into any MCP-compatible client (e.g., chat interfaces, tools, or automation environments).  
  - Authentication handled when adding the server to your application.

- **Multi-client Support**  
  - Same static MCP server URL used across clients; configuration is handled per client/application.  
  - Setup flows available for different chat/MCP clients (via Pipedream’s configuration guides).

- **Account-based Configuration**  
  - Connect a FullEnrich account and select a client/workspace within that account.  
  - Enrichment operations are performed under the connected account context.

- **Tool-based Actions**  
  - Enrichment functionality is exposed as MCP tools/actions that can be invoked programmatically by the client.  
  - Tools are auto-discovered by MCP clients when connecting to the server (actions list is loaded dynamically).

## Pricing
No pricing information is provided in the available content. Refer to the FullEnrich or Pipedream product pages for current pricing and plan details.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Protocol:** Model Context Protocol (MCP)  
- **Primary Use Case:** B2B lead and contact enrichment for email and phone data within AI/chat and workflow automation contexts.