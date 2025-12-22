# ArangoDB MCP Server

A TypeScript-based Model Context Protocol (MCP) server that exposes ArangoDB database capabilities to LLMs, enabling schema-aware querying and manipulation of ArangoDB collections and graphs.

**Source:** [GitHub – ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb)

---

## Features

- **MCP server for ArangoDB**
  - Implements the Model Context Protocol to let LLMs interact with ArangoDB.
  - Designed to provide schema-aware querying and manipulation of collections and graphs.

- **TypeScript-based implementation**
  - Server logic written in TypeScript.
  - Configured via standard Node/TypeScript project files (`package.json`, `tsconfig.json`).

- **Core database tools (MCP tools)**
  - `arango_query` – Execute AQL queries against ArangoDB.
  - `arango_insert` – Insert documents into collections.
  - `arango_update` – Update existing documents.
  - `arango_remove` – Remove documents from collections.

- **Integration with LLM tooling**
  - Usable from the Claude app via MCP.
  - Compatible with VS Code extensions that support MCP (e.g., Cline).

- **Container-friendly setup**
  - Includes a `Dockerfile` for containerized deployment.

---

## Compatibility / Integrations

- **ArangoDB** – Targets ArangoDB databases for queries and data manipulation.
- **Claude** – Can be used as an MCP server within the Claude app.
- **VS Code** – Works with MCP-compatible VS Code extensions such as Cline.

---

## Licensing

- A `LICENSE` file is provided in the repository; refer to it for the exact open-source license terms.

---

## Pricing

- No pricing information is listed. The project is distributed via GitHub as an open-source MCP server; usage conditions are governed by the repository’s license.