# Netatmo MCP Server

**Category:** Home Automation MCP Servers  
**Brand:** Netatmo  
**Slug:** `netatmo-mcp-server`

## Overview
Netatmo MCP Server is an MCP server integration for Netatmo that exposes Netatmo smart home products and sensor data to MCP-compatible clients. It is designed to help developers and power users build smart home automations and workflows using Netatmo devices via a standard MCP interface.

The server is provided via Pipedream Connect and is accessible through a static MCP endpoint URL.

## Features
- **MCP integration for Netatmo**  
  - Provides an MCP-compatible interface to Netatmo smart home products and sensor data.
- **Smart home device access**  
  - Designed to interact with Netatmo smart home devices (e.g., sensors and other smart products) for monitoring and automation.
- **Sensor data access**  
  - Exposes Netatmo sensor data through MCP for use in custom workflows and automations.
- **Static MCP server URL**  
  - Single static endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`
  - The same URL is used across supported MCP clients.
- **Client-agnostic integration**  
  - Intended to work with any MCP-compatible chat client or application.
- **Authentication at client setup**  
  - Authentication is performed when adding the server to your MCP client/application (details managed via the client and Pipedream, not in this summary).
- **Configuration documentation**  
  - Additional setup and configuration details are available on a dedicated configuration page (via Pipedream Connect).

## Usage
- Add the MCP server to your MCP-compatible app or chat client using the static URL:  
  - `https://mcp.pipedream.net/v2`
- Authenticate within your client when prompted to connect your Netatmo account and access devices and data.

## Pricing
No pricing information is provided in the available content.