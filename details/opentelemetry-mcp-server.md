# opentelemetry-mcp-server

**Category:** Monitoring  
**Brand:** traceloop  
**Source:** https://github.com/traceloop/opentelemetry-mcp-server

## Description
opentelemetry-mcp-server is an open source Model Context Protocol (MCP) server that connects large language models (LLMs) to OpenTelemetry backends. It allows AI agents to query distributed traces and telemetry data from systems such as Jaeger, Tempo, Traceloop, Datadog, Grafana, Dynatrace, and other OpenTelemetry-compatible platforms to support automated debugging and observability analysis.

## Features
- **Unified MCP server for OpenTelemetry traces**  
  - Exposes OpenTelemetry trace data via the Model Context Protocol.  
  - Provides a single interface for LLMs and AI agents to access traces across multiple observability systems.

- **Multi-backend support**  
  - Designed to query traces from various OpenTelemetry backends, including (as mentioned across descriptions):  
    - Jaeger  
    - Tempo  
    - Traceloop  
    - Datadog  
    - Grafana  
    - Dynatrace  
    - Other OpenTelemetry-compatible backends

- **AI-focused observability access**  
  - Enables LLMs and AI agents to analyze distributed traces for:  
    - Automated debugging workflows  
    - Observability insights and root-cause exploration

- **Telemetry and observability data exposure**  
  - Surfaces telemetry data (traces and related observability information) through MCP tools/resources that an LLM can call.  
  - Acts as a bridge between observability platforms and AI agents.

- **Open source**  
  - Available under the Apache-2.0 license.  
  - Source code hosted on GitHub for customization and extension.

## Technical Details
- **Ecosystem:** OpenTelemetry, observability, metrics/traces  
- **Intended usage:** Integrate into LLM/MCP-based agent environments that need direct access to trace data for debugging and monitoring.

## Pricing
- The project is open source and licensed under **Apache-2.0**.  
- No paid pricing plans are listed in the provided content.