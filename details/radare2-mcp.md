# radare2-mcp

**Category:** Testing & Debugging Tools  
**Tags:** reverse-engineering, binary-analysis, development

An MCP (Model Context Protocol) stdio server that integrates the Radare2 disassembler with AI agents, enabling automated disassembly and binary inspection for reverse engineering workflows.

---

## Key Details
- **Repository:** https://github.com/radareorg/radare2-mcp  
- **License:** MIT  
- **Technology:** Radare2-based MCP server, stdio-based protocol

---

## Features
- **MCP stdio server for Radare2**  
  - Exposes Radare2 functionality over a standard-input/standard-output (stdio) MCP server.
  - Designed for integration with AI agents and tools that support the Model Context Protocol.

- **Disassembly and inspection tooling**  
  - Provides programmatic access to Radare2’s disassembler capabilities.  
  - Allows AI agents to inspect binaries for reverse engineering tasks (e.g., code exploration, structure analysis).

- **AI-focused integration**  
  - Tailored to allow LLM-based or other AI agents to drive Radare2 through MCP tools.  
  - Suitable for building automated reverse engineering assistants or analysis pipelines.

- **Repository structure**  
  - `src/`, `svc/`, and `dist/` directories containing the MCP server implementation and build artifacts.  
  - `AGENTS.md` describing how agents can interact with the server/tools.  
  - `INSTALL.md` documenting installation and setup steps.  
  - `Makefile` and `autogen.sh` for building from source.

- **Planned / in-progress work**  
  - `TODO.md` lists future enhancements and outstanding tasks for the project (e.g., additional tools, protocol extensions, or improved workflows).

---

## Use Cases
- Automating reverse engineering tasks via AI agents.  
- Integrating Radare2-based binary analysis into LLM-powered tooling.  
- Building custom development or security analysis workflows that require scripted disassembly and inspection.

---

## Pricing
- **Open Source** – Available under the MIT license; no pricing plans listed.
