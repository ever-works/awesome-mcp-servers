## Overview

The Amazon Bedrock AgentCore Model Context Protocol (MCP) server helps you transform, deploy, and test Amazon Bedrock AgentCore-compatible agents directly from your preferred development environment. With built-in support for runtime integration, gateway connectivity, and agent lifecycle management, the MCP server simplifies moving from local development to production deployment on Amazon Bedrock AgentCore services.

## Features

### Stateful MCP Server Support (March 2026)

Amazon Bedrock AgentCore Runtime now supports stateful Model Context Protocol (MCP) server features, enabling developers to build MCP servers that leverage:

- **Elicitation**: Collect user input interactively during tool execution
- **Sampling**: Request LLM-generated content from clients
- **Progress Notifications**: Provide real-time progress updates for long-running operations
- **Long-Running Tasks**: Support for tasks up to 8 hours

### Server-Side Tool Execution (February 2026)

Amazon Bedrock now enables server-side tool execution through Amazon Bedrock AgentCore Gateway integration with the Responses API. Customers can connect their AgentCore Gateway tools to Amazon Bedrock models, enabling server-side tool execution without client-side orchestration.

### Documentation Access

Comprehensive access to Amazon Bedrock AgentCore documentation, enabling developers to search and retrieve detailed information about:

- AgentCore platform services and APIs
- Tutorials and best practices
- Runtime, Memory, Code Interpreter, Browser services
- Gateway, Observability, and Identity features

## Regional Availability

Stateful MCP server features are supported in AgentCore Runtime across fourteen AWS Regions:

- US East (N. Virginia), US East (Ohio), US West (Oregon)
- Asia Pacific (Mumbai), Canada (Central)
- Asia Pacific (Seoul), Asia Pacific (Singapore)
- Asia Pacific (Sydney), Asia Pacific (Tokyo)
- Europe (Frankfurt), Europe (Ireland)
- Europe (London), Europe (Paris), Europe (Stockholm)

## Compatible Clients

Works with popular MCP clients including:
- Kiro
- Cursor
- Claude Code
- Amazon Q CLI

## Protocol Support

Supported MCP protocol versions:
- 2025-06-18
- 2025-03-26

## Integration

Gateway immediately calls the MCP server's tools/list capability to fetch available tools and make them available in the unified catalog without requiring separate user action. Manual tool catalog refresh can be triggered by calling the SynchronizeGatewayTargets API.

## Use Cases

- Production-ready AI agent deployment
- Enterprise agent lifecycle management
- Long-running agent workflows
- Interactive agent operations with user input
- Real-time agent progress monitoring

## Pricing

Part of Amazon Bedrock AgentCore service. Pricing based on agent runtime and resource usage.