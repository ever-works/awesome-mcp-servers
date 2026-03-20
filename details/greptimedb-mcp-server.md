## Overview

The GreptimeDB MCP Server is a Model Context Protocol implementation for GreptimeDB — an open-source observability database that handles metrics, logs, and traces in one engine. It enables AI assistants to query and analyze GreptimeDB using SQL, TQL (PromQL-compatible), and RANGE queries, with built-in security features like read-only enforcement and data masking.

## Features

- **SQL Queries**: Execute SQL queries with format options (csv/json/markdown)
- **TQL (PromQL-compatible)**: Execute time-series queries for metrics analysis
- **Built-in Templates**: Common tasks including metrics_analysis, IoT monitoring, and trace analysis
- **Security**: Read-only enforcement, sensitive data masking, and audit logging
- **Connection Pooling**: Efficient database connection management
- **Multi-Protocol Support**: MySQL protocol integration

## Use Cases

- Real-time AIOps and observability monitoring
- IoT analytics and sensor data analysis
- Financial data monitoring and time-series analysis
- Application performance monitoring (APM)
- Log aggregation and analysis

## Installation

Install via pip:
```bash
pip install greptimedb-mcp-server
```

Run with:
```bash
greptimedb-mcp-server --host localhost --database public
```

## Configuration

- Database host and MySQL protocol port (default: 4002)
- Database user, password, and name
- Timezone settings
- HTTP API port for pipeline management
- Connection pool size
- Options for sensitive data masking and audit logging

## Pricing

Free and open-source.