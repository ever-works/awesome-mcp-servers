# Enginemailer MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Enginemailer  
**Source:** https://mcp.pipedream.com/app/enginemailer

## Overview
Enginemailer MCP Server is an MCP (Model Context Protocol) server integration for the Enginemailer email marketing platform. It allows MCP-compatible applications (such as chat clients or other tools) to trigger and manage Enginemailer email marketing campaigns programmatically.

A single static MCP server URL is used for all clients, with authentication handled when adding the server to each application.

## Features
- **MCP Server Integration**
  - Exposes Enginemailer email marketing capabilities through an MCP server.
  - Designed for use with MCP-based tools and chat clients.

- **Static MCP Server URL**
  - Uses a single static endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - The same URL works across different applications and chat clients.

- **Per‑Application Authentication**
  - Authentication is performed when adding the MCP server to an application.
  - Keeps the server URL generic while securing access per user/app.

- **Configurable Client Connection**
  - Users connect their Enginemailer account via the Pipedream interface.
  - Ability to select the desired client after connecting an account.

- **Tooling & Actions (MCP Tools)**
  - Provides an “Available tools” section within the MCP setup, exposing Enginemailer-related actions (exact actions not listed in the provided content, but surfaced as MCP tools once loaded).

- **Multi‑Client Integration**
  - Intended to be added to various chat clients or MCP-compatible applications.
  - Configuration guidance is available per client type via the UI and configuration documentation.

## Configuration
- Connect your Enginemailer account in the Pipedream Enginemailer MCP app.
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP client or application and authenticate during setup.
- Optional: Refer to the full configuration page on Pipedream for detailed client-specific instructions.

## Pricing
The provided content does not include any pricing information for Enginemailer MCP Server or Enginemailer services.