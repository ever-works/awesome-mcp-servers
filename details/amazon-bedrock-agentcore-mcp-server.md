# Amazon Bedrock AgentCore MCP Server

## Overview
The **Amazon Bedrock AgentCore Model Context Protocol (MCP) Server** lets you transform, deploy, and test Amazon Bedrock AgentCore–compatible agents directly from your development environment. It integrates with popular MCP clients to provide conversational commands for automating agent development and deployment workflows onto Amazon Bedrock AgentCore.

- **Category:** AI Integration – MCP Servers  
- **Vendor/Brand:** Amazon Web Services (AWS)  
- **Docs:** https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/mcp-getting-started.html

## Features
- **Agent transformation for AgentCore runtime**  
  - Helps convert existing agents built with supported frameworks (e.g., Strands Agents, LangGraph, CrewAI, or similar) into Amazon Bedrock AgentCore–compatible agents.

- **Deployment to Amazon Bedrock AgentCore**  
  - Supports deploying transformed agents from local development environments to the AgentCore runtime running on Amazon Bedrock.  
  - Integrates with Amazon Bedrock AgentCore services for moving agents from development to production.

- **Agent lifecycle management**  
  - Provides capabilities tied to the typical lifecycle of an agent: build, transform for runtime, deploy, and test.

- **Runtime integration**  
  - Built-in support for connecting agents to the Amazon Bedrock AgentCore runtime.  
  - Simplifies configuration required to run agents in the managed AgentCore environment.

- **Gateway connectivity**  
  - Includes support for gateway integrations used in conversational AI workflows (e.g., connecting agents to external or downstream services via gateway patterns).

- **Conversational workflow automation**  
  - Exposes conversational commands through MCP clients to automate complex agent development workflows (e.g., transform, deploy, test) from within your coding assistant or CLI.

- **Multi-client MCP compatibility**  
  - Works with multiple MCP clients, including:  
    - **Kiro**  
    - **Cursor**  
    - **Claude Code** (standalone app and VS Code extension via Claude Code CLI)  
    - **Amazon Q CLI** (and Amazon Q in IDEs via documented configuration)

- **IDE and CLI integration**  
  - Can be used from coding assistants and IDEs (such as VS Code and JetBrains via Amazon Q, or Claude Code extension).  
  - MCP server is configured via client-specific JSON configuration files (e.g., `.kiro/settings/mcp.json`, `.cursor/mcp.json`, `~/.claude/mcp.json`).

- **Local development to production path**  
  - Designed to bridge local AgentCore agent development and production-grade deployment on Amazon Bedrock AgentCore.

- **Python-based dependency support**  
  - Utilizes Python packages for AgentCore development, including:  
    - `bedrock-agentcore`  
    - `bedrock-agentcore-starter-toolkit`

## Prerequisites
- AWS account with appropriate **Amazon Bedrock AgentCore** permissions.  
- **AWS CLI** installed and configured with credentials.  
- One of the supported **MCP clients**:  
  - Kiro  
  - Cursor  
  - Claude Code  
  - Amazon Q CLI  
- An existing **AgentCore agent** built with a supported or compatible framework (e.g., Strands Agents, LangGraph, CrewAI).

## Typical Setup Workflow
1. Install required Python dependencies:  
   ```bash
   pip install bedrock-agentcore
   pip install bedrock-agentcore-starter-toolkit
   ```
2. Add the AgentCore MCP server to your MCP client’s configuration file:  
   - Kiro: `.kiro/settings/mcp.json`  
   - Cursor: `.cursor/mcp.json`  
   - Claude Code standalone: `~/.claude/mcp.json`  
   - Amazon Q: configure per-agent via Q CLI/IDE settings.
3. Use your MCP client to:  
   - Transform an existing agent for AgentCore runtime.  
   - Deploy the agent to AgentCore runtime.  
   - Test the deployed agent through conversational commands.

## Integrations
- **Amazon Bedrock AgentCore services** for hosting and running agents.
- **MCP-aware tools and assistants**, including:  
  - Kiro, Cursor, Claude Code, Amazon Q CLI, and Amazon Q in IDEs.

## Pricing
The provided documentation excerpt does not include any pricing or plan information for the Amazon Bedrock AgentCore MCP Server. Pricing, if applicable, is likely tied to Amazon Bedrock / AgentCore service usage and should be checked in the official AWS pricing pages or console.