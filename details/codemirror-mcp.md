## codemirror-mcp

### Description
codemirror-mcp is a CodeMirror extension by **marimo** that implements the [Model Context Protocol (MCP)](https://modelcontextprotocol.io) inside the editor, enabling resource mentions and prompt-style commands directly in CodeMirror.

---

### Features
- **Model Context Protocol integration**
  - Hooks a Model Context Provider (MCP) into a CodeMirror editor instance.
- **Resource mentions**
  - `@resource` syntax for referencing MCP resources.
  - `@resource-uri` syntax for specifying resource URIs.
- **Prompt commands**
  - `/prompt` command syntax for invoking prompt-style interactions.
  - `/command` syntax for command-style operations within the editor.

---

### Installation & Requirements
- Distributed as a JavaScript/TypeScript package (via `package.json`).
- **Peer dependencies:**
  - `@codemirror/view`
  - `@codemirror/state`
  - `@modelcontextprotocol/sdk`

---

### Pricing
- **Free and open-source**
  - Licensed under the **MIT License**.

---

### Links
- **Source code:** https://github.com/marimo-team/codemirror-mcp