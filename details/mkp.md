# MKP

**Category:** Cloud & DevOps · MCP Servers  
**Website/Source:** https://github.com/StacklokLabs/mkp  
**Vendor/Brand:** StacklokLabs

## Overview

MKP is a Model Context Protocol (MCP) server for Kubernetes. It enables LLM‑powered applications and AI assistants to interact with and manage Kubernetes clusters through a standardized MCP interface.

## Features

- **MCP server for Kubernetes**
  - Implements the Model Context Protocol to expose Kubernetes operations to LLMs and MCP‑compatible clients.
- **LLM integration**
  - Designed for use by LLM‑powered applications and AI assistants, enabling them to query and operate on Kubernetes clusters programmatically.
- **Cluster interaction and management**
  - Provides tools for interacting with Kubernetes clusters (e.g., listing and inspecting cluster resources; additional operations are available in the server but not fully visible in the provided content).
- **Kubernetes‑native**
  - Built specifically for Kubernetes environments, fitting into cloud‑native and DevOps workflows.
- **Open source**
  - Source code available on GitHub, with standard project files such as LICENSE, CONTRIBUTING, CODE_OF_CONDUCT, and CI/workflow configuration.

## Technology & Implementation

- **Language:** Go (Go modules present: `go.mod`, `go.sum`).
- **Server implementation:** Located under `cmd/server`.
- **Reusable packages:** Core logic under `pkg/`.
- **Automation/CI:** GitHub Actions workflows under `.github/workflows`; `Taskfile.yml` for task automation.

## Pricing

- Not specified in the provided content. The project appears to be an open‑source GitHub repository; no pricing plans are listed.