# HackerOne MCP Server

![HackerOne Logo](https://www.hackerone.com/themes/custom/hackerone/assets/images/logos/hackerone-logo-black.svg)

## Overview
The HackerOne MCP Server is a Model Context Protocol (MCP) server that connects AI agents to the HackerOne Attack Resistance Platform. It enables programmatic access to security findings, bug bounty data, and attack resistance workflows from compatible MCP clients.

- **Category:** Security Attestation MCP Servers  
- **Brand:** HackerOne  
- **Featured:** Yes  
- **Slug:** `hackerone-mcp-server`

## MCP Endpoint
- **Base MCP Server URL:** `https://mcp.pipedream.net/v2`  
  This is a static URL used by all supported MCP clients; authentication is handled when adding the server to your application.

## Features
- **MCP-compatible server** for integrating the HackerOne Attack Resistance Platform with AI / chat-based clients that support the Model Context Protocol.
- **Programmatic access to attack resistance data**, including:
  - Security findings
  - Bug bounty information
  - Attack resistance workflows across the software development lifecycle (as exposed via the platform’s APIs through MCP).
- **Centralized configuration** via a single static URL (`https://mcp.pipedream.net/v2`) usable across different MCP clients.
- **Authentication at client setup time**, handled when adding the server to your MCP-compatible application.
- **Pipedream Connect integration**, indicating that the server is operated and delivered via Pipedream’s infrastructure.

## Use Cases
- Query and review HackerOne security findings directly from an AI assistant or MCP-compatible chat client.
- Surface bug bounty reports and related metadata programmatically within development or security tooling.
- Integrate attack resistance workflows into automated SDLC pipelines that rely on MCP-aware agents.

## Images
- Brand logo: `https://www.hackerone.com/themes/custom/hackerone/assets/images/logos/hackerone-logo-black.svg`
- Platform dashboard: `https://www.hackerone.com/sites/default/files/2023-09/hackerone-platform-dashboard.png`

## Tags
- `security`  
- `bug-tracking`  
- `vulnerability`

## Pricing
- Not specified in the provided content.