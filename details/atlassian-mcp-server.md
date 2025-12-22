# Atlassian MCP Server

Remote MCP Server hosted by Atlassian that connects Jira and Confluence Cloud to MCP-compatible clients (LLMs, IDEs, and agent platforms) over SSE.

## Features
- **Remote MCP bridge** between Atlassian Cloud (Jira, Confluence) and external MCP clients.
- **Real-time interaction** with Jira and Confluence data via Server-Sent Events (SSE) endpoint:
  - Endpoint: `https://mcp.atlassian.com/v1/sse`.
- **OAuth 2.1 / 2.0–based authorization** for secure, scoped access.
- **Respects Atlassian permissions**:
  - Only data the user can see in Jira/Confluence is accessible.
  - Actions comply with project/space-level roles.
- **Summarize and search** Jira and Confluence content from compatible tools without switching apps.
- **Create and update** Jira issues and Confluence pages using natural language commands.
- **Bulk task processing**, such as:
  - Generating multiple tickets from meeting notes.
  - Creating tasks from product specs or other documents.
- **Works with multiple client types**:
  - LLM-based tools (e.g., Claude for Teams).
  - MCP-compatible IDE integrations (e.g., Claude desktop, VS Code, Cursor).
  - Custom MCP-compatible clients via the defined SSE endpoint.
- **Supports local MCP proxy setups** using a Node.js-based `mcp-remote` client.

## How It Works
1. A supported MCP client connects to the Atlassian MCP Server SSE endpoint: `https://mcp.atlassian.com/v1/sse`.
2. The server triggers a secure, browser-based OAuth authorization flow.
3. After authorization, the client can:
   - Stream contextual data to the server.
   - Receive real-time responses from Jira and Confluence.
4. All requests and actions are constrained by the user’s existing Atlassian Cloud permissions and OAuth token scopes.

## Requirements

### Cloud-based Setup
- An Atlassian Cloud site with **Jira** and/or **Confluence**.
- Access to an **AI client** that supports MCP (e.g., Claude for Teams).
- A **modern web browser** to complete the OAuth authorization flow.

### Desktop / Local Client Setup
- An Atlassian Cloud site with **Jira** and/or **Confluence**.
- A **supported IDE or client**, such as:
  - Claude desktop
  - VS Code
  - Cursor
  - Any custom MCP-compatible client
- **Node.js v18+** installed to run the local MCP proxy (`mcp-remote`).
- A **modern browser** to complete OAuth login.

## Data & Security
- All traffic is encrypted via **HTTPS** using **TLS 1.2 or later**.
- **OAuth 2.0 / 2.1** is used for secure authentication and access control.
- Access to Jira and Confluence data is governed by the user’s existing permissions (project/space-level roles and scopes).
- OAuth tokens are **scoped** and **session-based**.

## Rate Limits
- **Standard plan**:
  - Moderate usage thresholds (no specific numeric limit provided).
- **Premium / Enterprise plans**:
  - Higher usage quotas, including around **1,000 requests per hour** plus additional per-user limits.

## Pricing
The documentation describes **Standard** and **Premium/Enterprise** usage tiers in terms of **rate limits** but does not specify monetary pricing or subscription costs. Plans and pricing details would depend on the underlying Atlassian plan associated with your site.