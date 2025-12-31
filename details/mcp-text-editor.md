## mcp-text-editor

**Category:** Code Execution & Automation MCP Servers  
**Tags:** file-editing, code-execution, development  
**Source:** https://github.com/tumf/mcp-text-editor  
**License:** MIT

### Overview
mcp-text-editor is a line-oriented text file editor exposed as a Model Context Protocol (MCP) server. It is designed for use by LLM-based tools, providing efficient partial file access so large files can be read and modified with reduced token usage.

### Features
- **MCP server integration**
  - Exposes text-editing capabilities over the Model Context Protocol for use by AI agents and tooling.
- **Line-oriented text editing**
  - Operates on text files in a line-based manner, suitable for code and structured text editing.
- **Efficient partial file access**
  - Supports reading and modifying only relevant file sections, reducing the amount of text that needs to be transferred or processed.
  - Optimized specifically to minimize token usage for LLM interactions.
- **File editing operations**
  - Designed as a general-purpose text file editor for programmatic use (e.g., insert, update, and modify lines in files).
- **Developer-focused design**
  - Intended for integration into development workflows and LLM-based development assistants.

### Pricing
- Not specified (open-source project under the MIT license).