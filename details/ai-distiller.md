# ai-distiller

**Category:** repository-code-analysis-mcp-servers  
**Tags:** code-analysis, ai-assistant, documentation  
**Source:** https://github.com/janreges/ai-distiller  
**License:** MIT

## Description
ai-distiller is an open-source tool that analyzes large codebases and extracts only the essential public APIs, types, and structural information into a compact, AI-digestible format. It is commonly used as an MCP-accessible utility so AI agents can more effectively understand and work with complex repositories.

## Features
- Extracts essential public APIs, types, and structural information from large codebases
- Produces highly compressed, AI-friendly context (approximately 90–98% code size reduction)
- Designed for fast processing on large repositories
- Open-source, licensed under MIT
- Usable as a command-line (CLI) tool
- MCP integration for use as an MCP server in AI workflows
- Intended for AI assistants/agents to better navigate and reason about code
- Supports 12+ programming languages (multi-language code analysis)
- Suitable for generating distilled documentation-like views of a project’s structure
- Can be integrated into AI prompt workflows to reduce context size and cost while maintaining essential information

## Integrations & Interfaces
- **CLI:** Direct command-line usage for local or CI workflows
- **MCP (Model Context Protocol):** Accessible as an MCP server, enabling AI tools/agents to query distilled repository structure

## Use Cases
- Preparing large repositories for efficient AI-assisted code understanding and navigation
- Reducing context size and token costs when sending code information to LLMs
- Generating concise representations of public APIs and types for documentation or review

## Pricing
ai-distiller is open-source under the MIT license and can be used at no monetary cost. There are no stated paid plans in the provided content.