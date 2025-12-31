# Aroflo MCP Server

Field service management MCP server for integrating Aroflo’s job, scheduling, and service data into MCP-aware tools.

## Overview
- **Type:** MCP server / integration endpoint
- **Platform:** Aroflo field service management
- **Purpose:** Surface Aroflo job, scheduling, work-order, and service data to MCP-compatible chat clients and tools.

## MCP Server URL
- **Base URL:** `https://mcp.pipedream.net/v2`
- Single static URL used for all clients
- Authentication is performed when adding the server to your application

## Features
- Provides an MCP-compatible server endpoint for Aroflo
- Enables access to Aroflo field service data (e.g., jobs, scheduling, work orders, service records) from MCP-aware tools
- Designed to be added to various chat clients that support MCP
- Central static endpoint for all clients (no per-tenant URL changes required)
- Integrates via Pipedream Connect infrastructure

## Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`
- Add the server within your MCP-capable chat client or application
- Authenticate during the server addition process
- Optional: consult the provider’s configuration documentation for client-specific setup steps

## Pricing
- Not specified in the provided content.