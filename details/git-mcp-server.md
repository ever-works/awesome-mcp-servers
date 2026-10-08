# Overview

The Git MCP server is an MCP (Model Context Protocol) server that provides Git version control capabilities to AI agents. It offers 28 tools, 1 resource, and 1 prompt, accessible via STDIO and Streamable HTTP transports. The server runs on both Bun and Node.js (auto-detected).

## Features

- 28 Git tools organized into 7 categories: Repository Management, Staging & Commits, History & Inspection, Analysis, Branching & Merging, Remote Operations, Advanced Workflows
- Declarative tool definitions with automatic registration, validation, and execution
- Unified McpError system for consistent error handling
- Pluggable authentication (none, JWT, OAuth)
- Pluggable storage backends (in-memory, filesystem, Supabase, Cloudflare KV/R2)
- Observability with structured logging (Pino) and optional OpenTelemetry integration
- Dependency injection via tsyringe for decoupled architecture
- Cross-runtime support (auto-detects Bun or Node.js)
- Pluggable git provider architecture (current: CLI, planned: isomorphic-git for edge deployment)
- Working directory management for multi-repo workflows
- Configurable Git identity via environment variables
- Commit signing (GPG/SSH) with fallback to unsigned
- Safety measures: path validation, GIT_BASE_DIR restriction, no shell interpolation, explicit confirmation for destructive operations
- Security: JWT/OAuth support, optional rate limiting, comprehensive logging

## Pricing

Free and open-source under the Apache 2.0 license.