# gin-mcp

## Overview
`gin-mcp` is a zero-configuration Go library and MCP server that automatically exposes existing [Gin](https://github.com/gin-gonic/gin) web framework APIs as MCP tools. It allows Gin-based services to be used directly via the Model Context Protocol (MCP) with minimal code changes.

- **Category:** API Integration / MCP Servers
- **Technology:** Go, Gin, MCP
- **Source:** https://github.com/ckanthony/gin-mcp

## Features
- **Zero-configuration bridge**
  - Automatically exposes existing Gin routes as MCP tools without requiring custom wiring for each endpoint.
  - Designed to be enabled with as little as a single line of code in an existing Gin application.

- **MCP server implementation**
  - Runs as an MCP server compatible with MCP clients (e.g., MCP-enabled LLM tools / dev environments).
  - Treats Gin HTTP handlers as MCP tools, allowing LLMs or MCP clients to call your API operations.

- **Gin integration**
  - Built specifically for the Gin web framework.
  - Uses the Gin routing and handler ecosystem; you keep your existing Gin-based HTTP API and add MCP support on top.

- **Automatic tool exposure**
  - Discovers and exposes Gin routes as MCP tools.
  - Minimizes boilerplate and avoids manual tool definition duplication.

- **Go library**
  - Distributed as a Go module importable into any Go project using Gin.
  - Can be embedded alongside your existing server code.

- **Example implementation**
  - Includes a `examples/simple` directory in the repository to demonstrate basic integration.

- **Testing and CI**
  - Has automated tests (`server_test.go`).
  - CI workflow configuration in `.github/workflows` and code coverage reporting via Codecov.

## Pricing
- The project is open source (LICENSE file included in the repository). No pricing plans are listed; usage is free under the terms of its open-source license.

## License
- An open-source license is included in the repository (`LICENSE`). Refer to that file in the GitHub repository for full terms.