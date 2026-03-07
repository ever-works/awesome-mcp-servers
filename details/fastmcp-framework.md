## Overview

FastMCP is the fast, Pythonic way to build MCP servers, clients, and applications, and is the standard framework for building MCP applications. The Model Context Protocol (MCP) connects LLMs to tools and data.

## Key Features

- **Decorator-Based API**: Transform regular Python functions into MCP-compatible tools
- **Server Framework**: Wrap Python functions into MCP-compliant tools, resources, and prompts
- **Client Support**: Connect to any server with full protocol support
- **Interactive Apps**: Give tools interactive UIs rendered directly in the conversation
- **Built-in Debugging**: MCP Inspector tool for browser-based debugging

## Simple Example

Build an MCP server by:
1. Installing the framework
2. Decorating functions with @mcp.tool
3. Creating a minimal MCP server that exposes functions to AI assistants

The decorator handles all protocol details automatically.

## History and Adoption

- **FastMCP 1.0**: Incorporated into the official MCP Python SDK in 2024
- **Current Adoption**: Downloaded a million times a day
- **Market Share**: Some version of FastMCP powers 70% of MCP servers across all languages

## Installation

Can be installed using:
- pip install fastmcp
- poetry add fastmcp

Both package managers work well for FastMCP projects.

## Resources

- **Documentation**: Complete documentation at gofastmcp.com
- **Guides**: Detailed guides, API references, and advanced patterns
- **Debugging**: Built-in MCP Inspector starts the server and opens Inspector in browser
- **GitHub**: github.com/jlowin/fastmcp

## Use Cases

- Rapid MCP server development in Python
- Converting existing Python functions to MCP tools
- Building custom AI integrations
- Creating data access layers for LLMs
- Prototyping MCP applications

## PyPI

Available at pypi.org/project/fastmcp/