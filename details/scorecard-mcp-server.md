# Scorecard MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Scorecard  
**Slug:** `scorecard-mcp-server`

Evaluate and optimize LLM systems with comprehensive testing and metrics via a dedicated MCP server.

---

## Overview

Scorecard MCP Server connects your MCP-compatible client to Scorecard’s AI evaluation platform. It exposes remote endpoints over Streamable HTTP and uses OAuth-based authentication, enabling LLM evaluation workflows without managing raw API keys.

- **Name/ID:** `io.scorecard/mcp`  
- **Provider:** Scorecard (scorecard.io)  
- **Release date:** Apr 26, 2025  
- **Transport:** Streamable HTTP (supports SSE under the hood)  
- **Intended use:** Evaluation and optimization of LLM systems with structured tests and metrics

---

## Features

- **LLM Evaluation Capabilities**  
  - Designed to evaluate and optimize LLM systems.  
  - Supports comprehensive testing workflows and metrics collection.

- **MCP-Compatible Remote Endpoint**  
  - Provides a remote MCP endpoint suitable for integration with MCP clients.  
  - Exact MCP configuration URL is exposed (pattern: `https://mcp.scorecard.io/...`).

- **OAuth-Based Authentication**  
  - Uses OAuth2-style flow; no manual API key setup required in the MCP client.  
  - Initiates OAuth when connecting, simplifying secure access.

- **Modern MCP Transport**  
  - Uses the current MCP spec with Streamable HTTP transport.  
  - Capable of supporting stateless servers while still leveraging Server-Sent Events (SSE) under the hood for stateful interactions.

- **Standardized server.json Definition**  
  - Official `server.json` file available, defining:  
    - Installation instructions  
    - Configuration options  
    - Usage guidelines  
  - Maintained and kept up to date by the owner of scorecard.io.

- **Ecosystem Metrics (Informational)**  
  - Estimated visitors / usage across the MCP ecosystem.  
  - Popularity ranking within global MCP server implementations.

---

## Authentication

- **Method:** OAuth  
- **Details:** The server initiates an OAuth flow on connection; clients do not need to manage API keys directly.

---

## Transport & Protocol

- **Transport type:** Streamable HTTP (current MCP spec)  
- **Capabilities:**  
  - Supports stateless server operation.  
  - Can use SSE under the hood for stateful behavior and streaming.

---

## Pricing

- **Free Tier:** Available  
  - The remote service offers a free usage tier.  
  - A paid plan may be available for higher or more advanced usage, but specific paid tiers or limits are not detailed in the provided content.

---

## Useful Links

- **Product site:** https://www.scorecard.io  
- **MCP listing:** https://www.pulsemcp.com/servers/scorecard  
- **GitHub repository:** https://github.com/scorecard-ai/scorecard-node  
- **server.json definition:** `/servers/scorecard/serverjson` on Pulse MCP (contains installation & config details)
