# Bloomerang MCP Server

## Overview
Bloomerang MCP Server is an MCP (Model Context Protocol) server integration that connects Bloomerang’s donor management and nonprofit fundraising platform to MCP-compatible chat or automation clients. It enables donor management and fundraising workflows to be automated and accessed programmatically through MCP.

- **Name:** Bloomerang MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Use cases:** Nonprofit donor management, CRM-style donor data access, fundraising workflow automation via MCP  
- **Provider / Platform:** Runs via Pipedream Connect MCP infrastructure  
- **MCP Server URL:** `https://mcp.pipedream.net/v2` (static URL used by clients; authentication handled during client setup)

## Features

- **MCP Integration for Bloomerang**  
  - Exposes Bloomerang donor management and fundraising capabilities through the MCP protocol.  
  - Designed to be added as a server in MCP-compatible chat or automation applications.

- **Donor Management & Nonprofit CRM Workflows**  
  - Supports workflows centered on donor management.  
  - Oriented toward nonprofit fundraising operations and CRM-style use cases.  
  - Enables building automations that interact with donor and fundraising data available in Bloomerang (exact endpoints and objects not detailed in the provided content).

- **Standardized Static MCP Endpoint**  
  - Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - Authentication and any per-account configuration are handled when adding the server to the client, not by changing the URL.

- **Client-Agnostic Setup**  
  - Can be added to multiple different MCP-capable chat clients.  
  - Configuration guidance is available via the platform’s configuration page (referenced as “Configuration page”).

- **Hosted by Pipedream Connect**  
  - The MCP server is operated on top of Pipedream Connect infrastructure.  
  - Uses Pipedream’s standard platform terms and privacy framework for the integration.

## Setup

- **MCP URL to use in clients:**  
  - `https://mcp.pipedream.net/v2`
- **Configuration:**  
  - Add this URL as an MCP server in your chosen chat/automation client.  
  - Authenticate to Bloomerang when prompted by the client during server addition.  
  - Additional configuration details are available on the referenced configuration page of the hosting platform.

## Pricing

- No pricing information is provided in the available content for the Bloomerang MCP Server or any associated plans.
