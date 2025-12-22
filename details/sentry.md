### Sentry (MCP Server)

**Category:** MCP Server – Directories & Lists  
**Slug:** `sentry`  
**Source:** <https://github.com/madhukarkumar/anthropic-mcp-servers/blob/main/src/sentry>

#### Overview
Sentry is an MCP (Model Context Protocol) server that connects to Sentry.io to retrieve and analyze issues, enabling debugging and monitoring workflows directly from within an LLM.

#### Features
- Connects to Sentry.io as a data source for application error and performance issues
- Retrieves issues from Sentry for inspection within an LLM environment
- Supports analysis of Sentry issues to aid debugging workflows
- Supports monitoring-oriented workflows (e.g., reviewing active or recent issues) from within an LLM
- Exposes Sentry functionality via MCP so LLMs can interact with Sentry programmatically

#### Typical Use Cases
- Investigating Sentry-reported issues through natural language queries in an LLM
- Assisting with debugging by surfacing relevant Sentry issue details in context
- Monitoring the state of Sentry issues without leaving an LLM-based workspace

#### Integrations
- **Sentry.io** (error tracking and performance monitoring platform)
- **LLM tools via MCP** (usable by MCP-compatible LLM clients)

#### Pricing
Pricing details are not specified in the provided content.