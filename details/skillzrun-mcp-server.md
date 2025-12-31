# SkillzRun MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** SkillzRun  
**Slug:** `skillzrun-mcp-server`

## Description
SkillzRun MCP Server is a Model Context Protocol (MCP) server that connects AI clients to the SkillzRun learning management system (LMS). It is designed to enable AI-driven access to mobile learning and LMS capabilities provided by SkillzRun.

The server is hosted via Pipedream Connect and is exposed through a single static MCP endpoint that can be used across compatible MCP clients.

## Features
- **MCP-compatible LMS integration**: Exposes SkillzRun LMS through the Model Context Protocol so MCP-capable chat or AI clients can interact with SkillzRun data and features.
- **Mobile learning support**: Built to work with SkillzRun’s mobile-focused LMS, enabling AI workflows around mobile learning content and activities.
- **Static MCP endpoint**: Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all clients.
- **Per-client authentication**: Authentication is performed when adding the server in each client, so the same endpoint can be reused safely across different applications or users.
- **Pipedream Connect integration**: Hosted and managed via Pipedream Connect, benefiting from its infrastructure and configuration flow.

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Integration flow:**
  - Copy the static server URL.
  - Add the server in your MCP-compatible chat client or application.
  - Authenticate when prompted by the client.
  - Optionally refer to the general MCP configuration documentation (Pipedream Configuration page) for client-specific setup steps.

## Tags
- lms  
- mobile  
- education

## Pricing
No pricing information is provided in the available content.