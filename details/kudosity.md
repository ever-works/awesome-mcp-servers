# Kudosity MCP Server

Official Kudosity MCP server for sending SMS, RCS and WhatsApp messages, searching API docs, generating code and running live API requests from AI assistants.

## Basic Info

- **Name:** Kudosity MCP Server
- **Category:** Messaging MCP Servers
- **Brand:** Kudosity
- **Source URL:** https://developers.kudosity.com/docs/mcp
- **MCP Endpoint:** `https://developers.kudosity.com/mcp`
- **Tags:** `sms`, `whatsapp`, `messaging`, `official`

## Features

- **API discovery:** list messaging APIs (SMS, RCS, MMS, WhatsApp), endpoints, parameters and security schemes.
- **Documentation search:** search API specs and tutorials.
- **Code generation:** ready-to-run snippets in curl, JavaScript, Python and more.
- **Live execution:** run real API requests, such as sending a test SMS, with your credentials.
- Covers the Transmit Message API (v2: SMS, RCS, MMS, WhatsApp, webhooks) and the Transmit SMS API (v1).

## Setup

- Remote server: `https://developers.kudosity.com/mcp`
- Claude Code: `claude mcp add kudosity --scope project -- npx mcp-remote https://developers.kudosity.com/mcp`
- v1 endpoints use Basic auth (API key and secret); v2 endpoints use an API key in the `x-api-key` header.
