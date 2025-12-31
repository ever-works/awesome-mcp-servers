# MOCO MCP Server

## Overview
The MOCO MCP Server exposes MOCO’s business cloud software for agencies to MCP‑aware tools via a static MCP endpoint. It focuses on project-based businesses, covering project, time, and billing management.

- **Name:** MOCO MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Primary use:** Integrate MOCO project, time tracking, and billing features into MCP-compatible applications (e.g., AI/chat clients).  
- **MCP endpoint:** `https://mcp.pipedream.net/v2`

## Features

### Core Capabilities
- **Project business support**  
  - Designed for agencies and similar project-focused organizations.  
  - Provides access to project-related operations available in MOCO via MCP tools.

- **Time tracking**  
  - Exposes MOCO time-tracking functionality so MCP clients can interact with time data (e.g., logging or managing time entries, where supported by available tools).

- **Billing management**  
  - Bridges MOCO’s billing features into MCP-aware tools, enabling interaction with billing workflows (e.g., invoices, billable hours, where exposed).

### Integration & Configuration
- **Static MCP server URL**  
  - Single, static endpoint: `https://mcp.pipedream.net/v2` that works for every client.

- **Per-client authentication**  
  - Authentication occurs when adding the server to your application; the same URL is reused across clients, but each client authenticates separately.

- **Works with multiple chat clients**  
  - Can be added to different MCP-compatible chat or AI applications.  
  - Documentation and setup steps vary per client (select your chat client to view instructions).

- **Configuration page**  
  - A dedicated configuration page (on Pipedream) provides full setup details for connecting MOCO and managing MCP tools.

### Tools Exposure
- **MCP tools interface**  
  - The server advertises “available tools” (actions) to MCP clients, corresponding to MOCO operations (project, time, billing).  
  - Tools are dynamically loaded within the MCP client environment.

## Technical Details
- **Protocol:** MCP (Model Context Protocol) server.  
- **Host platform:** Pipedream (MCP server hosted/managed via Pipedream infrastructure).  
- **Usage pattern:** Connect MOCO account → configure MCP server URL in your app → authenticate → use exposed tools from within the MCP-aware client.

## Pricing
The provided content does not list any pricing or plans for the MOCO MCP Server. Pricing, if applicable, would need to be obtained from the MOCO or Pipedream product pages directly.