# Levity MCP Server

MCP server that connects MCP-compatible clients to Levity’s custom AI workflows for classifying documents, images, and text, enabling automation of repetitive tasks directly from AI tools.

---

## Basic Information

- **Name:** Levity MCP Server  
- **Category:** AI Integration – MCP Servers  
- **Brand:** Levity (powered by Pipedream Connect)  
- **Slug:** `levity-mcp-server`  
- **Source URL:** https://mcp.pipedream.com/app/levity

---

## Description

Levity MCP Server exposes Levity’s AI classification workflows (for documents, images, and text) over the Model Context Protocol (MCP). This lets MCP-compatible chat and AI clients use Levity-trained models to automate repetitive, classification-driven tasks from within existing AI workflows.

---

## Features

- **MCP-compatible server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Usable with any MCP-compatible client or chat application.

- **Levity workflow access**  
  - Connects to Levity’s custom AI workflows.  
  - Designed for classification of:  
    - Documents  
    - Images  
    - Text

- **Automation of repetitive tasks**  
  - Offloads daily, repetitive, classification-based tasks to AI.  
  - Intended to improve team productivity by integrating classification directly into existing tools.

- **Authentication model**  
  - Single static URL for the server.  
  - Authentication is handled when adding/configuring the server in the client or application.

- **Client integration guidance**  
  - Instructions available for adding the server to specific chat clients.  
  - Central configuration guidance via a dedicated configuration page (`/configuration` on the host site).

- **Powered by Pipedream Connect**  
  - Hosted and provided via Pipedream’s integration platform (Pipedream Connect).

---

## Integration & Usage

- **Server URL for MCP clients:**  
  - Use `https://mcp.pipedream.net/v2` as the MCP server endpoint.  
- **Setup flow:**  
  - Add the MCP server URL to your MCP-compatible chat client or AI application.  
  - Authenticate as prompted by the client during setup.  
- **Configuration reference:**  
  - Additional configuration details are available via the platform’s "Configuration" page.

---

## Pricing

- No pricing information is provided in the available content.

---

## Tags

- ai-integration  
- automation  
- classification
