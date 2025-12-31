# Paylocity MCP Server

Online HR and payroll MCP server exposing Paylocity functionality for automated HR operations.

## Overview
- **Type:** MCP Server (Model Context Protocol)
- **Provider:** Paylocity, powered by Pipedream Connect
- **Category:** Business & Commerce – MCP Servers
- **Use Case:** Integrate Paylocity’s online HR and payroll capabilities into MCP-compatible chat clients or applications for automation and programmatic workflows.

## MCP Server URL
- **Base URL:** `https://mcp.pipedream.net/v2`
- This is a static URL used for all clients; authentication is performed when adding the server in your application.

## Features
- **MCP-compatible server endpoint** for integrating Paylocity HR and payroll operations with tools that support the Model Context Protocol.
- **Central static URL** (`https://mcp.pipedream.net/v2`) that can be reused across different clients and environments.
- **Authentication at connection time**: credentials are provided when you add the server to a chat client or application (rather than per-URL customization).
- **Works with multiple chat clients**: can be added to various MCP-enabled chat or AI assistants (specific clients configured via each client’s “add server” flow).
- **Backed by Pipedream Connect** for connection and routing to the Paylocity integration.

## Getting Started
- Copy and use the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server in your MCP-compatible chat client or application.
- Configure authentication when prompted by your client.
- Optional: refer to the provider’s full configuration documentation ("Configuration" page referenced on the source site).

## Pricing
- Not specified in the provided content.

## Additional Information
- **Source / More details:** https://mcp.pipedream.com/app/paylocity
- Terms, privacy, and cookie settings are available via Pipedream (for the integration infrastructure).