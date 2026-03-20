## Overview

Make MCP server allows AI systems, such as large language models (LLMs), to run scenarios and manage the contents of your Make account. The Model Context Protocol (MCP) is a communication standard between AI and external systems, enabling safe interactions by defining endpoints and providing authentication.

## Features

### Scenario Execution

- **Run Scenarios**: Execute Make automation scenarios through AI commands
- **Scenario Management**: View and modify scenarios (paid plans only)
- **On-Demand Activation**: Scenarios must be set to active and on demand
- **Real-time Results**: Get immediate feedback from scenario execution

### Integration Capabilities

- **3,000+ Apps**: Connect to thousands of applications
- **30,000+ Actions**: Comprehensive action library
- **AI Compatibility**: Works with ChatGPT, Claude, and other MCP-compatible AI agents
- **No Local Setup**: Cloud-based server requires no additional infrastructure

## Architecture

### Cloud-Based Server

- Hosted by Make
- Runs via Streamable HTTP and Server-Sent Events (SSE)
- Stateless Streamable HTTP is the default transport method for connection reliability

### Authentication

- Generate MCP token in Make profile
- Secure communication between AI clients and Make scenarios
- Enterprise-grade security

## Available Tools

### Scenario Run Tools (All Plans)

- Execute automation workflows
- Trigger multi-step processes
- Real-time execution feedback

### Management Tools (Paid Plans)

- View scenario configurations
- Modify scenario parameters
- Access scenario analytics
- Manage workflow settings

## Use Cases

- Build Make.com automation scenarios with AI assistance
- Natural language workflow creation
- Automated data processing pipelines
- Cross-app integrations through AI commands
- Dynamic workflow adjustments
- Testing and validation of automation scenarios

## Setup Requirements

1. Make account (free or paid)
2. MCP token generated from profile
3. Active scenarios set to on-demand mode
4. Compatible MCP client (ChatGPT, Claude, etc.)

## Technical Details

- **Protocol**: Model Context Protocol (MCP)
- **Transport**: Stateless Streamable HTTP (default)
- **Events**: Server-Sent Events (SSE)
- **Hosting**: Cloud-based by Make
- **GitHub**: integromat/make-mcp-server

## Benefits

- Instant access to unique workflows
- No additional servers required
- Built-in authentication
- Reliable cloud infrastructure
- Turn complex automations into simple AI commands

## Pricing

Scenario run tools available to all plans. Management tools require paid plans. Pricing based on Make.com subscription tier.