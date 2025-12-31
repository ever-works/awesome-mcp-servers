# AiVOOV MCP Server

MCP Server for AiVOOV, providing text-to-speech capabilities with AI voices to MCP-based applications and agents.

## Overview
- Online tool that converts input text into speech using AI-generated voices.
- Exposed as an MCP (Model Context Protocol) server, usable from compatible clients and agents.
- Accessible via a single static MCP server URL for all clients.

## Features
- **Text-to-Speech Conversion**: Turn arbitrary text input into spoken audio.
- **AI Voices**: Uses AI-generated voices to produce speech.
- **MCP Integration**: Designed to plug into MCP-based applications, agents, and chat clients.
- **Static Server Endpoint**: Single, reusable MCP server URL for all supported clients:
  - `https://mcp.pipedream.net/v2`
- **Client-Agnostic Setup**: Can be added to multiple chat clients / MCP-compatible apps using the same endpoint.

## Usage
- Configure your MCP-compatible client or application to use the server URL:
  - `https://mcp.pipedream.net/v2`
- Authenticate within your client when adding the server (authentication is handled at integration time).

## Pricing
- Not specified in the provided content.