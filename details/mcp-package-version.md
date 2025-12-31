# mcp-package-version

**Category:** Development Tools – MCP Servers  
**Brand:** sammcj  
**License:** MIT  
**Repository:** https://github.com/sammcj/mcp-package-version

## Description
mcp-package-version is a Model Context Protocol (MCP) server that helps language models look up and suggest the latest stable versions of software packages while writing or refactoring code.

It is designed to be integrated into LLM-driven development workflows so that generated code can depend on current, stable package releases instead of outdated or manually specified versions.

## Features
- **Latest stable version lookup** – Provides up-to-date, stable package version information for use in code generation and refactoring.
- **LLM-focused design** – Exposes functionality in a way intended for use by Large Language Models via the MCP standard.
- **MCP server implementation** – Runs as an MCP-compliant server that can be connected to compatible LLM tooling and IDE integrations.
- **Repository assets**
  - `Dockerfile` for containerized deployment.
  - `tests` directory for automated testing of functionality.
  - `internal` and `pkg` directories for modular server internals and reusable components.
  - `CHANGELOG.md` for documented changes across versions.
  - `CODE_OF_CONDUCT.md` and `.github` configuration for project governance and automation.

*(Note: The upstream content provided here does not expose language/ecosystem-specific details or API endpoints; only general capabilities can be listed.)*

## Use Cases
- Automatically inserting the latest stable package versions into dependency files (e.g., when generating configuration or lock files via an LLM).
- Updating version constraints during code refactoring suggested by an LLM.
- Ensuring generated snippets and templates rely on current stable libraries.

## Pricing
- Not specified in the provided content.  
- The project is open source under the MIT license; no commercial plans are described in the available information.