## Overview

WildFly MCP Server is an open-source Model Context Protocol (MCP) server that connects Large Language Models (LLMs) to running WildFly application servers. It focuses on monitoring and management use cases, allowing AI agents to work with WildFly runtime data and management APIs.

## Features

- **MCP server for WildFly**
  - Exposes WildFly server capabilities through the Model Context Protocol so MCP-compatible LLM clients can interact with WildFly.

- **Monitoring and observability integration**
  - Retrieve runtime information and metrics from running WildFly servers to support AI-assisted monitoring.

- **Logs access**
  - Allow LLMs to access WildFly server logs so they can analyze or summarize log output.

- **Management operations**
  - Invoke WildFly management operations programmatically through the MCP server, enabling AI-driven server management workflows.

- **AI tooling ecosystem (within the repo)**
  - **Container images** for running the MCP server in containerized environments.
  - **`mcp-stdio-sse-gateway`** component for bridging MCP stdio to SSE-based communication.
  - **`wait-mcp-server`** utility to wait for the MCP server to become available (useful in scripted/automated setups).
  - **`wildfly-chat-bot`** example tooling to demonstrate interactive, chat-based usage of WildFly through an AI assistant.

## Pricing

- Open-source project hosted on GitHub.
- Free to use, modify, and self-host (subject to the license terms in the repository).