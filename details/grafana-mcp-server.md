## Overview

The official Grafana MCP Server enables AI agents to interact with your entire observability stack through the Model Context Protocol. It provides comprehensive support for dashboards, datasource queries, alerting, incident management, and more.

## Features

### Dashboard Management
- Query and manipulate Grafana dashboards
- Create and update dashboard panels
- Export and import dashboard configurations
- Dashboard templating and variables

### Datasource Integration
- **Prometheus**: Query metrics, metadata, and calculate histogram percentiles (p50, p90, p95, p99)
- **Loki**: Run log queries and metric queries using LogQL
- **Pyroscope**: Query performance profiling data
- **Multi-datasource support**: Query multiple datasources simultaneously

### Alerting & Incident Management
- Manage alert rules and notification channels
- Query alert state and history
- **Grafana OnCall**: Incident management and on-call scheduling
- Alert annotation and silencing

### Sift Investigations
- Interactive incident investigation workflows
- Correlation of metrics, logs, and traces
- Root cause analysis assistance

### Metrics & Monitoring
- Prometheus metrics exposure with `--metrics` flag (SSE/HTTP only)
- Track MCP operation duration with labels for method, tool, error type, transport, and protocol version
- Self-monitoring capabilities

## Use Cases

- Automated dashboard creation and updates
- Intelligent alert management and response
- Log analysis and troubleshooting
- Performance profiling and optimization
- Incident investigation and root cause analysis
- SLO monitoring and reporting
- Custom observability workflows

## Technical Implementation

Built and maintained by Grafana Labs, ensuring tight integration with Grafana's APIs and features. Supports SSE and streamable HTTP transports with optional Prometheus metrics exposition.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Supports Grafana Cloud and self-hosted Grafana instances with API key authentication.