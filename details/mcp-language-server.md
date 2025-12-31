# mcp-language-server

**Category:** Development Tools – MCP Servers  
**Repository:** https://github.com/isaacphi/mcp-language-server  
**License:** BSD-3-Clause

## Overview
mcp-language-server is an MCP server that exposes language-server-like, semantic code navigation and analysis capabilities to MCP-enabled clients. It helps tools understand and work with codebases by providing core language-intelligence operations over the MCP protocol.

## Features
- **Semantic code navigation**  
  - Go to / get definition  
  - Find references
- **Codebase refactoring support**  
  - Rename symbols via semantic analysis
- **Diagnostics**  
  - Surface diagnostics from the underlying language server(s) through MCP
- **Language-server-like capabilities over MCP**  
  - Bridges MCP-enabled clients to LSP-style functionality  
  - Designed to help clients navigate and understand codebases semantically

*(Additional implementation details, supported languages, and configuration options are available in the project’s README and source code.)*

## Pricing
- **Open Source**: Available free of charge under the BSD-3-Clause license.