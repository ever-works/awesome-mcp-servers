# Testmo MCP Server

**Category:** Testing & Debugging Tools  
**Brand:** Testmo  
**Source:** https://mcp.pipedream.com/app/testmo

## Overview

Testmo MCP Server is a Model Context Protocol (MCP) server that connects AI agents to Testmo’s unified test management platform. It provides programmatic access to manual, exploratory, and automated test data and operations, with integrations into common DevOps tools such as Jira, GitHub, and GitLab.

## Features

- **Unified test management access**
  - Work with manual, exploratory, and automated tests via a single MCP server endpoint.
  - Leverage Testmo’s integrations with common DevOps tools (e.g., Jira, GitHub, GitLab) through the underlying Testmo platform.

- **Static MCP server endpoint**
  - Single static URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication handled when adding the server to your application or client.

- **Project sessions access**
  - **List Project Sessions**
    - Retrieve all sessions for a given Testmo project.
    - Use for analysis, reporting, or feeding session data into AI workflows.

- **Automation run management**
  - **List Automation Runs**
    - List all automation runs for a specified Testmo project.
    - Useful for discovering existing runs and their status before updating or appending results.
  - **Create Automation Run**
    - Create a new automation run in a target project.
    - Prepares a run for subsequent addition of threads and test results.

- **Automation run enrichment**
  - **Append to Thread in Automation Run**
    - Append test artifacts, custom fields, or test results to an existing thread within an automation run.
    - Enables incremental result reporting or artifact attachment as tests execute.
  - **Append to Automation Run**
    - Append test artifacts, fields, or external links directly to an existing automation run.
    - Supports enhancing runs with additional context, documentation, or evidence.

- **Client-agnostic configuration**
  - Works across multiple chat or AI clients that support MCP.
  - Central configuration guidance available via the Pipedream configuration page (for setting up the server in different clients).

## Available Tools (Actions)

1. **List Project Sessions**  
   List all sessions for a project.

2. **List Automation Runs**  
   List all automation runs for a project.

3. **Create Automation Run**  
   Create a new automation run in a target project.

4. **Append to Thread in Automation Run**  
   Append test artifacts, fields, or test results to an existing thread in an automation run.

5. **Append to Automation Run**  
   Append test artifacts, fields, or links to an existing automation run.

## Pricing

No pricing information is provided in the available content for the Testmo MCP Server on Pipedream.