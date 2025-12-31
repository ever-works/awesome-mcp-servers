# Cal.com MCP Server

Scheduling infrastructure for applications via the Model Context Protocol (MCP), provided through Pipedream Connect.

- **Website / Source**: https://mcp.pipedream.com/app/cal_com
- **Category**: Business & Commerce · MCP Servers
- **Tags**: scheduling, calendar, appointments
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

---

## Overview

Cal.com MCP Server is an MCP-compatible service that exposes Cal.com scheduling and calendar booking capabilities to MCP-enabled chat clients and applications. It provides a single, static MCP endpoint that clients can connect to, then authenticate within their own configuration.

---

## Features

- **Model Context Protocol (MCP) server**  
  - Provides a standards-based MCP endpoint for integrating Cal.com into AI/chat clients and tools.

- **Static MCP endpoint**  
  - Single URL for all clients: `https://mcp.pipedream.net/v2`.  
  - Works across compatible MCP clients; authentication is handled when adding the server to a specific app.

- **Scheduling and calendar booking**  
  - Exposes Cal.com’s scheduling and booking infrastructure over MCP.  
  - Designed for use cases involving scheduling, calendars, and appointments.

- **Client-agnostic integration**  
  - Intended to be used from multiple chat clients or applications that support MCP.  
  - Setup instructions are provided per client via the Pipedream configuration documentation.

- **Configuration documentation**  
  - A dedicated configuration page (linked from the app page) explains how to add the server to supported chat clients.

---

## Pricing

- Not specified in the provided content. No plan or pricing details are available.

---

## Usage Notes

- Use `https://mcp.pipedream.net/v2` as the MCP server URL in your client configuration.
- Authentication is performed when you add the server to your MCP-compatible application.
- For detailed setup steps, refer to the Pipedream "Configuration" page linked from the app listing.