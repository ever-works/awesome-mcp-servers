## Overview

Everything MCP Server is a comprehensive reference and test server for the Model Context Protocol (MCP). It is designed primarily for MCP client developers to explore and validate protocol features, rather than for production use. The server aggregates prompts, tools, resources, sampling, and other protocol capabilities in a single implementation.

## Key Details

- **Name:** Everything MCP Server  
- **Type:** Reference / example MCP server  
- **Purpose:** Exercise and demonstrate the full range of MCP protocol features for client builders  
- **Source URL:** https://github.com/modelcontextprotocol/servers/blob/main/src/everything/README.md  
- **Category:** Reference implementations & examples  

## Features

- **Comprehensive MCP feature coverage**  
  - Implements a wide range of MCP protocol primitives.  
  - Designed to exercise “all the features” of the protocol as much as possible.

- **Prompts**  
  - Includes registered prompts to demonstrate how MCP prompts are defined and used.

- **Tools**  
  - Registers multiple MCP tools to showcase tool invocation and handling within clients.

- **Resources**  
  - Exposes resources to illustrate MCP resource discovery and access patterns.

- **Sampling and advanced protocol behavior**  
  - Demonstrates sampling-related capabilities and other advanced protocol behaviors.

- **Documentation for internals and extension**  
  - **Architecture:** Detailed description of the server architecture.  
  - **Project Structure:** Explanation of how the codebase is organized.  
  - **Startup Process:** Step‑by‑step view of how the server starts and initializes features.  
  - **Server Features:** Complete list of registered MCP primitives and protocol features.  
  - **Extension Points:** Guidance on how to extend or customize the server.  
  - **How It Works:** Conceptual and technical overview of internal operation.

- **Multiple transport support**  
  - **stdio transport:** Supported and demonstrated (e.g., for Claude Desktop and VS Code).  
  - **HTTP + SSE transport:** Can be run from source with HTTP+SSE (noted as deprecated as of 2025‑03‑26 but still demonstrable).

- **Client integration examples**  
  - **Claude Desktop:** Example configuration for `claude_desktop_config.json` using `npx @modelcontextprotocol/server-everything`.  
  - **VS Code (MCP support):**  
    - Example user‑level MCP configuration via `mcp.json`.  
    - Example workspace configuration via `.vscode/mcp.json` for sharing settings.  
    - Uses `npx -y @modelcontextprotocol/server-everything` as the command.

- **Run from source**  
  - Example commands to install dependencies and start the server from the `src/everything` directory.  
  - SSE run example: `npm run start:sse` (with HTTP+SSE transport).

## Installation & Usage (Summarized)

- **Via `npx` (recommended for quick setup)**  
  - Command: `npx -y @modelcontextprotocol/server-everything`  
  - Used as the executable in both Claude Desktop and VS Code configurations.

- **From source**  
  - Navigate to `src/everything` in the repository.  
  - Install dependencies: `npm install`.  
  - Start with SSE transport (deprecated but available): `npm run start:sse`.

## Intended Audience

- MCP client developers and tool builders who need a comprehensive, feature‑rich reference server to test, debug, or demonstrate MCP capabilities.

## Pricing

- No pricing information is provided in the referenced content. The project is hosted publicly on GitHub and appears to be open source, but specific licensing and cost details should be confirmed directly in the repository (e.g., LICENSE file).