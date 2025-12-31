# ByteForms MCP Server

## Overview
ByteForms MCP Server is an all‑in‑one Model Context Protocol (MCP) server that exposes ByteForms’ capabilities for creating forms and surveys, managing submissions, and integrating collected data into other systems.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Surveys, data collection, online forms, submission handling, workflow and data integration

## Features

- **Form & survey creation**
  - Create and manage forms and surveys via the MCP interface.
  - Designed for general data collection scenarios (e.g., surveys, contact forms, applications).

- **Submission management**
  - Access and manage form submissions through the MCP server.
  - Centralizes incoming responses from ByteForms.

- **Data integration**
  - Surfaces ByteForms data and actions through the Model Context Protocol, enabling integration with MCP‑compatible chat clients and applications.
  - Supports use in automated workflows and assistant environments.

- **Single static MCP endpoint**
  - Uses a static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when adding the server to your application, simplifying configuration.

- **Client‑agnostic setup**
  - Designed to be added to various MCP‑compatible chat clients and applications.
  - Configuration guidance is available via the linked configuration page in the host environment.

## Configuration & Usage

- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Setup flow (high‑level):**
  - Connect your ByteForms account in the Pipedream environment.
  - Select the relevant ByteForms client/account.
  - Copy and add the static MCP server URL to your MCP‑compatible app.
  - Authenticate when prompted in your application.

## Pricing

- Pricing details are not provided in the available content. Users should refer to the ByteForms or Pipedream/Workday pricing pages for current plan information.