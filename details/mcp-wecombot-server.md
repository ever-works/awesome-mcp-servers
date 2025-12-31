# mcp-wecombot-server

**Category:** Messaging MCP Servers  
**Tags:** messaging, WeCom, notifications  
**Source:** https://github.com/gotoolkits/mcp-wecombot-server

An MCP server application that integrates with WeCom group robots to send different types of messages as part of MCP-based workflows.

## Features

- **WeCom group robot integration**
  - Connects to WeCom group robots to automate notifications and messaging.

- **Multiple message types**
  - Send text messages to WeCom groups.
  - Send markdown-formatted messages to WeCom groups.
  - Send image messages to WeCom groups.
  - Send “news” type messages (WeCom news/card-style content).

- **MCP server implementation**
  - Exposed as an MCP server to plug into MCP-compatible tools and workflows.

- **Configurable behavior**
  - Uses a `config.json` file for configuration (e.g., endpoints/keys and other runtime settings).

- **Deployment & tooling**
  - Includes a `Dockerfile` for containerized deployment.
  - Includes a `Makefile` for common build and run tasks.
  - Provides `smithery.yaml` for installation and usage via Smithery.

- **Testing & code structure**
  - Contains dedicated WeCom integration logic (`wecom.go`).
  - Includes tests for WeCom-related functionality (`wecom_test.go`).

## Installation

- **Via Smithery**
  - Can be installed for Claude Desktop automatically using Smithery:
    - Smithery server entry: `@gotoolkits/mcp-wecombot-server`.

- **Manual installation**
  - Repository includes Go modules (`go.mod`, `go.sum`) and `main.go` for building and running the server directly.

## Usage

- Send a text message to a WeCom group.
- Send a markdown message to a WeCom group.
- Send an image message to a WeCom group.
- Send a news-type message to a WeCom group.

## Pricing

- Not specified in the provided content. The project appears to be open-source (LICENSE file present), but no explicit pricing details are given.