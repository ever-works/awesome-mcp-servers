# Loqate MCP Server

**Category:** Data Access & Integration – MCP Servers  
**Brand:** Loqate

An MCP (Model Context Protocol) server integration that exposes Loqate’s address and location intelligence services to compatible AI tools and workflows, using a lightweight server hosted via Pipedream.

![Loqate logo](https://www.loqate.com/globalassets/global/logos/loqate-logo.svg)

---

## Features

- **MCP-compatible server**
  - Provides a Model Context Protocol server endpoint for integrating Loqate services into AI applications.
- **Static server URL**
  - Single MCP endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Same URL can be reused across different MCP-compatible chat or AI clients.
- **Authentication at client setup**
  - Authentication is handled when adding the server to your application or client (per-client auth, not embedded in the URL).
- **Lightweight Go implementation**
  - Server is written in Go as a lightweight code-hosting / integration solution.
  - Designed to be easy to install and use.
- **Integration with Loqate services**
  - Intended to connect AI tools to Loqate’s address and location intelligence APIs (e.g., address verification and location data), via MCP.
- **Client-agnostic usage**
  - Can be added to various compatible chat clients or AI tooling that support MCP.
- **Configuration documentation**
  - Setup and configuration details available through a dedicated configuration page (via Pipedream Connect).

---

## Pricing

Pricing details are not provided in the available content. Refer to the linked Pipedream / Loqate resources for current pricing and plan information.

---

## Links

- Source / App page: https://mcp.pipedream.com/app/loqate
- MCP server URL: `https://mcp.pipedream.net/v2`
- Configuration docs: `/configuration` (via Pipedream Connect)
- Pipedream Connect: https://pipedream.com/connect
- Loqate brand site: https://www.loqate.com/