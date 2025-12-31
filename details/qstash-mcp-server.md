# QStash MCP Server

## Overview
QStash MCP Server is an MCP-compatible server that exposes QStash’s HTTP-based messaging and scheduling capabilities for serverless and edge runtimes. It can be added to any MCP-compatible chat client via a static server URL and used to manage QStash topics, endpoints, and message publishing.

- **Type:** MCP server / integration
- **Category:** Messaging MCP servers
- **Brand:** qstash
- **Core purpose:** HTTP-based messaging, scheduling, and webhook handling for serverless and edge environments via MCP tools.
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server Integration
- Static MCP server URL that works with all supported MCP clients.
- Authentication handled when adding the server to the client/application.
- Usable from MCP-compatible chat tools and environments.

### Messaging & Scheduling (via QStash)
- HTTP-based messaging designed for serverless and edge runtimes.
- Publish messages to topics or directly to HTTP endpoints.
- Suitable for event-driven and queue-like workflows.

### Available Tools / Actions
The MCP server exposes 7 actions as tools:

1. **Verify Webhook**
   - Verifies incoming QStash webhooks to an endpoint.
   - Intended to be used together with the **Publish Endpoint Message** action to securely validate callbacks.

2. **Publish Topic Message**
   - Publishes a message to a QStash topic.
   - Enables fan-out to multiple endpoints subscribed to the topic.

3. **Publish Endpoint Message**
   - Publishes a message directly to a specific callback HTTP endpoint.
   - Used for targeted message delivery.

4. **List Topics**
   - Lists all existing QStash topics in the connected account.
   - Useful for discovery, management, or selection of topics from within MCP clients.

5. **List Endpoints**
   - Lists all existing QStash endpoints.
   - Helps manage and inspect configured delivery targets.

6. **Create Topic**
   - Creates a new QStash topic.
   - Topics can emit messages to multiple associated endpoints (fan-out pattern).

7. **Create Endpoint**
   - Creates a new HTTP endpoint on a QStash topic.
   - Used to attach additional consumers / destinations to a topic.

## Setup
- Connect a QStash account via the Pipedream interface.
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add this server URL to the desired MCP-compatible chat client, then authenticate.

## Pricing
The provided content does not specify any pricing or plans for QStash MCP Server or QStash usage.