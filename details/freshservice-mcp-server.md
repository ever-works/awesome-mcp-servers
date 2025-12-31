# Freshservice MCP Server

Cloud-based IT Service Management (ITSM) MCP server that links MCP-aware tools to Freshservice, enabling automated interactions with help desk tickets and knowledge base content.

## Overview
- **Type:** MCP server / connector
- **Category:** business-commerce-mcp-servers
- **Use cases:** IT ticket management, help desk automation, solution article (knowledge base) management
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP integration**
  - Static MCP server URL usable across clients
  - Authentication occurs when adding the server to an MCP-aware application
  - Supports configuration via various chat clients and tools (through Pipedream’s configuration flow)

- **Ticket management tools**
  - **Create Ticket**
    - Create new Freshservice tickets from MCP-aware clients or workflows.
  - **Get Ticket**
    - Retrieve a ticket by ID, allowing inspection of ticket details within external tools.
  - **Update Ticket**
    - Modify existing tickets (e.g., status, details) programmatically.

- **Solution / Knowledge base management tools**
  - **Create Solution Article**
    - Create new solution (knowledge base) articles in Freshservice.
  - **Get Solution Article**
    - Fetch a solution article by ID.
  - **Update Solution Article**
    - Edit and update existing solution articles.
  - **Delete Solution Article**
    - Remove a solution article from Freshservice.
  - **List Solution Categories**
    - Retrieve all solution categories for browsing or automation.
  - **List Solution Articles**
    - Retrieve all solution articles (e.g., for search, synchronization, or bulk operations).

- **Tool count**
  - 9 Freshservice actions exposed as MCP tools.

## Pricing
Pricing information is not provided in the available content.

## Links
- Product page: https://mcp.pipedream.com/app/freshservice
- MCP server URL: `https://mcp.pipedream.net/v2`
- Action documentation examples (GitHub):
  - Update Ticket: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/update-ticket/update-ticket.mjs
  - Update Solution Article: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/update-solution-article/update-solution-article.mjs
  - List Solution Categories: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/list-solution-categories/list-solution-categories.mjs
  - List Solution Articles: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/list-solution-articles/list-solution-articles.mjs
  - Get Ticket: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/get-ticket/get-ticket.mjs
  - Get Solution Article: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/get-solution-article/get-solution-article.mjs
  - Delete Solution Article: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/delete-solution-article/delete-solution-article.mjs
  - Create Ticket: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/create-ticket/create-ticket.mjs
  - Create Solution Article: https://github.com/PipedreamHQ/pipedream/blob/master/components/freshservice/actions/create-solution-article/create-solution-article.mjs