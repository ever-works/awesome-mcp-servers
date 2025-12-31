# davinci-resolve-mcp

**Category:** media-processing-mcp-servers  
**Brand:** Blackmagic Design  
**Repository:** https://github.com/samuelgursky/davinci-resolve-mcp  
**License:** MIT

An MCP (Model Context Protocol) server that integrates with DaVinci Resolve to automate video editing, color grading, and media management through natural language instructions.

## Features

- **MCP server for DaVinci Resolve**
  - Exposes DaVinci Resolve functionality via the Model Context Protocol.
  - Designed to be used by LLM-based agents and tools.

- **Natural language control**
  - Accepts high-level, natural language instructions to drive Resolve operations.
  - Automates common workflows without manual UI interaction.

- **Video editing automation**
  - Automates editing-related tasks within DaVinci Resolve (e.g., timeline operations, clip handling, basic edit actions).

- **Color grading automation**
  - Integrates with Resolve’s color tools to perform grading operations driven by natural language.

- **Media management**
  - Supports media organization tasks such as importing, organizing, and managing media assets from within Resolve.

- **Configurable project environment**
  - Uses configuration files (under `config/`) to adjust behavior and connection details.

- **Examples and documentation**
  - `examples/` folder with sample usage patterns and prompts.
  - `docs/` folder with additional setup and usage documentation.

- **Logging and diagnostics**
  - `logs/` directory for recording server activity and troubleshooting.

- **Scriptable workflows**
  - `scripts/` directory with helper scripts to install, run, or manage the MCP server.

- **Tested implementation**
  - `tests/` directory for automated tests to verify functionality and stability.

- **Extensible source structure**
  - `src/` directory with modular codebase allowing extension or customization of supported Resolve operations.

## Technical Details

- **Tech stack:** MCP server (language/framework details not explicitly listed in provided content).
- **Integration target:** DaVinci Resolve desktop application.
- **Usage context:** AI/LLM tools that support MCP (e.g., agent frameworks, dev environments).

## Pricing

- Open-source under the MIT license; no pricing plans are listed in the provided content.