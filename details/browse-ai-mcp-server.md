# Browse AI MCP Server

An MCP (Model Context Protocol) server integration for Browse AI that lets MCP-compatible agents control Browse AI robots to extract structured data from websites without coding.

---

## Overview

- **Type:** MCP server / developer tool
- **Purpose:** Enable MCP-compatible chat or AI clients to trigger and control Browse AI robots for web data extraction.
- **Primary use case:** No-code web scraping and structured data extraction from arbitrary websites via an MCP endpoint.
- **Endpoint:** `https://mcp.pipedream.net/v2`

---

## Features

- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`.  
  - Same URL works across different MCP clients; authentication is handled when adding the server to the client or application.

- **Integration with Browse AI robots**  
  - Lets MCP-compatible agents control Browse AI robots for web scraping tasks.  
  - Focused on extracting **structured data** from arbitrary websites.  
  - Designed to avoid manual coding for most scraping workflows.

- **No-code data extraction**  
  - Targets users who want to automate data collection without writing scraper code.  
  - Relies on preconfigured or existing Browse AI setups, exposed as tools via MCP.

- **Client-agnostic configuration**  
  - Can be added to various MCP-enabled chat clients or applications.  
  - Documentation and examples are available per client type via the configuration guidance.

- **Configuration support via Pipedream**  
  - Provides a guided configuration flow (“Configure Browse AI”) to connect a Browse AI account.  
  - Includes a dedicated configuration page for detailed setup.

- **Tool discovery in clients**  
  - Once connected, available tools / actions (i.e., Browse AI operations) are discoverable from within the MCP client as the server loads “available tools” and “actions.”

---

## Technical Details

- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the MCP server to the client/application (details provided in client-specific or configuration documentation).
- **Provider:** Pipedream (Browse AI integration hosted and managed via Pipedream’s MCP infrastructure).

---

## Pricing

The provided content does not include any pricing or plan information for the Browse AI MCP Server. For pricing details, refer to the Browse AI and/or Pipedream websites directly.