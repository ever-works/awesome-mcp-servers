# Keycloak MCP Server

## Description
An open-source Model Context Protocol (MCP) server for Keycloak administration that enables natural language management of Keycloak realms and users. It supports creating, deleting, and listing users and realms via MCP-compatible clients such as Claude Desktop.

## Features
- MCP server implementation for Keycloak user management
- Administration of Keycloak users and realms via natural language
- Supports creating, deleting, and listing users
- Supports creating, deleting, and listing realms
- Integrates with Claude Desktop
- Compatible with other MCP clients
- Distributed as an NPM package
- Configurable via Claude Desktop configuration file
- Supports local development and modification of the server

## Installation
- **Via Smithery**: Can be installed for Claude Desktop through Smithery using the published server configuration.
- **Via NPM (recommended)**: Available as an NPM package for installation into Node.js environments.
- **Local Development Setup**: Repository includes configuration (e.g., `tsconfig.json`, `package.json`) to run and develop the server locally.

## Configuration
- **Using NPM package**: Configure the server in the Claude Desktop configuration file to expose the Keycloak tools via MCP.
- **For local development**: Local configuration supports running the MCP server directly from the repository source.

## Available Tools
### `create-user`
- **Description**: Creates a new user in a specified realm.
- **Inputs**:
  - `realm`
  - Additional user-related fields (not fully visible in the provided content).

## Pricing
- **Open-source**: Hosted on GitHub and available to use and modify for free.