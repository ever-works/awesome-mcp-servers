# The Bookie MCP Server

MCP server integration for The Bookie accounting software, enabling MCP-compatible agents and chat clients to access and automate bookkeeping and accounting workflows.

---

## Overview
- **Type:** MCP Server (Model Context Protocol) integration
- **Category:** Accounting / Business Management
- **Platform:** Pipedream Connect
- **Purpose:** Allow agents and chat-based applications (e.g., ChatGPT) to connect to The Bookie, manage accounts, and automate common accounting tasks.

---

## Features

### MCP Server & Connection
- **Static MCP server URL:** `https://mcp.pipedream.net/v2` (shared URL, client-specific authentication on connection).
- **Authentication per client:** Users authenticate to their own The Bookie account when adding the server to their MCP-compatible application.
- **Supports multiple chat clients:** Includes instructions for ChatGPT (OpenAI); general configuration information available via Pipedream’s configuration resources.
- **Account selection:** After connecting, you can select a specific client/company within The Bookie to work with.

### Available Tools (Actions)
The server exposes the following tools as MCP actions:

1. **Find Contacts**
   - Search and retrieve a contact from The Bookie address book.
   - Useful for looking up existing customers, vendors, or other parties before creating invoices or other records.

2. **Create Sales Invoice**
   - Create a new sales invoice in The Bookie.
   - Can be used by agents to automate invoicing workflows directly from a chat interface.

3. **Create Contact**
   - Instantly create a new contact in The Bookie address book.
   - Supports adding new customers or other entities as part of automated or conversational workflows.

---

## Configuration
- **Step 1:** Sign in via Pipedream Connect to link your The Bookie account.
- **Step 2:** Select the relevant client/company within The Bookie.
- **Step 3:** Copy the MCP server URL and add it to your MCP-compatible application (e.g., ChatGPT) following the client-specific guide.
- **Step 4:** Enable and use the provided tools (`Find Contacts`, `Create Sales Invoice`, `Create Contact`) within your agent or chat environment.

---

## Pricing
- No explicit pricing information for The Bookie MCP Server is provided in the available content.