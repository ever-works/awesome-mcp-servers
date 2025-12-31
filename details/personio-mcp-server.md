# Personio MCP Server

An MCP Server integration for Personio’s all-in-one HR software for SMEs, enabling HR actions directly from MCP-compatible chat and automation tools.

## Overview
- **Type:** MCP Server / Integration
- **Category:** Business & Commerce – MCP Servers
- **Provider / Platform:** Pipedream (for Personio)
- **Primary domain:** Human Resources (HR) for small and medium-sized enterprises
- **Base MCP server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server & Connectivity
- Static MCP server URL that works for all Personio clients.
- Authentication occurs when adding the server to your MCP-compatible application.
- Can be added to various chat clients (e.g., ChatGPT via OpenAI) following configuration guides.
- Central configuration and management via Pipedream’s MCP configuration page.

### Available Tools / Actions
The Personio MCP Server exposes 3 main actions as tools:

1. **List Employees**
   - Retrieves a list of company employees from Personio.
   - Designed for querying HR data (e.g., for overviews, checks, or workflows).

2. **Create Employee**
   - Creates a new employee record in Personio.
   - Supports automating employee onboarding flows via MCP-compatible clients.

3. **Create Application**
   - Creates a new application in Personio (e.g., job candidate application).
   - Useful for recruitment and applicant tracking workflows integrated into chat or automation tools.

## Use Cases
- Access employee lists from Personio within MCP-enabled chat clients.
- Automate creation of new employee records directly from conversational interfaces.
- Log or create new job applications programmatically from tools that support MCP.

## Pricing
- No pricing information is provided in the available content for the Personio MCP Server or its usage via Pipedream.

## Links
- **Personio Developer Docs:** https://developer.personio.de/reference/introduction
- **Personio MCP App Page (Pipedream):** https://mcp.pipedream.com/app/personio
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Configuration Guide:** https://mcp.pipedream.com/configuration
- **Tool Documentation:**
  - List Employees: https://github.com/PipedreamHQ/pipedream/blob/master/components/personio/actions/list-employees/list-employees.mjs
  - Create Employee: https://github.com/PipedreamHQ/pipedream/blob/master/components/personio/actions/create-employee/create-employee.mjs
  - Create Application: https://github.com/PipedreamHQ/pipedream/blob/master/components/personio/actions/create-application/create-application.mjs