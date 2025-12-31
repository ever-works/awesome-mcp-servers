# Globalping MCP Server

**Brand:** globalping  
**Category:** Cloud & DevOps → MCP Servers  
**Slug:** `globalping-mcp-server`

A Model Context Protocol (MCP) server that exposes Globalping’s global network measurement and diagnostics platform to AI/LLM clients over OAuth2.1/HTTP, enabling natural-language driven network tests from thousands of probes worldwide.

> **Note:** The `@globalping/globalping-mcp` npm package is deprecated. The maintained project is at: https://github.com/jsdelivr/globalping-mcp-server

---

## Description

Globalping MCP Server implements the Model Context Protocol to let AI models (such as GPT or Claude) run and interpret internet measurement tasks using the Globalping API. It provides programmatic access to a globally distributed probe network for monitoring, debugging, and benchmarking internet infrastructure via natural language queries.

---

## Features

### Global Network & Measurements
- Access a globally distributed network of probes in thousands of locations.  
- Run network tests from many geographical regions to observe regional differences.
- Support for multiple network measurement types:
  - **Ping** (latency and reachability)
  - **Traceroute** (routing paths)
  - **DNS** (resolution and DNS behaviour)
  - **MTR** (combined ping/traceroute-style path analysis)
  - **HTTP** (HTTP connectivity and basic performance)

### MCP / AI Integration
- Implements the **Model Context Protocol (MCP)** to integrate with MCP-compatible clients.
- Designed for use by AI models like OpenAI GPT and Anthropic Claude.
- **AI-friendly interface**:
  - Output structured so LLMs can easily parse and reason about results.
  - Supports initiating new measurements based on conversation context.
- **Smart context handling**:
  - Allows intelligent selection of appropriate test types (ping, traceroute, DNS, etc.) based on the user’s natural-language request.

### Analysis & Comparison
- **Comparative analysis** capabilities:
  - Compare network performance between multiple targets.
  - Run measurements from different locations to contrast paths and latency.

### Authentication & Rate Limits
- **Token support**:
  - Can be used **without authentication**, using IP-based rate limits via Globalping’s public API.
  - Optional **Globalping API token** for higher rate limits and more reliable access.
- Designed to work with OAuth2.1 via the Globalping MCP endpoint (`https://mcp.globalping.dev/sse`) in compatible environments.

### Installation & Usage
- Distributed as an npm package (`@globalping/globalping-mcp`).
- **Global installation** (recommended) via npm or yarn to run `globalping-mcp` from anywhere.
- **No-install usage** with `npx @globalping/globalping-mcp`.
- Default server port: **3000** (configurable by environment variable).

### Platform & Environment
- Requires **Node.js v18+**.
- Works with npm or yarn.
- Windows-specific guidance:
  - Use PowerShell for better compatibility.
  - Ensure Node.js is on the PATH.
  - Use `.env` or system/user environment variables for configuration.

### Configuration

Supported environment variables include:

- `GLOBALPING_API_TOKEN`
  - Description: Globalping API token for authenticated usage and higher rate limits.
  - Default: not set (falls back to IP-based public rate limits).

- `PORT`
  - Description: Port on which the MCP server listens.
  - Default: `3000` (implied in docs as default server port).

---

## Installation & Setup (Summary)

- **Prerequisites**: Node.js 18+ (includes npm) or yarn.

- **Install globally** (example):
  ```bash
  npm install -g @globalping/globalping-mcp
  # then
  globalping-mcp
  ```

- **Run with npx** (no global install):
  ```bash
  npx @globalping/globalping-mcp
  ```

- **Windows notes**:
  - Use PowerShell (optionally as Administrator for global install).
  - Configure environment variables either via `.env` or system settings.

- **Verification**:
  - Start the server and confirm log output indicates it is listening on the configured port (default 3000).

---

## Pricing

- The Globalping API and MCP server usage described are **free to use without authentication**, subject to IP-based public rate limits.
- Using a **Globalping API token** provides **higher rate limits**.  
- No additional pricing tiers, paid plans, or detailed pricing structure are specified in the provided content.

---

## Links & Assets

- **Project (npm entry, deprecated):** https://www.npmjs.com/package/@globalping/globalping-mcp  
- **Recommended repository:** https://github.com/jsdelivr/globalping-mcp-server  
- **Globalping homepage:** https://globalping.io  
- **MCP endpoint:** `https://mcp.globalping.dev/sse`  
- **Brand:** globalping  
- **Brand logo:** https://globalping.io/favicon.ico  
- **Image / Open Graph:** https://globalping.io/img/opengraph.png