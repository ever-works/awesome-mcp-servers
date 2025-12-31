# Confluent MCP Server

An MCP server that connects MCP-compatible tools and chat clients to Confluent’s data-in-motion platform and Kafka-based streaming capabilities.

![Confluent MCP Server](https://assets.confluent.io/m/4a59c9e4c54d7f2/webimage-confluent-cloud-console.png)

---

## Overview

- **Name:** Confluent MCP Server  
- **Category:** Database & Messaging MCP Servers  
- **Provider / Brand:** Confluent  
- **Purpose:** Expose Confluent’s Kafka-based streaming and data-in-motion capabilities to MCP-compatible applications via a standardized MCP server endpoint.

---

## Features

- **Standard MCP Endpoint**  
  - Single static MCP server URL for all supported clients:  
    - `https://mcp.pipedream.net/v2`
  - Compatible with multiple MCP-enabled chat clients and tools.

- **Confluent Integration**  
  - Connects MCP tools to Confluent’s data-in-motion platform.  
  - Built to work with Kafka-based streaming workflows and event-driven systems.

- **Client-Agnostic Setup**  
  - Same URL works across different clients; authentication is performed when adding the server in each client.  
  - Configuration guidance available via a dedicated configuration page (per-client setup instructions).

- **Hosted by Pipedream Connect**  
  - MCP server is hosted and operated via Pipedream’s “Connect” infrastructure, removing the need to self-host the MCP server.

---

## Configuration

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when you add the server to your application/client.  
- **Setup:**  
  - Add the MCP server URL in your MCP-compatible chat client or tool.  
  - Follow client-specific steps on the Configuration page (not included in the provided content).

---

## Pricing

- Not specified in the provided content.

---

## Links

- **Source / App Page:** https://mcp.pipedream.com/app/confluent  
- **Configuration Docs:** /configuration (relative path on host site)  
- **Provider:** https://confluent.io  
- **Host Platform:** https://pipedream.com/connect
