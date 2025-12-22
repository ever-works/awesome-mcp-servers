## Neovim MCP Server

### Overview
Neovim MCP Server is an open-source Model Context Protocol (MCP) server that connects a running Neovim instance to Claude Desktop or any other MCP-compatible client. It uses the official `neovim/node-client` JavaScript library to expose your current Neovim session to LLMs for editor-aware operations like code editing and navigation.

- **Name:** Neovim MCP Server  
- **Brand:** neovim  
- **Category:** mcp-server-directories-lists  
- **Source:** [GitHub Repository](https://github.com/bigcodegen/mcp-neovim-server)

### Features
- **MCP Integration**
  - Implements a full MCP server for Neovim.
  - Compatible with Claude Desktop and other MCP clients.
  - Exposes Neovim state and operations as MCP resources and tools.

- **Neovim Session Connectivity**
  - Connects to an existing Neovim instance via a listening socket:  
    - Example: `--listen /tmp/nvim`
  - Leverages Neovim’s native text-editing commands and workflows that LLMs can operate through.

- **Exposed Resources**
  - `nvim://session` – access information about the current Neovim session.  
  - `nvim://buffers` – access and work with open buffers.

- **Core Tools & Editing Capabilities**
  - Work with files by **filename** (open/target specific buffers).
  - Execute Neovim **commands** programmatically.
  - Use `nvim.replaceTermcodes` to send key sequences in Neovim-compatible form.
  - Optional shell command execution via Neovim’s `!` commands, controlled by:
    - `ALLOW_SHELL_COMMANDS=true` (environment/setting gate).
  - Handle Neovim error messages (e.g. via `'nvim:errmsg'`).
  - Perform structured edits using:
    - `startLine`, `endLine`
    - `startColumn`, `endColumn`
    - `mode` controls editing behavior such as `"insert"`, `"replace"`, `"replaceAll"`.
  - Read/write **registers** and **marks** using fields like `register`, `mark`, `line`, and `column`.
  - Operate on raw **lines** and **content** within a buffer.

- **Enhanced Buffer Management**
  - Identify buffers via an `identifier` or by `filename`.
  - Support for disambiguating and managing multiple buffers that may share similar names.

- **Search and Replace Tools**
  - Text search within buffers using:
    - `pattern`
    - `ignoreCase`
    - `wholeWord`
  - Search-and-replace operations with control flags:
    - `pattern` and `replacement`
    - `global` (apply to all matches)
    - `ignoreCase`
    - `confirm` (prompt/confirm replacements)
  - Project or multi-file oriented search using `pattern` plus `filePattern` filters.

- **Advanced Workflow Tools**
  - Generalized `action` tools that can operate on:
    - A specific `register`
    - A given `count` (repeat actions multiple times)
    - A specific `filename`
    - Line ranges via `startLine` and `endLine`
    - A `direction` (e.g., act relative to cursor position).
  - Designed to support:
    - Navigation across buffers.
    - Performing searches and edits.
    - Recording and replaying **macros**.
    - Managing **tabs** and **folds**.
    - Automating and orchestrating typical Neovim development workflows.

- **System / Session-Oriented Tools**
  - "System tools" for inspecting and interacting with the broader Neovim environment (e.g., session-level state and configuration) needed to drive a complete development workflow.

- **Tooling Scope**
  - Provides a set of **19 MCP tools** enabling an LLM to:
    - Inspect your Neovim session.
    - Navigate and manage buffers.
    - Perform searches and structured edits.
    - Work with macros, tabs, and folds.
    - Coordinate end-to-end editing and navigation tasks from within an MCP client.

### Pricing
- **Model:** Open-source project hosted on GitHub.  
- **Paid plans:** None listed in the available content.  
- For licensing and usage terms, refer to the `LICENSE` file in the repository.

### Links
- **Source Code / Documentation:** https://github.com/bigcodegen/mcp-neovim-server
- **MCP Directory Listing:** https://glama.ai/mcp/servers/s0fywdwp87 (from project badge)