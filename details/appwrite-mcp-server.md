# Appwrite MCP Server

## Overview
The Appwrite MCP Server exposes Appwrite’s backend‑as‑a‑service capabilities—authentication, databases, functions, storage, and messaging—to MCP‑compatible clients and agents via a static MCP server URL hosted on Pipedream.

- **Category:** Cloud / DevOps MCP Servers  
- **Provider / Brand:** Appwrite (via Pipedream)  
- **Use case:** Add Appwrite backend capabilities (accounts, teams, etc.) into MCP-aware tools such as ChatGPT and other chat clients.

## Features

### MCP Server Endpoint
- **Static MCP server URL:** `https://mcp.pipedream.net/v2`  
  - Single URL used across all supported MCP clients.  
  - Authentication is handled when you add the server to your MCP-compatible application.

### Appwrite Backend Capabilities (via MCP)
- **Authentication & Accounts**  
  - Integrates with Appwrite’s account system to register and manage users.
- **Teams / Members**  
  - Access to team and members information for collaboration use cases.
- **General Appwrite Platform Access**  
  While only certain actions are explicitly exposed as tools, the server is conceptually designed around Appwrite’s core services:
  - Authentication
  - Databases
  - Functions
  - Storage
  - Messaging

### Available Tools (Actions)
Currently, the MCP server exposes three Appwrite-related actions as tools:

1. **Get Members**  
   - Retrieves account setup information (e.g., member or account metadata associated with Appwrite projects / teams).

2. **Create Team**  
   - Creates a new team in an Appwrite project.
   - Useful for organizing users into groups or workspaces programmatically from MCP clients.

3. **Create Account**  
   - Registers a new user account in an Appwrite project.
   - Supports onboarding flows and automated user provisioning via MCP-aware clients.

### Client Integration
- **Chat client support**  
  - Can be added as an MCP server to compatible chat clients (e.g., ChatGPT / OpenAI’s MCP support).  
  - Dedicated guide provided for ChatGPT; other MCP clients can use the same server URL.
- **Configuration resources**  
  - Central configuration page describes how to:  
    - Add the MCP server URL.  
    - Authenticate and connect an Appwrite account.  
    - Manage and use tools within compatible clients.

## Setup & Usage
- **Connect Appwrite account** via the Pipedream-hosted configuration flow.  
- **Copy and add MCP server URL** (`https://mcp.pipedream.net/v2`) to your MCP client.  
- **Authenticate** when prompted inside the client.  
- **Invoke tools** like `Get Members`, `Create Team`, and `Create Account` directly from supported clients.

## Pricing
No pricing details for the Appwrite MCP Server or its usage are provided in the available content.
