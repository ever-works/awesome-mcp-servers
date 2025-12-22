# kintone MCP Server

## Overview

kintone MCP Server is an open‑source Model Context Protocol (MCP) server that connects LLMs to the kintone platform. It lets AI tools (such as Claude Desktop) explore and manipulate kintone app data, enabling low‑code style business data operations through MCP tools.

> Note: The project is now feature‑frozen. The maintainer recommends using and contributing to the official kintone MCP server. This repository will receive maintenance updates until the official server reaches sufficient functionality.

## Features

- **MCP-compliant server for kintone**  
  - Implements a Model Context Protocol server dedicated to kintone.  
  - Allows LLMs to interact with kintone via standard MCP tools.

- **kintone data exploration and manipulation**  
  - Browse and work with kintone app data through AI interfaces.  
  - Supports operations on business records and apps (as exposed via the MCP tools defined in the server).

- **Integration with AI tools**  
  - Designed to work with MCP-capable clients such as Claude Desktop.  
  - Lets LLMs call tools to manage kintone data instead of using the REST API directly.

- **Low-code style data operations**  
  - Enables non‑traditional developers (via LLMs) to perform structured operations on kintone records and apps.  
  - Useful for automating or delegating routine business data tasks to an AI assistant.

- **Predefined MCP tools configuration**  
  - `tools_list.json` defines the available MCP tools and their behavior for interacting with kintone.  
  - Centralized configuration of tool capabilities that clients can discover.

- **Containerized deployment**  
  - Includes a `Dockerfile` for building and running the MCP server in Docker.  
  - Suitable for container-based or cloud-native setups.

- **Go-based implementation**  
  - Implemented in Go (`main.go`, `go.mod`, `go.sum`).  
  - Can be built as a standalone binary for different platforms.

- **Release automation**  
  - `.goreleaser.yml` for automated builds and releases.  
  - GitHub Actions workflows under `.github/workflows` for CI/CD.

- **Smithery integration config**  
  - `smithery.yaml` provided for integrating with Smithery or related MCP hosting tooling.

- **Multilingual documentation**  
  - English README (`README.md`).  
  - Japanese README (`README.ja.md`) for Japanese-speaking users.

## Pricing

- **Cost**: Open-source and free to use.  
- **License**: See the `LICENSE` file in the repository for full licensing terms.

## Links

- **Source code & documentation**: https://github.com/macrat/mcp-server-kintone