## Overview

The Prometheus MCP Server is a Go-based Model Context Protocol implementation deployed in-cluster to provide AI assistants with authenticated, multi-tenant access to Prometheus and Mimir metrics infrastructure. It exposes 18 read-only tools that wrap the Prometheus HTTP API.

## Features

### Query Capabilities
- **Instant Queries**: Execute PromQL queries for instant metric values
- **Range Queries**: Query metrics over time ranges
- **Series Queries**: Discover time series by label matchers

### Metadata & Discovery
- **Metric Discovery**: List available metrics and their metadata
- **Label Discovery**: Query label names and values
- **Target Information**: Access scrape target details
- **Service Discovery**: View service discovery configuration

### System Information
- **TSDB Stats**: Time series database statistics
- **Runtime Info**: Prometheus runtime and configuration details
- **Build Info**: Version and build information

### Alerting
- **Alert Rules**: Query active and pending alert rules
- **Alert State**: Monitor alert firing status

### Advanced Features
- **Exemplars**: Query exemplar data for distributed tracing correlation
- **Multi-tenancy**: Support for multi-tenant Prometheus and Mimir deployments
- **Authentication**: In-cluster authentication for secure access
- **Read-only**: All operations are non-destructive

## Use Cases

- Metrics exploration and analysis
- Alert investigation and troubleshooting
- Capacity planning and forecasting
- Performance analysis
- SLI/SLO monitoring
- Custom metrics dashboards
- Documentation generation

## Technical Implementation

Built with Go for high performance and deployed directly in Kubernetes clusters. Supports both Prometheus and Mimir backends with automatic multi-tenancy support.

## Integration

Designed for in-cluster deployment alongside Prometheus or Mimir. Compatible with MCP clients through authenticated endpoints. Supports Kubernetes RBAC for access control.