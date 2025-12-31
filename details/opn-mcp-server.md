# OPN MCP Server

## Overview
OPN MCP Server is an MCP Server integration for OPN (formerly Omise) that provides payment processing capabilities via the MCP / Pipedream platform. It exposes OPN’s payment APIs through a standardized MCP endpoint that can be added to compatible chat or agent clients.

- **Name:** OPN MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Tags:** payments, e-commerce, API integration  
- **Provider / Brand:** OPN (formerly Omise), via Pipedream Connect  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Standard MCP endpoint**
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL works for every compatible client.

- **OPN (Omise) payment integration**
  - Integrates OPN (formerly Omise) payment processing into MCP-compatible applications.
  - Suitable for e-commerce and payment workflows.

- **Client-agnostic setup**
  - Designed to be added to various chat or agent clients that support MCP.
  - Authentication is handled when adding / configuring the server in your client.

- **Pipedream Connect platform**
  - Runs on Pipedream’s MCP / Connect infrastructure.
  - Centralized configuration and management via the Pipedream configuration page (for supported environments).

## Authentication
- Authentication is not encoded in the URL; it is performed when you add the server to your application / client.
- Each client handles auth configuration as part of its MCP server setup.

## Getting Started
1. Use the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this URL as an MCP server in your compatible chat or agent client.
3. Configure authentication as required by your client and OPN credentials.
4. Optionally refer to the full configuration documentation on the Pipedream configuration page (within the Pipedream environment).

## Pricing
The provided content does not list any pricing or plans for the OPN MCP Server integration.