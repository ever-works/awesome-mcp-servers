# Outreach MCP Server

MCP Server integration for Outreach that lets Model Context Protocol (MCP) clients (such as chat-based AI tools) interact with Outreach’s sales engagement platform.

---

## Overview
- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Primary function:** Connect MCP-compatible clients to Outreach to manage prospects, accounts, and sequences programmatically.
- **Provider:** Pipedream
- **Protocol endpoint (server URL):** `https://mcp.pipedream.net/v2`

---

## Features

### MCP Server & Connectivity
- **Static MCP Server URL** usable by any compatible client:
  - `https://mcp.pipedream.net/v2`
- **Authentication at client setup time** (you authenticate when you add the server to your MCP-compatible application).
- **Works with multiple MCP clients**, including ChatGPT (OpenAI) and others that support the Model Context Protocol.
- **Configuration resources:**
  - Client-specific getting started guide (e.g., ChatGPT / OpenAI).
  - Central configuration documentation via the Pipedream MCP configuration page.

### Outreach Integration Capabilities
- **Account connection:**
  - Connect an Outreach account via sign-in to enable API-based actions.
- **Available tools (actions exposed as MCP tools):**
  1. **Create Prospect**  
     - Creates a new prospect in Outreach.  
     - Implemented as an MCP tool that uses the Outreach API to add new prospect records.
  2. **Create Account**  
     - Creates a new account in Outreach.  
     - Allows MCP clients to programmatically manage organizations / accounts in Outreach.
  3. **Add Prospect to Sequence**  
     - Adds an existing prospect to a specific Outreach sequence.  
     - Enables automated enrollment of prospects into Outreach’s sales engagement workflows.

### Usage Context
- Designed for **sales engagement and automation workflows**, such as:
  - Automating the creation of Outreach prospects and accounts from within an AI chat or other MCP client.
  - Programmatically adding prospects to Outreach sequences as part of sales workflows.

---

## Pricing
No pricing information is provided in the available content for the Outreach MCP Server or its usage via Pipedream.

---

## Links
- **Outreach developer documentation:** https://developers.outreach.io/api/
- **Pipedream MCP Outreach page:** https://mcp.pipedream.com/app/outreach
- **MCP configuration overview:** https://mcp.pipedream.com/configuration
- **Action implementations (GitHub):**
  - Create Prospect: https://github.com/PipedreamHQ/pipedream/blob/master/components/outreach/actions/create-prospect/create-prospect.mjs
  - Create Account: https://github.com/PipedreamHQ/pipedream/blob/master/components/outreach/actions/create-account/create-account.mjs
  - Add Prospect to Sequence: https://github.com/PipedreamHQ/pipedream/blob/master/components/outreach/actions/add-prospect-sequence/add-prospect-sequence.mjs
