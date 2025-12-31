# Lob MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** Lob  
**Slug:** `lob-mcp-server`

An MCP server that exposes Lob’s direct mail automation and address verification APIs to MCP-compatible clients, enabling programmatic mail and address workflows from AI tools and chat-based applications.

![Lob logo](https://s3-us-west-2.amazonaws.com/assets.lob.com/logos/lob-logo-blue.svg)

---

## Overview

The Lob MCP Server provides a standardized MCP endpoint that lets AI tools and chat clients interact with Lob’s APIs. It focuses on:

- Direct mail automation (creating and managing physical mailings programmatically)
- Address verification (validating and standardizing mailing addresses)

The server is hosted via Pipedream Connect and is accessed through a single static URL common to all clients.

---

## MCP Server URL

Use the following static URL for all MCP clients; authentication is handled when you add the server to your application:

```text
https://mcp.pipedream.net/v2
```

---

## Features

- **MCP-compatible server**  
  - Exposes Lob’s APIs through the Model Context Protocol (MCP) for integration with MCP-aware chat clients and AI tools.

- **Direct mail automation APIs**  
  - Programmatic access to Lob’s direct mail capabilities (e.g., letters, postcards, and related mail workflows) from within MCP clients.  
  - Intended for creating, sending, and managing mail via automated workflows.

- **Address verification APIs**  
  - Programmatic address validation and verification through Lob’s address APIs.  
  - Supports building workflows that confirm address accuracy before sending mail.

- **Static endpoint for all clients**  
  - Single URL (`https://mcp.pipedream.net/v2`) used by any compatible client.  
  - Authentication is performed when configuring the server in your chosen application.

- **Integration via Pipedream Connect**  
  - Hosted and provided by Pipedream, leveraging their integration infrastructure.  
  - Can be combined with other Pipedream-based automations and tools.

- **Multi-client compatibility**  
  - Designed to be added to various MCP-supporting chat clients or AI applications.  
  - Configuration instructions vary by client, with a central configuration reference page available.

---

## Integration & Configuration

- Add the server to any MCP-compatible chat client or AI application using the static URL.  
- Authentication is configured when adding the server within your app’s MCP settings.  
- A dedicated configuration page (referenced by the provider) offers client-specific setup instructions.

---

## Pricing

Pricing information is not provided in the available content. Refer to Lob and/or Pipedream documentation or dashboards for any usage-based or subscription pricing details related to Lob’s APIs and Pipedream-hosted MCP servers.