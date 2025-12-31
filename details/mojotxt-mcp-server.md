# MojoTxt MCP Server

MojoTxt MCP Server connects MojoTxt’s texting platform for churches and nonprofits to the Model Context Protocol (MCP), enabling automated group messaging and engagement flows from compatible MCP clients.

---

## Overview
- **Type:** MCP server / messaging integration
- **Category:** Messaging MCP Servers
- **Use Cases:** Church and nonprofit communication, SMS-based engagement flows, group messaging
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

This server provides a static MCP endpoint that you add to your MCP-compatible chat client, then authenticate with your MojoTxt account to interact with MojoTxt’s texting capabilities.

---

## Features
- **Static MCP Endpoint**  
  - Single, static URL (`https://mcp.pipedream.net/v2`) used for all clients.  
  - URL remains the same across different environments and chat clients.

- **MCP Integration**  
  - Connects MojoTxt’s texting platform to any MCP-compatible client.  
  - Lets you use MojoTxt features via tools exposed in your chat interface (once configured and authenticated).

- **Authentication at Client Setup**  
  - Authentication occurs when you add the MCP server to your application / chat client.  
  - Keeps the server URL generic while securing access per client / user.

- **Support for Multiple Chat Clients**  
  - Designed to be added to various MCP-enabled chat clients.  
  - Documentation and configuration guidance are available via the linked configuration page.

- **Pipedream-Hosted**  
  - MCP server is hosted and powered by Pipedream Connect.  
  - Benefits from Pipedream’s managed infrastructure for availability and maintenance.

- **Targeted for Churches and Nonprofits**  
  - Tailored to organizations that already use, or plan to use, MojoTxt’s SMS platform for outreach, announcements, and engagement.

> Note: The underlying MojoTxt product supports SMS and group messaging for churches/nonprofits; the MCP server is specifically the integration endpoint that allows those capabilities to be accessed through MCP.

---

## Pricing
No pricing information for the MojoTxt MCP Server or MojoTxt plans is provided in the available content.

---

## Links
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **MojoTxt MCP page:** https://mcp.pipedream.com/app/mojotxt  
- **Configuration docs:** `/configuration` (on the same site)  
- **Pipedream Connect:** https://pipedream.com/connect
