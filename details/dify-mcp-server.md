## Overview

Dify is an open-source platform for building AI applications that combines Backend-as-a-Service and LLMOps to streamline the development of generative AI solutions. Version 1.6.0 introduces built-in two-way MCP integration that lets agents call any MCP server or become one.

## Two-Way MCP Integration

### Consume MCP Servers

Add any MCP server as tools in an Agent or as solo nodes in a Workflow:

- **In Agents**: LLM automatically selects appropriate MCP actions at runtime
- **In Workflows**: Place MCP tools exactly where needed for deterministic execution
- **Supported Servers**: Linear, Notion, Zapier (8,000+ connected apps), and any MCP-compatible service

### Publish as MCP Servers

Publish Dify Agents or Workflows as MCP servers:

- Clear server and parameter descriptions
- Any MCP-compatible client can discover and invoke
- Standard protocol compliance
- Instant AI availability across platforms

## Key Features

### Workflow Builder

- Visual canvas for building AI workflows
- Test powerful AI workflows in real-time
- Modular architecture
- Drag-and-drop interface

### LLM Orchestration

- Seamless integration with hundreds of LLMs
- Proprietary and open-source models
- Support for GPT, Mistral, Llama3
- Any OpenAI API-compatible models
- Easy model switching

### Integration Capabilities

- Access external APIs, databases, and services through standardized MCP protocols
- Eliminate integration complexity and maintenance overhead
- HTTP-based MCP services (protocol 2025-03-26)
- Pre-authorized and auth-free modes

## Platform Features

- **RAG Pipeline**: Built-in retrieval augmented generation
- **Agent Capabilities**: Autonomous agent creation
- **Model Management**: Centralized LLM management
- **Observability**: Integration with Opik, Langfuse, and Arize Phoenix
- **Backend-as-a-Service**: Complete backend infrastructure

## Use Cases

- Research pipelines with multiple agent access to MCP tools
- Technical analysis and web research
- Email and communication automation
- Incident response with integrated monitoring tools
- Cross-platform workflow orchestration
- AI-powered documentation generation

## Technical Specifications

- **Protocol Support**: MCP protocol 2025-03-26
- **Transport**: HTTP-based MCP services
- **Authentication**: Pre-authorized and auth-free modes
- **Integration**: Works with 8,000+ apps via Zapier and other MCP servers

## Development Features

- Intuitive interface for AI workflow creation
- Quick prototype to production
- Comprehensive documentation
- Community support
- Open-source codebase

## Pricing

Open-source platform with self-hosting option. Cloud hosted version available with various pricing tiers.