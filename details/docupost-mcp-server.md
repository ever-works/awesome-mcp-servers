# DocuPost MCP Server

**Category:** Business & Commerce – MCP Servers  
**Tags:** direct-mail, printing, workflow-automation

An MCP server integration for DocuPost that allows MCP-compatible tools and chat clients to trigger and manage physical mailings (letters and postcards) via DocuPost’s online mailing service.

---

## Features

- **Physical mail automation**  
  - Trigger printing, stamping, and sending of U.S. mail (letters and postcards) through DocuPost’s online mailing service.
  - Designed to be used programmatically from MCP-compatible tools and chat clients.

- **Unified MCP endpoint**  
  - Single static MCP server URL for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Authentication handled when you add the server to your application.

- **Chat client integration**  
  - Can be added to supported chat clients that speak the Model Context Protocol (MCP).
  - Central configuration via a shared MCP server URL, simplifying setup across multiple tools.

- **Workflow automation**  
  - Integrates physical mail into automated workflows and conversational agents (e.g., sending letters or postcards as part of a business or operations process).

---

## Pricing

- **Pay-as-you-go**  
  - Simple usage-based pricing starting from **$0.95 per mailing** (letters or postcards).  
  - No mention of subscriptions or tiers; charges are based on actual mail sent.

---

## Technical Details

- **MCP Server Type:** Remote HTTP endpoint for MCP-compatible clients.  
- **Base URL:** `https://mcp.pipedream.net/v2`  
- **Provider:** DocuPost (delivered via Pipedream Connect).