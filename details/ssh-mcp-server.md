# SSH MCP Server

## Description
SSH MCP Server is a Model Context Protocol (MCP) server that uses the Secure Shell (SSH) protocol with username and password authentication to execute commands on remote servers. It enables agents and applications to interact with and manage remote systems through SSH-based remote execution.

- Protocol: SSH
- Authentication: Password-based (username + password)
- Purpose: Remote command execution and server management

## Features
- **Remote command execution** via SSH on target servers
- **Password-based authentication** using username and password (no keys required)
- **Static MCP server endpoint** usable from any compatible client:
  - Server URL: `https://mcp.pipedream.net/v2`
- **Client-agnostic setup**: works with multiple MCP-compatible chat or agent clients
- **Centralized configuration** through the Pipedream Connect platform
- **Supports server management use cases** such as running scripts, administrative commands, and automation tasks on remote machines

## Configuration
- Add `https://mcp.pipedream.net/v2` as an MCP server endpoint in your client
- Authenticate with your SSH username and password when prompted by the client or integration
- Additional configuration details are available on the referenced Configuration page in the Pipedream interface

## Pricing
The provided content does not list any pricing or plans for SSH MCP Server.