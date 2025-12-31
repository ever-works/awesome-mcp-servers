# Darwinbox MCP Server

## Overview
The Darwinbox MCP Server is a Model Context Protocol (MCP) server that connects applications (such as chat clients) to Darwinbox, a modern HR management platform. It is provided and hosted by Pipedream.

## Category
- Business & Commerce → MCP Servers
- Human Resources / People Management

## Features
- **MCP-compatible endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works for all Darwinbox clients; authentication occurs when adding the server to your application.

- **Darwinbox integration**  
  - Designed to connect applications to Darwinbox, a new‑age HR management system.  
  - Targets HR and people‑management workflows.

- **Client-agnostic setup**  
  - Can be added to multiple chat clients or MCP‑compatible applications.  
  - Setup instructions are available per chat client via the configuration UI.

- **Central configuration page**  
  - A dedicated configuration page ("Configuration" section on Pipedream) guides users through connecting their Darwinbox account and selecting their client.

- **Account connection flow**  
  - Users connect their Darwinbox account within Pipedream before using the MCP server.  
  - The system verifies / checks the connected account during setup.

- **Tool / action discovery (within MCP)**  
  - Exposes HR‑related tools / actions from Darwinbox to the MCP client (labeled as “Available tools”).  
  - Tools are dynamically loaded by the MCP server once configured.

## Technical Details
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Protocol:** Model Context Protocol (MCP)  
- **Provider:** Pipedream  
- **Intended system:** Darwinbox HR platform  

## Pricing
No pricing information is provided in the available content.
