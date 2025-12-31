# Planhat MCP Server

An MCP (Model Context Protocol) server integration for Planhat, a customer platform focused on acquiring, servicing, and growing long-term customer relationships.

## Overview

- **Type:** MCP Server (integration endpoint)
- **Platform:** Planhat (customer success / CRM / retention)
- **Category:** Business & Commerce MCP Servers
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Provider:** Pipedream Connect

## Features

- **Static MCP Endpoint**  
  - Single static server URL (`https://mcp.pipedream.net/v2`) used for all clients.
  - Centralized entry point for MCP-compatible chat or agent clients.

- **Per-Client Authentication**  
  - Authentication is performed when adding the MCP server in your application, allowing each client to connect securely.

- **Chat Client Integration**  
  - Designed to be added to compatible chat / AI clients as an MCP server.  
  - Uses standard MCP configuration flows as described in the related configuration documentation.

- **Planhat Data & Workflows (via Planhat platform)**  
  - Intended for use with Planhat’s customer platform focused on:  
    - Customer acquisition workflows  
    - Servicing / customer success operations  
    - Long-term customer relationship management and retention

## Configuration

- **Server URL to add in your MCP-compatible app:**  
  `https://mcp.pipedream.net/v2`
- Further configuration steps are available on the linked configuration page from the source site (per client / app instructions).

## Pricing

- Not specified in the provided content.