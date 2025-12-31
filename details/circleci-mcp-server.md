# CircleCI MCP Server

Continuous integration and delivery platform MCP integration

**Source:** https://mcp.pipedream.com/app/circleci

---

## Overview
The CircleCI MCP Server is an MCP (Model Context Protocol) integration that enables MCP-compatible clients (such as chat-based developer tools) to interact with CircleCI. It is designed to let clients trigger, monitor, and manage CI/CD pipelines and workflows on the CircleCI platform via a standardized MCP server endpoint.

---

## MCP Server URL
- Static MCP server URL (for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is performed when adding the server to the MCP-compatible application.

---

## Features
Based on the provided information and item description, the CircleCI MCP Server includes the following capabilities:

- **MCP Integration Endpoint**
  - Single, static MCP server URL usable across compatible MCP clients.
  - Centralized configuration via one endpoint: `https://mcp.pipedream.net/v2`.

- **CircleCI CI/CD Control (from item description)**
  - Trigger CircleCI pipelines and workflows from MCP clients.
  - Monitor status and progress of CircleCI CI/CD pipelines.
  - Manage CircleCI workflows (e.g., interact with builds and jobs) via MCP.

- **Client-Agnostic Setup**
  - Works with multiple MCP-enabled chat or automation clients.
  - Configuration instructions available per client type via the platform’s configuration page.

- **Pipedream Connect Integration**
  - Powered by Pipedream Connect as the hosting / integration layer for the MCP server.

> Note: The specific CircleCI operations exposed (e.g., listing projects, rerunning workflows, viewing artifacts) are not detailed in the provided content and would be defined within the MCP tools of this server.

---

## Configuration
- Add the MCP server to your MCP-compatible app using:
  - Server URL: `https://mcp.pipedream.net/v2`
- Follow client-specific setup instructions in the platform’s Configuration page (not included in the provided content).

---

## Category & Tags
- **Category:** cloud-devops-mcp-servers
- **Tags:**
  - cicd
  - automation
  - devops

---

## Pricing
No pricing information or plan details are provided in the available content.