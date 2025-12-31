# Gmail Headless MCP Server

## Overview
Gmail Headless MCP Server is a Model Context Protocol (MCP) server that enables sending and retrieving Gmail messages without requiring local Gmail credentials, tokens, or filesystem configuration on the client side. It is designed to be remote-hostable and used as an email integration for MCP-compatible clients.

- **Category:** Messaging MCP Servers  
- **Brand:** Google (community-built integration)  
- **License:** MIT  
- **Source Code:** https://github.com/baryhuang/mcp-headless-gmail

## Features
- **Headless Gmail access**  
  - Interact with Gmail (get and send emails) without storing credentials or tokens locally on the client.  
  - Suitable for remote deployment where authentication and configuration are handled on the server side.

- **MCP server implementation**  
  - Implements the Model Context Protocol to expose Gmail operations as tools/endpoints.  
  - Usable by MCP-compatible agents/clients for email workflows.

- **Email retrieval**  
  - Provides operations to retrieve Gmail messages (e.g., inbox reading, message access).  
  - Designed for programmatic access to emails via MCP.

- **Email sending**  
  - Provides operations to send Gmail messages via MCP tools.  
  - Allows agents or applications to draft and send messages through a connected Gmail account.

- **Remote-hostable architecture**  
  - Intended to run on a remote environment (server or container).  
  - Centralizes Gmail configuration and token handling away from individual clients.

- **Containerization support**  
  - Includes a `Dockerfile` for container-based deployment.  
  - Simplifies running the MCP server in cloud or on-prem environments.

- **Multi-language tooling**  
  - JavaScript/Node-based server entry (`server.js`).  
  - Python project configuration (`pyproject.toml`), indicating Python tooling or packaging support.  
  - Node dependencies managed via `package.json` and `package-lock.json`.

- **Version & dependency management**  
  - Uses `uv.lock` and `pyproject.toml` for Python dependency locking.  
  - Uses `package-lock.json` for Node dependency locking.

## Pricing
- No paid plans are indicated.  
- Distributed under the MIT open-source license; usage is free subject to license terms.
