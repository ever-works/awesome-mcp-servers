# mcp-server-wazuh

**Category:** Security Attestation MCP Servers  
**Brand:** wazuh  
**License:** MIT  
**Repository:** https://github.com/gbrigandi/mcp-server-wazuh

## Overview
mcp-server-wazuh is a Rust-based Model Context Protocol (MCP) server that integrates the Wazuh SIEM platform with AI assistants. It exposes real-time security alerts and event data from Wazuh so that AI tools can perform automated analysis and reasoning over SIEM telemetry.

## Features
- **Rust-based MCP implementation** for performance and reliability.
- **Integration with Wazuh SIEM** to access security alerts and event data.
- **Real-time data exposure** of Wazuh alerts/events to AI assistants.
- **MCP server interface** to make Wazuh data consumable by compatible AI tools.
- **Configuration via environment file** (example provided in `.env.example`).
- **Docker support** with a `Dockerfile` and `docker` directory for containerized deployment.
- **Test suite** under `tests` directory for validating functionality.
- **Media assets** under `media` (e.g., for documentation/diagrams).
- **GitHub Actions workflows** under `.github/workflows` for CI-related automation.

## Technical Details
- Implemented in Rust (managed via `Cargo.toml`).
- Ships with example configuration and ignore rules (`.env.example`, `.gitignore`).
- Distributed as open source under the MIT license.

## Pricing
- Not applicable. This is an open-source project released under the MIT license; no pricing information is provided.