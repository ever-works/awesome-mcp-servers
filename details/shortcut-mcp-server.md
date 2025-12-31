# Shortcut MCP Server

**Category:** Project Management MCP Servers  
**Tags:** project-management, agile

## Overview
Shortcut MCP Server is an MCP (Model Context Protocol) server integration for the Shortcut project management platform. It gives AI agents programmatic access to Shortcut project management artifacts—such as stories, epics, and workflows—via a standard MCP endpoint.

- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Provider:** Pipedream
- **Use case:** Connect Shortcut project data to AI assistants or MCP-compatible clients.

## Features
- **Model Context Protocol server for Shortcut**  
  Exposes Shortcut project management data and actions through a standardized MCP interface.

- **Access to project artifacts**  
  Designed to work with Shortcut entities like:
  - Stories
  - Epics
  - Workflows
  (Exact tools are loaded dynamically in the UI.)

- **Static server URL**  
  Uses a single static URL (`https://mcp.pipedream.net/v2`) for all MCP clients.

- **Authentication at client configuration time**  
  You authenticate your Shortcut / Pipedream account when adding the server to your MCP-compatible application.

- **Multi-client compatibility**  
  Can be added to different chat or AI clients that support MCP (the site provides client-specific setup instructions).

- **Centralized configuration docs**  
  A dedicated configuration page is available for detailed setup steps.

## Pricing
No pricing information is provided in the available content.