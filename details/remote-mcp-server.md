# Remote MCP Server

An MCP server for integrating Remote.com with AI agents and chat clients, enabling access to international employment operations data such as payroll-related information, time off balances, and expenses.

---

## Overview
- **Type:** MCP server / integration
- **Category:** Human Resources, Global Employment
- **Purpose:** Allow AI agents and applications to work with Remote.com data for global payroll, benefits, and compliance-related workflows.
- **Provider / Platform:** Pipedream (Pipedream Connect)
- **Static MCP Server URL:** `https://mcp.pipedream.net/v2`

---

## Features

### Core Capabilities
- Connect a Remote.com account and select a client to operate on.
- Use a single static MCP server URL for all clients, with authentication handled when adding the server to your application.
- Integrate with chat-based AI clients (e.g., ChatGPT / OpenAI) to perform HR and global employment tasks via tools.

### Available Tools / Actions
1. **Show Time Off Balance**
   - Retrieve time off balance for an employment in Remote.
   - Useful for checking available leave / PTO for a specific employee.

2. **List Employments**
   - List employments in Remote.
   - Enables agents to browse or select from existing employee / employment records.

3. **Create Expense**
   - Create an expense in Remote.
   - Supports submitting or logging expenses associated with employments.

### Configuration and Integration
- **Authentication:** Performed when connecting your Remote account through Pipedream and when adding the MCP server to your application.
- **Client Setup:**
  - Copy and use the static MCP server URL.
  - Add the server to supported chat clients (e.g., ChatGPT / OpenAI) using the provided guide.
- **Documentation:**
  - Individual tool/action docs available via linked GitHub component files.
  - Additional setup details on the Pipedream MCP Configuration page.

---

## Pricing

No pricing information is provided in the available content.