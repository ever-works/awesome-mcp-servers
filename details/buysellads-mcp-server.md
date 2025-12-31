# BuySellAds MCP Server

Integration for programmatic access to BuySellAds advertising solutions via MCP.

---

## Overview
The BuySellAds MCP Server is an MCP (Model Context Protocol) server integration that exposes BuySellAds advertising capabilities to compatible MCP clients. It enables publishers and marketers to access and work with BuySellAds programmatically from within chat or MCP-enabled applications.

---

## Features
- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL works for all supported MCP clients.

- **Account-based configuration**  
  - Connect a BuySellAds account through the Pipedream interface.  
  - Select a configured client after connecting your account.

- **MCP client integration**  
  - Designed to be added as a server to compatible MCP / chat clients.  
  - Per-client setup instructions available via the configuration flow.  
  - Can be configured by following the "Add the server to your app" guidance in the UI.

- **Tooling exposure**  
  - Exposes BuySellAds-related actions as MCP tools (actions are dynamically loaded within clients that support tool discovery).

- **Hosted by Pipedream**  
  - Managed and hosted by Pipedream, which provides the MCP server infrastructure.

---

## Use Cases
- Access BuySellAds advertising functionality from within MCP-enabled chat applications.  
- Allow publishers and marketers to interact with BuySellAds programmatically through MCP tools (e.g., for managing or querying advertising operations, where supported by the exposed tools).

---

## Technical Details
- **Protocol**: Model Context Protocol (MCP) server.  
- **Base URL**: `https://mcp.pipedream.net/v2` (static, shared across clients).  
- **Authentication**: Performed when adding/configuring the server in the client (exact method handled through Pipedream’s configuration flow).

---

## Pricing
The provided content does not list any pricing or plans for the BuySellAds MCP Server.

---

## Category & Tags
- **Category**: Business & Commerce MCP Servers  
- **Tags**: advertising, marketing, campaigns