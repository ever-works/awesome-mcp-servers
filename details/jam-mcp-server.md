# Jam MCP Server

Jam MCP Server is a Model Context Protocol (MCP) server for Jam.dev that lets developer tools and AI agents load Jam bug recordings (video, events, logs, network data) directly into their workflow via the OAuth2.1 endpoint `https://mcp.jam.dev/mcp`.

## Overview

- Connects Jam.dev with MCP-compatible tools (e.g., VS Code, Cursor, Windsurf, Claude Code, ChatGPT/Claude Desktop).
- Lets AI agents and IDE copilots consume Jam recordings and associated debugging data securely.
- Designed to speed up debugging by providing rich context (video, user events, console logs, errors, network requests) from Jam recordings without manual copy-paste.

## Prerequisites

To use Jam MCP, you first need a Jam recording:
- Install the Jam Chrome extension.
- Record your screen and voice.
- Stop recording to generate a Jam link for use via MCP.

## Features

### MCP Tools

Jam MCP exposes several tools to AI agents and IDEs:

- **getDetails**  
  - Returns a summary snapshot of a Jam recording.  
  - Includes who created the Jam, what happened, and guidance on what other tools to use next.

- **getConsoleLogs**  
  - Retrieves console logs captured during the Jam recording.  
  - Useful for debugging JavaScript errors, warnings, and other runtime messages.

- **getNetworkRequests**  
  - Lists all web/network requests associated with the Jam as JSON.  
  - Data is trimmed to the essentials to enable fast debugging and analysis.

- **getScreenshot**  
  - Fetches screenshots from screenshot-type Jams.  
  - Allows inspection of visual state without watching a full video.

- **getUserEvents**  
  - Returns user interaction events in plain language (clicks, inputs, page navigations, etc.).  
  - Enables agents to reconstruct user flows and reproduction steps.

- **analyzeVideo**  
  - Analyzes Jam video recordings.  
  - Extracts insights, detects issues, and provides structured feedback from the video content.

### Protocol & Transport

- Implements **Model Context Protocol (MCP)** over HTTP/SSE.  
- **OAuth2.1 endpoint**: `https://mcp.jam.dev/mcp`.  
- Backwards compatible with the deprecated **HTTP+SSE transport** as defined in the MCP specification.

### Usage Flow

1. Configure Jam MCP in a supported client (e.g., VS Code, Cursor, Windsurf, Claude Code, ChatGPT/Claude Desktop) using the provided HTTP/SSE endpoint.
2. Record a Jam and copy its link.
3. Paste one or more Jam links into an MCP-enabled client/agent.
4. Authenticate your IDE or agent with Jam when prompted.
5. Approve tool requests (e.g., calls to `getConsoleLogs`, `getNetworkRequests`, etc.).

### Example Use Cases

- Bug analysis and debugging with full context (video, logs, network data, and user events).
- Product feedback review with concrete recordings and structured metadata.
- Guiding AI agents to propose debugging plans and changes based on real user sessions.

## Integrations & Configuration Notes

- **ChatGPT / Claude Desktop**: Connect Jam via their “Apps & Connectors” / “Connectors Directory” flows, then authorize workspace access.
- **Claude Code**: Install Claude Code in your IDE and configure Jam MCP as a connector.
- **Cursor**: Add the Jam MCP server via the provided deep link or MCP configuration, then restart Cursor.
- **Visual Studio Code / Windsurf**:  
  - Use `>MCP: Add Server`.  
  - Transport: HTTP / HTTP (Server-Sent Events).  
  - Endpoint: `https://mcp.jam.dev/mcp`.  
  - Name: `Jam`.  
  - Ensure `mcp.json` reflects this server configuration.

## Pricing

- The provided content does not include any pricing or plan information for Jam MCP Server.