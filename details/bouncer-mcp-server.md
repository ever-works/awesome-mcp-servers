# Bouncer MCP Server

## Overview
Bouncer MCP Server is an MCP (Model Context Protocol) server integration for Bouncer’s email validation and verification platform. It allows MCP-compatible clients and tools to programmatically validate and verify email addresses via a static server endpoint.

- **Type:** MCP server integration
- **Category:** Security / Attestation MCP Servers
- **Use case:** Programmatic email validation and verification within MCP-enabled applications
- **Static MCP server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible email verification**: Exposes Bouncer’s email validation and verification capabilities as tools accessible through the MCP protocol.
- **Static server endpoint**: Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all supported clients.
- **Account-based authentication**: Requires connecting a Bouncer/Pipedream account; authentication occurs when adding the server to an MCP-compatible application.
- **Client-agnostic configuration**: Designed to be added to various chat or MCP clients; configuration instructions are provided per client type via the configuration page.
- **Central configuration page**: A dedicated configuration page (via Pipedream) guides users through connecting accounts and setting up the server with different clients.

## Integration & Usage
- Connect your account on the configuration page.
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-enabled app or chat client, then authenticate when prompted.

## Pricing
Pricing information is not provided in the available content.