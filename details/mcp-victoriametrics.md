# mcp-victoriametrics

**Category:** Monitoring  
**Brand:** VictoriaMetrics  
**Type:** Open‑source MCP server / integration

An open-source Model Context Protocol (MCP) server that integrates VictoriaMetrics with LLM-based tools, exposing VictoriaMetrics APIs and documentation so LLMs can query metrics, assist with monitoring, and help troubleshoot systems backed by VictoriaMetrics.

## Features

- **Model Context Protocol (MCP) server implementation**  
  - Implements an MCP-compliant server specifically for VictoriaMetrics.  
  - Designed to be consumed by MCP-compatible LLM clients and tools.

- **VictoriaMetrics integration**  
  - Connects directly to VictoriaMetrics instances.  
  - Exposes VictoriaMetrics APIs for querying and working with time‑series metrics.  
  - Oriented around observability use cases such as metrics exploration, monitoring, and troubleshooting.

- **Metrics querying via LLMs**  
  - Enables LLMs to formulate and run queries against VictoriaMetrics metrics.  
  - Intended to support interactive analysis and question‑answering workflows over observability data.

- **Monitoring and troubleshooting workflows**  
  - Provides access to metrics data suitable for diagnosing performance and reliability issues.  
  - Targets scenarios like incident analysis, metric-based investigation, and historical trend inspection.

- **Documentation exposure**  
  - Surfaces VictoriaMetrics documentation to LLM clients so they can reason about metric semantics and API usage.

- **Deployment resources**  
  - `cmd/mcp-victoriametrics` command directory for building/running the MCP server.  
  - `k8s/helm` charts for Kubernetes deployment and configuration.  
  - `scripts` directory for auxiliary automation (e.g., building, running, or integration helpers).  
  - `dashboard` assets likely related to visual dashboards for monitoring the MCP server and/or VictoriaMetrics.

- **Vendor dependencies**  
  - `vendor` directory with vendored Go dependencies for reproducible builds.

- **Open-source licensing**  
  - Released under the Apache-2.0 license.

## Pricing

- No pricing information is provided in the available content. The project appears to be open source under the Apache-2.0 license.