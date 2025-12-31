# FHIR MCP Server

- **Name:** FHIR MCP Server
- **Brand:** WSO2
- **Category:** Data Access & Integration – MCP Servers
- **Repository:** https://github.com/wso2/fhir-mcp-server
- **License:** Apache-2.0

## Description
FHIR MCP Server is a Model Context Protocol (MCP) server implementation by WSO2 that exposes Fast Healthcare Interoperability Resources (FHIR) APIs via MCP. It allows MCP-compatible clients (such as MCP-enabled applications or agents) to query and interact with clinical data hosted in FHIR-compliant systems or existing FHIR servers.

## Features
- **MCP server for FHIR**
  - Implements the Model Context Protocol so FHIR resources can be accessed through MCP-compatible clients.
- **FHIR API exposure**
  - Exposes any existing FHIR server or FHIR API as an MCP server endpoint.
- **Interoperability with FHIR-compliant systems**
  - Designed to work with FHIR-compliant backends, enabling standardized access to clinical and healthcare data.
- **Containerization support**
  - Includes a `Dockerfile` and `docker-compose.yml` for container-based deployment.
- **Configuration via environment variables**
  - Provides an `.env.example` file to configure runtime parameters (e.g., endpoints, credentials) for different environments.
- **Python-based implementation**
  - Uses a Python project structure (`src/fhir_mcp_server`, `.python-version`) suitable for Python tooling and dependency management.
- **Documentation and examples**
  - `docs` directory and tests to illustrate usage patterns and validate behavior.
- **CI / GitHub workflows support**
  - `.github` directory indicates integration points for automation (e.g., CI/CD) within GitHub.

## Technical Details
- **Protocol:** Model Context Protocol (MCP)
- **Domain:** Healthcare interoperability, FHIR APIs, clinical data access
- **Runtime:** Python (version specified via `.python-version` in the repo)
- **Deployment:** Docker / Docker Compose

## Pricing
- **Open Source:** Distributed under the Apache-2.0 license. No pricing tiers are specified; usage is governed by the open-source license terms.