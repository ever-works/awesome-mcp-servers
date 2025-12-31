# Conveyor MCP Server

Conveyor MCP Server is an MCP-compatible server that exposes Conveyor’s security review and questionnaire automation platform to MCP-capable agents, enabling programmatic access to security review workflows.

- **Website / Source**: https://mcp.pipedream.com/app/conveyor
- **Category**: Security Attestation MCP Servers
- **Tags**: security, questionnaires, compliance
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

## Features

- **MCP-compatible server**
  - Implements the Model Context Protocol (MCP) to integrate with MCP-capable chat clients and agents.
  - Uses a static server URL (`https://mcp.pipedream.net/v2`) that works across supported clients.

- **Access to Conveyor’s security review platform**
  - Exposes Conveyor’s security review and questionnaire automation capabilities to agents.
  - Designed for programmatic interaction with security review workflows (e.g., security questionnaires, compliance-related inquiries).

- **Client-agnostic setup**
  - Single static MCP server URL for all compatible clients.
  - Authentication handled when adding the server in each application/client.

- **Configuration guidance**
  - Documentation available via a central configuration page on Pipedream for adding the server to different chat clients.

## Usage

- Add the MCP server to an MCP-compatible chat client or agent using:
  - **Server URL**: `https://mcp.pipedream.net/v2`
- Authenticate within your chosen application when prompted.

## Pricing

- No pricing information is provided in the available content.