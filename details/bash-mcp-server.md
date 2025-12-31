# Bash MCP Server

**Brand:** Pipedream  
**Category:** Code Execution & Automation MCP Servers  
**Tags:** shell, code-execution, automation  
**Source:** https://mcp.pipedream.com/app/bash

## Overview
Bash MCP Server is an MCP (Model Context Protocol) server by Pipedream that lets you execute Bash commands inside Pipedream workflows. It supports shell scripting and curl-based integrations through a single, reusable MCP endpoint.

## Features
- **Run Bash in workflows**: Execute arbitrary Bash commands as a step within Pipedream workflows.
- **Shell scripting support**: Use standard shell scripting constructs (e.g., piping, environment variables, file operations) within the workflow context.
- **HTTP and API calls via curl**: Make `curl` requests from Bash to integrate with HTTP APIs and external services.
- **Static MCP server URL**: Uses a single, static MCP endpoint for all clients:  
  `https://mcp.pipedream.net/v2`
- **Client-agnostic**: The same MCP server URL works for every compatible client; integration is handled on the client side.
- **Authentication at client setup**: Authentication occurs when adding the MCP server to your application or chat client.
- **Workflow integration**: Designed to be used as a step within broader Pipedream workflows, combining Bash with other triggers and actions.
- **Configuration guidance**: Dedicated configuration documentation is available via the Pipedream Configuration page.

## MCP Server URL
```text
https://mcp.pipedream.net/v2
```

## Setup & Integration
- Add the MCP server to your preferred chat client or application using the static URL.
- Authenticate during setup as required by Pipedream.
- Refer to the Pipedream Configuration page for detailed setup instructions.

## Pricing
The provided content does not list any pricing or plans for Bash MCP Server.