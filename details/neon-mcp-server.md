# Neon MCP Server

An MCP server that provides MCP-based access to Neon’s serverless Postgres databases using Neon API keys, delivered via Pipedream.

---

## Overview
- **Type:** MCP server (developer tool / integration)
- **Platform:** Pipedream / Pipedream Connect
- **Database:** Neon serverless PostgreSQL
- **Authentication:** Neon API keys
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

This server allows compatible MCP clients (such as ChatGPT with MCP support) to programmatically manage Neon serverless Postgres resources.

---

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across supported MCP clients.
- Authentication handled when adding the server to an MCP-capable application.
- Configuration guidance available for ChatGPT (OpenAI) and via a generic configuration page.

### Neon Account Connectivity
- Connect a Neon account via Pipedream to manage serverless Postgres resources.
- Uses Neon API keys for secure access.

### Available Tools (Actions)
The Neon MCP Server exposes the following actions as MCP tools:

1. **Create Project**
   - Creates a new Neon project.
   - Intended for provisioning new logical environments within Neon.
   - Linked documentation in the Pipedream GitHub repository for parameters and usage.

2. **Create Database**
   - Creates a database within an existing Neon project.
   - Used to add new Postgres databases under a given Neon project.

3. **Create Branch**
   - Creates a branch within a Neon project.
   - Supports Neon’s branching model for development, staging, or other isolated environments.

---

## Use Cases
- Programmatically provisioning Neon serverless Postgres infrastructure from MCP-enabled chat clients.
- Automating setup of projects, databases, and branches for different environments (development, staging, production) via conversational interfaces.

---

## Pricing
The provided content does not include any pricing information for the Neon MCP Server or related Pipedream usage.