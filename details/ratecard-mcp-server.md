# Ratecard MCP Server

## Overview
Ratecard MCP Server is an MCP (Model Context Protocol) server integration for Ratecard that allows AI agents and chat-based applications to trigger and manage automated feedback and review collection workflows through systems like ATS, CRM, or ERP.

## Features
- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL works for all clients; authentication is handled when adding the server to your application.

- **Ratecard account integration**  
  - Connect an existing Ratecard account.  
  - Select a specific Ratecard “client” (or sub-account) after connecting.  
  - Verifies / checks account connection before use.

- **Feedback & review workflows**  
  - Designed to trigger automated feedback and review collection workflows.  
  - Supports workflows running via ATS, CRM, or ERP systems.

- **Surveys & forms**  
  - Integrates with Ratecard’s surveys and forms for collecting feedback.  
  - Enables AI agents to initiate or manage survey-based interactions.

- **Chat client integration**  
  - Can be added to various chat clients as an MCP server.  
  - Each chat client can follow specific setup instructions for connecting to the MCP server.  
  - Central configuration reference available via a separate configuration page.

- **Tooling exposure through MCP**  
  - Exposes Ratecard actions as MCP tools (listed as “available tools” once loaded).  
  - Tools are accessible to AI agents through the MCP protocol for programmatic use.

## Use Cases
- Automate sending feedback requests from an ATS when a candidate reaches a certain stage.  
- Trigger customer satisfaction surveys from a CRM after deal closure.  
- Collect operational feedback through ERP-driven workflows.

## Technical Details
- **Protocol**: Model Context Protocol (MCP).  
- **Base URL**: `https://mcp.pipedream.net/v2`.  
- **Authentication**: Performed when adding the server to the chat client or application (no per-client URL changes required).

## Pricing
- Not specified in the provided content.