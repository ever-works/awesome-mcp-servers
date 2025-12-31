# OpenPhone MCP Server

Modern business phone features for startups and small businesses, exposed via an MCP (Model Context Protocol) server.

> Note: The provided page content appears to reference a generic/placeholder "Quo MCP Server" but the item metadata indicates this is the **OpenPhone MCP Server** on Pipedream. The summary below is based on the MCP server scaffolding information available and the item metadata.

---

## Overview

The **OpenPhone MCP Server** is an MCP integration that exposes OpenPhone’s business phone capabilities—such as calling and messaging—inside MCP-compatible chat or AI clients. It is designed for startups and small businesses that want to integrate modern phone communication directly into their workflows.

- **Type:** MCP Server integration
- **Category:** Messaging MCP Servers
- **Use cases:** Business calling, SMS/messages, VOIP-style communication workflows
- **Audience:** Startups and small businesses needing integrated phone communications in AI/chat environments

---

## Features

### MCP Server Integration
- **Static MCP Server URL:**
  - Base server endpoint: `https://mcp.pipedream.net/v2`
  - Same URL works for all clients; authentication occurs when adding the server to your application.
- **Client-agnostic setup:**
  - Designed to be added to a variety of MCP-compatible chat clients.
  - Configuration guidance is provided per-client via the Pipedream interface.

### OpenPhone Business Phone Capabilities
*(Inferred from item metadata: “exposing modern business phone features (calls, messaging)”)*
- **Calling features:**
  - Access to OpenPhone’s call-related capabilities via MCP tools (e.g., initiating or managing calls).
- **Messaging features:**
  - Access to OpenPhone’s messaging functions (e.g., sending/receiving or managing messages) from within MCP clients.
- **Business-focused workflows:**
  - Tailored for use by startups and small businesses that rely on OpenPhone for customer and internal communication.

### Tooling within MCP
- **Available tools (actions):**
  - The server exposes a set of tools/actions (loaded dynamically in the Pipedream UI) that let AI or chat clients interact with OpenPhone.
  - Tools are discoverable by the client via MCP once the server is added.

### Configuration & Management
- **Account connection:**
  - Connect your OpenPhone-related account within Pipedream and select the appropriate client to configure.
- **Central configuration page:**
  - A dedicated configuration page (referenced as “Configuration page” in the UI) for viewing and managing the MCP server setup.

---

## Setup

1. **Connect your account** in the Pipedream OpenPhone MCP app and select the corresponding client.
2. **Copy the MCP server URL:**
   - `https://mcp.pipedream.net/v2`
3. **Add the server to your MCP-compatible client:**
   - Paste the URL and follow that client’s instructions for adding an MCP server.
4. **Authenticate:**
   - Complete authentication when prompted by your application.
5. **Use available tools:**
   - Once connected, the client can list and invoke the MCP tools that wrap OpenPhone’s phone and messaging capabilities.

---

## Pricing

The provided content does not include any pricing information for the OpenPhone MCP Server or its usage on Pipedream. Pricing, if any, would need to be obtained from the relevant Pipedream/OpenPhone product or billing pages.