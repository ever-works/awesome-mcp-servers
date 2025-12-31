# Telnyx MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Telnyx  
**Slug:** `telnyx-mcp-server`

Exposes Telnyx telecommunications APIs to LLM agents via authenticated Model Context Protocol (MCP) endpoints, enabling programmable communications such as voice calling, SMS/MMS messaging, phone number management, and related telecom workflows.

![Telnyx](https://telnyx.com/_next/image?url=%2Fimages%2Fresources%2Ftelnyx-mission-control-portal.png&w=1200)

---

## Overview

The Telnyx MCP Server integrates Telnyx's telecom capabilities into MCP-compatible clients. It provides MCP tools that wrap Telnyx APIs for building communication applications and workflows, including voice, messaging, phone number operations, storage interactions, and webhook handling.

- **MCP server name:** `com.pulsemcp.mirror/telnyx`  
- **Server definition:** Official `server.json` file available (standardized MCP configuration: installation, auth, and usage details).  
- **Maintainer note:** `server.json` currently managed by PulseMCP until published to the official MCP registry by the primary maintainer.

---

## Features

### Telecom & Messaging Capabilities

- **Voice calling integration**  
  - Tools for initiating and managing voice calls via Telnyx’s telephony APIs.

- **SMS/MMS messaging**  
  - Send and manage SMS and MMS messages through Telnyx messaging APIs.

- **Phone number management**  
  - Interact with Telnyx phone number APIs (e.g., buying/assigning numbers, configuration workflows) via MCP tools.

### Workflow & Tooling Scope

- **60+ MCP tools**  
  - Broad tool surface for building communication applications and telecom workflows on top of Telnyx APIs.

- **Webhook handling**  
  - Tools to work with Telnyx webhooks for event-driven workflows (e.g., call status, message delivery events) in MCP clients.

- **Cloud storage integration**  
  - Interfaces with Telnyx-related cloud storage operations (e.g., for media or call-related assets) as MCP tools.

### MCP Integration

- **Model Context Protocol endpoints**  
  - Exposes Telnyx functionality as authenticated MCP endpoints usable by LLM agents.

- **Standardized configuration**  
  - `server.json` describes:
    - Installation details
    - Configuration/auth options (e.g., Telnyx API credentials)
    - Usage guidelines for all exposed tools

---

## Pricing

No pricing information is provided in the available content for this MCP server or its usage. Refer to Telnyx’s main site and documentation for API and telecom usage pricing, and to the MCP server repository/registry entry for any server-specific cost notes if applicable.
