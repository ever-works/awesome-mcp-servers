# DottedSign

**Category:** Document Management Mcp Servers  
**Tags:** esignature, contracts, document-management, signing, ai-assistant  
**Source:** [github.com/DottedSign-Official/dottedsign-mcp](https://github.com/DottedSign-Official/dottedsign-mcp)

## Description
DottedSign MCP is a remote MCP server that lets AI assistants (Claude, Claude Code, ChatGPT) run a complete eSignature workflow through natural language — create signing tasks from templates, arrange the signing order, send documents to signers, track status, and manage completed contracts. It connects over streamable HTTP with OAuth authorization, so no API keys or coding are required.

## Features
- **Natural-language eSignature workflow:** Create, send, and manage signing tasks by chatting with your AI assistant.
- **Template-based tasks:** Quickly create a signing task from a saved DottedSign template.
- **Signing order control:** Arrange who signs first and route each task to the right recipients.
- **Status tracking:** Check the real-time status of pending, waiting, completed, and canceled tasks.
- **Task management:** Read task content, void or cancel tasks, and get download links for completed documents.
- **Multi-client support:** Works with Claude Desktop, Claude web, Claude Code, and ChatGPT.
- **Secure OAuth authorization:** Access is granted through DottedSign's OAuth flow and can be revoked at any time.

## Requirements
- A DottedSign account (sending signing tasks requires a paid plan)
- An MCP-compatible AI client (Claude, Claude Code, or ChatGPT)

## Installation
- Claude / ChatGPT: add a Connector with the URL `https://mcp.dottedsign.com/dottedsign-api/mcp`
- Claude Code: `claude mcp add --transport http dottedsign https://mcp.dottedsign.com/dottedsign-api/mcp`
- Authorize access by signing in to DottedSign on first use

## Pricing
The MCP connector is free and works on free AI accounts. A DottedSign account is required; full AI-powered sending features require a paid DottedSign plan (Business recommended).

## Additional Notes
- Remote server (streamable-http), endpoint `https://mcp.dottedsign.com/dottedsign-api/mcp`.
- Recipients sign through the normal DottedSign email link — no AI tool or account required on their side.

---
