## Memory MCP Server (Basic Memory)

**Description**  
Basic Memory is a knowledge management MCP server that lets AI assistants (e.g., Claude) build and maintain a persistent, local knowledge base. It saves conversations and notes as Markdown files on your machine and exposes tools over the Model Context Protocol so assistants can read, write, and organize this knowledge as a semantic graph over time.

**Provider:** Basic Machines  
**Release date:** Mar 15, 2025  
**Language:** Python  
**Package:** [`basic-memory` on PyPI](https://pypi.org/project/basic-memory)  
**Code:** [GitHub repository](https://github.com/basicmachines-co/basic-memory)  
**Stats (from source):** ~80.9K downloads, ~2.2K stars

---

### Features

#### Knowledge management & storage
- Builds a **persistent knowledge base** from your interactions with Large Language Models.  
- Saves conversations and notes as **Markdown files** on your local machine.  
- Default storage directory: `~/basic-memory`.  
- Supports building a **searchable semantic knowledge graph** that grows over time.  
- AI assistants can **read from and write to** this knowledge base using MCP tools.

#### MCP integration & clients
- Implements the **Model Context Protocol (MCP)** so it can be used as a server by compatible clients.  
- Supported / documented client setups:
  - **Claude Desktop** via `claude_desktop_config.json` (`mcpServers.basic-memory`).  
  - **VS Code** via User Settings JSON (`mcp.servers.basic-memory`) or workspace `.vscode/mcp.json`.  
  - **Cursor / Claude Code** (generic MCP/CLI-based setup).  
- Can be installed and auto-configured via **Smithery** for Claude (`npx @smithery/cli install @basicmachines-co/basic-memory --client claude`).

#### Installation & CLI
- **uv-based installation (recommended):**
  - `uv tool install basic-memory` to install.  
  - Run MCP server with: `uvx basic-memory mcp`.  
- Exposes a CLI (`basic-memory`) with subcommands for sync and cloud operations.

#### Basic usage patterns
- Designed for **natural-language interaction** via your AI assistant, e.g.:
  - Create notes: “Create a note about coffee brewing methods.”  
  - Retrieve knowledge: “What do I know about pour over coffee?”  
  - Search: “Find information about Ethiopian beans.”  
- The assistant uses MCP tools behind the scenes to manage the underlying Markdown notes.

#### Synchronization (local)
- One-time local sync of the knowledge base:  
  - `basic-memory sync`  
- Real-time sync / watch mode (recommended):  
  - `basic-memory sync --watch`  
- Ensures the MCP server and file system stay consistent as content changes.

#### Cloud features (optional add-on)
If you subscribe to **Basic Memory Cloud**, additional CLI capabilities are available:
- `basic-memory cloud login` – Authenticate with the cloud service.  
- `basic-memory cloud sync` – Bidirectional synchronization between local and cloud knowledge base.  
- `basic-memory cloud check` – Verify integrity and consistency of cloud data.  
- `basic-memory cloud mount` – Mount cloud storage for direct access.

#### Multi-project support
- Can scope knowledge to specific projects using the `--project` flag when starting the MCP server, e.g.:
  - `"args": ["basic-memory", "mcp", "--project", "your-project-name"]`  
- Allows separate, project-specific knowledge bases while using the same tool.

#### Available MCP tools (Content Management)
Once configured, Claude (or another MCP client) can use these tools:
- `write_note(title, content, folder, tags)`  
  - Create new notes or update existing notes.  
  - Organize notes into folders and associate tags.
- `read_note(identifier, page, page_size)`  
  - Read notes by title or permalink.  
  - Supports pagination via `page` and `page_size`.
- `read_content(path)`  
  - Read raw file content from a specified path within the knowledge base.
- `view_note(identifier)`  
  - View notes as formatted artifacts (for display in richer UIs).
- `edit_note(identifier, operation, content)`  
  - Incrementally modify notes using specific edit operations.  
  - Suitable for fine-grained updates instead of full rewrites.
- `move_note(identifier, destination_path)`  
  - Move notes to different folders/paths, enabling reorganization of your knowledge structure.

---

### Pricing
- The source content does not specify pricing.  
- Basic Memory itself is available as an open-source Python package; **Basic Memory Cloud** is an optional subscription service (pricing details not provided in the source).