## Overview

The Sentry MCP Server connects your LLM client to Sentry using the Model Context Protocol (MCP), giving your AI tools direct access to issues, errors, projects, and Seer analysis. Sentry hosts and manages a remote MCP server with OAuth authentication, so there's nothing to install.

## MCP Server Monitoring

In August 2025, Sentry announced MCP Server monitoring, giving developers the context they need across every layer to find bugs anywhere in their application stack. Gartner predicts that by 2026, 75% of API gateway vendors and 50% of iPaaS vendors will have MCP features.

## Key Features

### Error Monitoring

The Anthropic MCP SDK handles errors by returning a JSON-RPC response instead of throwing. Sentry captures these errors and links them to the specific tool, resource, or prompt that caused them, preventing silent failures.

### Performance Tracking

The Tools tab shows:
- Most Used Tools widget
- Slowest Tools analysis
- Most Failing Tools tracking
- Per-tool metrics: request count, error rate, average duration, and P95 latency

### AI Integration - Mission Control

Sentry Mission Control Integration enables Continuous AI for error monitoring:
- AI agents autonomously detect, analyze, and fix production errors
- Automatic issue analysis when Sentry detects problems
- Auto-generated fixes and pull requests
- Solution validation without manual intervention

## Implementation

Wrap your McpServer instance with `Sentry.wrapMcpServerWithSentry()`. This single wrapper automatically instruments:
- All tool calls
- Resource reads
- Prompt retrievals

## Use Cases

- Debug production errors without leaving your editor
- Automated error analysis with AI assistants
- Real-time alerting for MCP server failures
- Performance optimization for MCP tools
- Continuous AI-powered error resolution

## Integration Capabilities

- Direct access to Sentry issues and errors
- Project and organization management
- Seer AI analysis integration
- Source code context
- Stack trace analysis
- Error grouping and trends

## Compatible Clients

- Claude Desktop and Claude Code
- Cursor IDE
- Continue extension
- VS Code with MCP support
- Any MCP-compatible client

## Security Features

- OAuth authentication
- Hosted and managed by Sentry
- No local server installation required
- Secure API access
- Enterprise-grade security

## Current Status (2026)

The Sentry MCP Server is in production, though MCP is still a developing technology and changes should be expected. Active development continues with refinements and new features being added regularly.

## Benefits

- Zero infrastructure setup
- Automatic error instrumentation
- Real-time performance metrics
- AI-powered error resolution
- Seamless IDE integration
- Production-ready monitoring

## Pricing

Part of Sentry platform. Pricing based on Sentry subscription plan and usage.