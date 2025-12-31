# Slite MCP Server

An MCP Server for Slite that exposes your company knowledge base to MCP-compatible clients (like ChatGPT) for retrieval, documentation management, and collaboration workflows.

---

## Overview
- **Type:** MCP server integration for Slite
- **Category:** Document management / knowledge base
- **Provider:** Pipedream
- **Purpose:** Enable MCP-based access to Slite spaces and documents so chat-based tools can read and modify your company knowledge base.

---

## Features

### MCP Server & Connectivity
- Static MCP server URL: `https://mcp.pipedream.net/v2`
- Works with multiple MCP-compatible chat clients (e.g., ChatGPT via OpenAI)
- Authentication handled when adding the server to your application
- Central configuration via Pipedream’s configuration page

### Slite Knowledge Base Integration
- Connect a Slite account to expose workspace content to MCP clients
- Operates on your existing Slite knowledge base (documents, sub-documents, channels)
- Suitable for automating documentation and knowledge workflows

### Available Tools (Actions)
1. **Create Document**  
   - Creates a new Slite document
   - Supports choosing a parent document or a private channel as the location

2. **Update Document**  
   - Modifies an existing Slite document
   - Enables programmatic editing and maintenance of knowledge base content

3. **Fetch Sub-Documents**  
   - Fetches a specified number of sub-documents related to a parent document in Slite
   - Useful for navigating document hierarchies and retrieving related content

---

## Use Cases
- Automate creation and updating of Slite documentation from a chat-based interface
- Retrieve related sub-documents to provide context-aware answers from the knowledge base
- Manage internal knowledge, processes, and collaboration documentation through MCP-compatible tools

---

## Getting Started
- Sign in to Pipedream to connect your Slite account
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`
- Add the server to your MCP-compatible app (e.g., ChatGPT) using the provided configuration guide

---

## Pricing
The provided content does not list any pricing or plans for the Slite MCP Server. Refer to Pipedream’s main site or account billing settings for current pricing details, if applicable.