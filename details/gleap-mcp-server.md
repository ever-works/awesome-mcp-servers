# Gleap MCP Server

Bug reporting and customer feedback integration for mobile apps and websites via the Model Context Protocol (MCP).

## Overview
The Gleap MCP Server exposes Gleap’s bug reporting and customer feedback capabilities to MCP-compatible clients, allowing applications and tools to access and work with feedback data from mobile apps and websites.

- **Type:** MCP server integration
- **Category:** Testing & Debugging Tools
- **Use cases:** Bug tracking, customer feedback collection, analytics
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Unified MCP endpoint**  
  - Single static MCP server URL (`https://mcp.pipedream.net/v2`) used across compatible clients.  
  - Authentication handled when adding the server to your application.

- **Bug reporting integration**  
  - Connects to Gleap’s bug reporting system for mobile apps and websites (via MCP).  
  - Enables access to bug reports within MCP-enabled tools and chat clients.

- **Customer feedback access**  
  - Provides access to customer feedback data collected through Gleap.  
  - Facilitates feedback analysis and handling through MCP clients.

- **MCP client compatibility**  
  - Designed to be added to supported chat clients and MCP applications.  
  - Configuration guided via client-specific instructions and a central configuration page.

- **Pipedream Connect integration**  
  - Hosted and powered by Pipedream Connect’s MCP infrastructure.

## Configuration
- Add the MCP server to your chosen chat client or MCP-compatible app using:  
  `https://mcp.pipedream.net/v2`
- Authentication and setup occur when you register the server in your client.
- Additional configuration details are available via the platform’s Configuration page (not included in the provided content).

## Pricing
- Not specified in the provided content.