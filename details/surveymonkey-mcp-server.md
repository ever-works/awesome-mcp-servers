# SurveyMonkey MCP Server

## Overview
The SurveyMonkey MCP Server is an MCP-compatible integration that exposes SurveyMonkey’s online survey creation and management capabilities to chat clients, tools, and AI agents via Pipedream. It allows authenticated applications to list and inspect surveys, collectors, responses, and account information through a static MCP server URL.

- **Category:** Business & Commerce – MCP Servers
- **Provider / Brand:** SurveyMonkey (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server endpoint usable across clients: `https://mcp.pipedream.net/v2`.
- Works with multiple chat clients and MCP-compatible applications.
- Authentication handled when adding the server to the client/app.

### Survey & Response Management Tools (Actions)
The server exposes 7 actions as tools:

1. **List Surveys**
   - Retrieve a list of all surveys in the authenticated SurveyMonkey account.

2. **List Survey Responses**
   - Retrieve responses for a specific survey.

3. **List Survey Collectors**
   - Retrieve the list of collectors associated with a survey.

4. **Get Response Details**
   - Retrieve detailed information for a specific survey response.

5. **Get My Info**
   - Retrieve details about the authenticated SurveyMonkey account.

6. **Get Collector Details**
   - Retrieve detailed information for a specific collector.

7. **Get Survey Details**
   - Retrieve detailed information for a specific survey.

### Usage & Configuration
- Connect a SurveyMonkey account through Pipedream.
- Add the MCP server URL to a supported chat client or MCP application.
- Configuration guidance available via Pipedream’s configuration documentation (not client-specific in this summary).

## Tags
- Surveys
- Customer Feedback
- Data Collection

## Pricing
Pricing information for the SurveyMonkey MCP Server is not provided in the available content.