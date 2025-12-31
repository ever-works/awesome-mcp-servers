# ChainAware.ai MCP Server

## Overview
ChainAware.ai MCP Server is an MCP-compatible server that integrates ChainAware.ai’s crypto wallet auditing capabilities into tools and chat clients that support the Model Context Protocol (MCP). It enables AI agents and applications to perform security-focused analysis of cryptocurrency wallets via a standardized MCP endpoint.

## Features
- **MCP-compatible server**: Exposes ChainAware.ai’s crypto wallet auditing capabilities through the Model Context Protocol.
- **Static MCP endpoint**: Uses a single static server URL (`https://mcp.pipedream.net/v2`) that works across compatible clients.
- **Client-agnostic integration**: Can be added to multiple MCP-enabled chat clients and applications using the same server URL.
- **AI-powered wallet auditing (implied)**: Leverages ChainAware.ai’s AI-based analysis for assessing crypto wallet activity and security posture.
- **Hosted by Pipedream**: Operated as a managed MCP server instance, so users connect via configuration rather than self-hosting.

## Configuration
- Copy and use the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to any supported MCP client or application, then authenticate within that client.
- Further setup details are available via the provider’s configuration documentation (referenced as a configuration page from the source).

## Category
- Security / Attestation MCP Servers
- Tags: crypto, security, wallet-auditing

## Pricing
- Not specified in the provided content.