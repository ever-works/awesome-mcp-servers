# AcyMailing MCP Server

## Overview
AcyMailing MCP Server is an MCP (Message Control Protocol) server on Pipedream that exposes core AcyMailing newsletter and email marketing capabilities for WordPress and Joomla applications. It provides a static MCP endpoint that applications can use to manage users and automate email workflows.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Email marketing automation, newsletter management, subscriber list management, transactional / targeted emails from apps or chat clients
- **Platform:** Runs on Pipedream MCP infrastructure

## Features

### MCP Endpoint
- **Static MCP server URL:** `https://mcp.pipedream.net/v2`
  - Single URL used for all clients.
  - Authentication is performed when adding the server to an application.

### Integration with AcyMailing
- Connects to an existing **AcyMailing** account.
- Works with **WordPress** and **Joomla** sites using AcyMailing.
- Exposes AcyMailing functionality to MCP-compatible clients (e.g., chat clients or apps integrated with Pipedream MCP).

### Available Tools (Actions)
The server provides 3 primary tools as MCP actions:

1. **Subscribe User to Lists**
   - Subscribes a user to one or more specified lists in AcyMailing.
   - Accepts user information and target list identifiers.
   - Intended for newsletter signups and list segmentation flows.

2. **Email User**
   - Sends an email to a single AcyMailing user.
   - Requires that the user already exists in the AcyMailing database.
   - Can be used for direct messages, notifications, or campaign-style sends to individuals.

3. **Add or Update User**
   - Creates a new AcyMailing user or updates an existing one.
   - If the user exists, their data is updated with the provided information.
   - Supports maintaining subscriber profiles and keeping user data in sync with other systems.

### Configuration & Usage
- Connect an AcyMailing account within Pipedream to enable the server.
- Use the static MCP URL when configuring the server in your application or chat client.
- Reference the Pipedream component documentation for detailed input/output schemas for each action (via linked GitHub docs in the original content).

## Pricing
The provided content does not include any pricing or plan information for AcyMailing MCP Server or related Pipedream usage.