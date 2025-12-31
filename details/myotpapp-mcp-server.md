# MyOTP.App MCP Server

An MCP Server integration for MyOTP.App that lets MCP-compatible agents trigger and manage SMS one-time passwords for web and mobile applications.

## Overview
- **Type:** MCP server (for MCP-compatible agents)
- **Purpose:** Enable SMS-based one-time password (OTP) workflows for authentication in web and mobile apps
- **Provider / Infrastructure:** Powered by Pipedream Connect
- **Server URL:** `https://mcp.pipedream.net/v2` (static URL used by all MCP clients; authentication is configured in the client)

## Features
- **SMS OTP delivery**
  - Trigger sending SMS-based one-time passwords for user authentication flows.
- **OTP management**
  - Manage SMS OTP lifecycle (e.g., triggering and coordinating OTP flows) via MCP-compatible agents.
- **MCP-compatible**
  - Exposes functionality through the Model Context Protocol so any supported MCP client or agent can integrate.
- **Static MCP endpoint**
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Authentication is handled when you add the server to your MCP-compatible application.
- **Web and mobile app support**
  - Designed for integrating SMS OTP into both web applications and mobile applications.
- **Hosted via Pipedream**
  - Runs on Pipedream’s MCP infrastructure (Pipedream Connect).

## Getting Started
- Use the MCP server URL: `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible client.
- Configure authentication within your chat client or MCP client as prompted.
- Refer to the platform’s configuration documentation (e.g., "Configuration" page in the hosting environment) for client-specific setup steps.

## Category
- **Directory category:** security-attestation-mcp-servers

## Tags
- sms
- authentication
- otp

## Pricing
- No pricing details are provided in the available content.