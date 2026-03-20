## Overview

The Strands Agents MCP server provides documentation about Strands Agents to your GenAI tools, enabling you to use your favorite AI coding assistant to build Strands Agents applications. Strands Agents is a model-driven approach to building AI agents that handles long-running tasks, persistent state, and complex orchestration.

## Long-Running Task Strategies

Strands Agents MCP integration introduces two main approaches for handling tasks that exceed typical session timeframes:

### 1. Context Messaging Approach

Maintains continuous communication between the MCP server and client throughout task execution:

- Uses MCP's built-in context object to send periodic notifications
- Optimal for tasks completed within 10–15 minutes
- Requires stable network connectivity
- Real-time progress updates

### 2. Async Task Management Approach

Separates task initiation from execution and result retrieval:

- Tool immediately returns a task initiation message
- Task executes in the background
- Excels in enterprise scenarios where tasks might run for hours
- Users can disconnect and reconnect
- Maximum reliability for critical operations

## Integration with Amazon Bedrock AgentCore

Amazon Bedrock AgentCore supports:

- Long-running tasks (up to 8 hours)
- Asynchronous tool execution
- Tool interoperability using MCP, A2A, or API Gateway based services
- Persistent state management for seamless cross-session task execution

## Compatible AI Tools

Works with 40+ applications that support MCP servers, including:

- Amazon Q Developer CLI
- Anthropic Claude Code
- Cline
- Cursor

## Key Features

- **Model-Driven Approach**: Build AI agents in just a few lines of code
- **Persistent Memory**: Maintain context across sessions
- **Observability**: Built-in tracing and monitoring
- **Production-Ready**: Enterprise-grade reliability
- **Agent Architectures**: Support for various agent patterns

## Use Cases

- Machine learning model training agents
- Large dataset processing workflows
- Extended simulation agents
- Enterprise automation with reliability requirements
- Multi-step workflows spanning hours

## Technical Requirements

- Compatible MCP client
- AWS account for production deployment
- Python or TypeScript SDK

## Pricing

Open-source framework. AWS infrastructure costs may apply for production deployment.