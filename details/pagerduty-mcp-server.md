# PagerDuty MCP Server

**Category:** Monitoring  
**Tags:** incident-management, alerting

An MCP (Model Context Protocol) server that connects PagerDuty’s real-time operations and incident response capabilities to MCP-compatible clients, enabling alerting, on-call, and incident workflows directly from chat or other MCP-aware tools.

---

## Features

- **Standard MCP Endpoint**  
  - Provides a single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works with any compatible MCP client; authentication occurs when adding the server to the application.

- **Incident Triggering**  
  - Trigger new PagerDuty incidents from within your MCP client.  
  - Uses PagerDuty’s incident API via the MCP server for real-time alert creation.

- **Incident Acknowledgement**  
  - Acknowledge existing incidents directly through the MCP workflow.  
  - Supports updating incident state to reflect ownership and in-progress work.

- **Incident Resolution**  
  - Resolve existing PagerDuty incidents via MCP actions.  
  - Enables closing the loop on alerts without leaving the MCP client.

- **On‑Call User Lookup**  
  - Find the current on-call user for a specific PagerDuty schedule.  
  - Useful for routing incidents, escalations, and notifications from chat.

- **Client Integration Guides**  
  - Example setup instructions for ChatGPT (OpenAI) as an MCP client.  
  - Links to a general configuration page for using the server with other MCP clients.

- **Account Connection & Management**  
  - Connect a PagerDuty account via Pipedream to authorize the MCP server.  
  - Manage credentials and account connections through the Pipedream UI.

---

## Configuration

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup Steps (high level):**  
  1. Sign in to Pipedream and connect your PagerDuty account.  
  2. Add the MCP server URL to your MCP-compatible client (e.g., ChatGPT).  
  3. Authenticate when prompted and enable available tools/actions.

---

## Pricing

- No specific pricing information is provided for the PagerDuty MCP Server on the referenced page. Pricing, if any, would depend on Pipedream and/or PagerDuty plans and is not detailed in the available content.
