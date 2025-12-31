# Defastra MCP Server

## Overview
Defastra MCP Server is an MCP server integration that connects Defastra’s fraud detection capabilities with MCP-compatible chat or agent applications. It enriches data at scale using OSINT-powered analysis to help uncover complex fraud patterns on phone numbers and email addresses.

- **Category:** Security / Attestation MCP Server
- **Provider / Brand:** Defastra (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL usable for all clients (`https://mcp.pipedream.net/v2`).
- Authentication handled when adding the server to your MCP-compatible application.
- Usable across supported chat clients and tools that implement the MCP protocol.

### Available Tools (Actions)

#### Deep Phone Check
- Performs a risk assessment and digital lookup for a given phone number.
- Returns a **risk score** indicating whether the number is:
  - Disposable
  - Risky
  - Safe
- Provides **carrier details** (e.g., network information).
- Provides **location** details for the phone number.
- Surfaces potential **associated social profiles** where available.
- Designed to help detect fraud patterns linked to phone numbers using OSINT-enriched data.

#### Deep Email Check
- Performs a **risk analysis** on a given email address.
- Returns a **risk score** indicating whether the email is:
  - Disposable
  - Risky
  - Safe
- Intended to support fraud and risk analysis workflows involving email-based identity or activity.

## Configuration
- Users connect their Defastra account within Pipedream.
- After connection, clients can be selected and used through the MCP server.
- Full configuration instructions are available via the referenced configuration page (within Pipedream).

## Pricing
- No pricing information is provided in the available content.