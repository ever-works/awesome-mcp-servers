# CustomGPT MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** CustomGPT  
**Source:** https://mcp.pipedream.com/app/customgpt

## Overview
CustomGPT MCP Server is an MCP (Model Context Protocol) integration that lets you build and interact with CustomGPT chatbots from your own data sources. It exposes CustomGPT capabilities (projects/agents and conversations) as tools accessible via the MCP URL:

`https://mcp.pipedream.net/v2`

## Features

### MCP Server Integration
- Static MCP server URL that works for all clients: `https://mcp.pipedream.net/v2`.
- Authentication performed when adding the server to your client/application.
- Can be added to compatible chat clients or applications that support MCP.

### Agent / Project Management
- **Create Project (Agent)**
  - Create a new CustomGPT agent (formerly called a project).
  - Import data from a sitemap or an uploaded file.
  - System processes the provided data and builds an agent based on the imported or uploaded information.

### Conversation Management
- **Create Conversation**
  - Create a new conversation for a specific agent/project, identified by its `projectId`.
  - Initializes a fresh conversation context tied to the chosen agent.

- **Send Message**
  - Send a message to an existing conversation within a project.
  - Enables programmatic interaction with an agent using its existing conversation context.

### Available Tools (Actions)
- `Send Message` – send messages into an existing conversation.
- `Create Project (Agent)` – create a new agent from sitemap or file data.
- `Create Conversation` – start a new conversation associated with an agent.

## Data & Use Cases
- Build chatbots powered by your own data sources (e.g., sitemap-based content or uploaded documents).
- Implement RAG-like behavior and custom knowledge bases through CustomGPT agents.
- Use within any MCP-compatible environment to:
  - Spin up agents from structured or unstructured data.
  - Start new conversations programmatically.
  - Exchange messages with those conversations via tools.

## Pricing
- Not specified in the provided content.