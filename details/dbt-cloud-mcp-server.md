# dbt Cloud MCP Server

## Overview
The dbt Cloud MCP Server is an MCP (Model Context Protocol) integration that allows MCP-compatible tools (such as chat-based clients) to orchestrate and manage dbt Cloud transformations. It provides actions to trigger and inspect dbt jobs, runs, artifacts, and environments through a standard MCP endpoint.

- **Category:** Data analysis & exploration – MCP servers
- **Vendor / Brand:** dbt Labs (via Pipedream Connect)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server Endpoint
- **Static MCP URL:** `https://mcp.pipedream.net/v2` (works for all supported clients; authentication handled when adding the server to the application).
- Designed to be added to MCP-capable chat clients (e.g., ChatGPT / OpenAI clients) using provided configuration guides.

### Available Tools (Actions)
The server currently exposes 4 dbt Cloud actions as tools:

1. **Trigger Job Run**
   - Action: `Trigger Job Run`
   - Purpose: Start a specified dbt Cloud job.
   - Capability: Initiates execution of a dbt transformation job in dbt Cloud.

2. **Get Run**
   - Action: `Get Run`
   - Purpose: Retrieve information about a specific dbt run.
   - Capability: Accesses run metadata and status (e.g., to monitor progress or inspect results).

3. **Get Run Artifact**
   - Action: `Get Run Artifact`
   - Purpose: Retrieve information or content for a run artifact.
   - Capability: Lets clients access generated artifacts from a dbt run (for example compiled models or logs, per dbt Cloud’s API).

4. **Get Environment**
   - Action: `Get Environment`
   - Purpose: Retrieve information about a dbt Cloud environment.
   - Capability: Exposes environment-level configuration and details, enabling context-aware orchestration.

### Client Integration
- **Chat client guides:**
  - Specific guide available for ChatGPT (OpenAI) on how to add and configure the MCP server.
  - A general **Configuration** page is available with setup details for supported MCP clients.

### Authentication & Connection
- Users sign in via Pipedream to connect their dbt Cloud accounts.
- Once connected, the MCP server uses those credentials to perform actions against dbt Cloud on the user’s behalf.

## Pricing
The provided content does not include any pricing or plan information for the dbt Cloud MCP Server or related services.