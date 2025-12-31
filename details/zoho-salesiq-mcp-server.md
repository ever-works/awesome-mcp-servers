# Zoho SalesIQ MCP Server

**Brand:** Zoho  
**Category:** Business & Commerce MCP Servers  
**Slug:** zoho-salesiq-mcp-server  
**Source:** https://mcp.pipedream.com/app/zoho_salesiq

![Zoho logo](https://www.zohocorp.com/themes/zohocorp/images/logo-zoho.png)

## Overview

Zoho SalesIQ MCP Server is a Model Context Protocol (MCP) server that exposes Zoho SalesIQ’s digital customer engagement, live chat, and analytics capabilities to MCP-compatible AI agents. It enables programmatic access to website visitor and customer lifecycle data so agents can retrieve feedback data and create knowledge content directly through the MCP interface.

Static MCP server URL (for all clients):

```text
https://mcp.pipedream.net/v2
```

Authentication is performed when adding the server to an MCP-compatible application.

## Features

- **MCP-compatible server**
  - Provides a single, static server endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Can be added to various MCP-compatible chat or agent clients.
  - Uses authentication at the time of adding/configuring the server.

- **Zoho SalesIQ integration**
  - Connects to a Zoho SalesIQ account to access customer engagement data.
  - Works across marketing, sales, and support use cases.
  - Operates across all stages of the website visitor/customer lifecycle.

- **Available tools (actions)**
  - **List Feedback**
    - Retrieves a list of feedback from website visitors.
    - Useful for summarizing customer sentiment, quality monitoring, and analytics within AI workflows.
  - **Get Visitor Feedback**
    - Fetches detailed visitor feedback by conversation ID.
    - Allows AI agents to inspect specific interactions and reference them in responses or reports.
  - **Create Article**
    - Creates a new article in Zoho SalesIQ.
    - Enables AI agents to generate and publish help articles or knowledge-base entries programmatically.

- **Configuration**
  - Requires connecting and signing into a Zoho SalesIQ account.
  - Client selection and additional setup can be done via the full configuration page on Pipedream.

## Use Cases

- Analyze and retrieve website visitor feedback for reporting or sentiment analysis.
- Pull specific conversation feedback to inform AI-assisted responses or coaching.
- Auto-generate and publish support or FAQ articles based on common issues and feedback.

## Pricing

Pricing information is not provided in the available content. Users should refer to the Pipedream Zoho SalesIQ MCP Server page or Zoho/Pipedream documentation for current pricing details.