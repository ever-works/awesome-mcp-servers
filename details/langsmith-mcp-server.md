## Overview

The LangSmith MCP Server is a Model Context Protocol (MCP) server that integrates with LangSmith. It lets MCP-compatible clients (for example, AI coding assistants) read conversation history, prompts, runs and traces, datasets, experiments, and billing usage from your LangSmith workspace.

## Tracing Capabilities

### MCP Tool Call Tracing
Log every MCP tool call (with inputs and outputs) to a separate LangSmith project for monitoring and analytics. Each tool run is traced with:
- run_type="tool"
- session_id in metadata (from mcp-session-id, x-session-id, or x-request-id header)
- Generated per request for HTTP transport

### Fetching Traces
Fetch LangSmith runs (traces, tools, chains, etc.) from one or more projects with support for:
- Filters (run_type, error, is_root)
- FQL (filter, trace_filter, tree_filter)
- Ordering options

## Available Tools

- **get_thread_history**: Retrieve message history for conversations
- **list_prompts**: Fetch prompts from LangSmith with optional filtering by visibility (public/private) and limit
- **get_prompt**: Get specific prompts by name
- **fetch_runs**: Fetch LangSmith runs (traces, tools, chains, etc.) from one or more projects

## Deployment Options

### 1. Hosted Version
Available at https://langsmith-mcp-server.onrender.com/mcp
- Authentication via LANGSMITH-API-KEY header

### 2. Local Installation
Can be installed via PyPI/uvx

### 3. HTTP Server
Deployable as an HTTP server using Docker, enabling remote access via the HTTP-streamable protocol

## GitHub Repository

Available at github.com/langchain-ai/langsmith-mcp-server

## Use Cases

- Monitoring MCP tool calls and agent behavior
- Debugging AI applications with comprehensive tracing
- Analyzing conversation patterns
- Dataset and experiment management
- Billing usage tracking
- Observability for production AI systems

## Integration

Provides powerful observability integration for MCP-compatible AI applications with comprehensive support for monitoring and analyzing agent behavior.