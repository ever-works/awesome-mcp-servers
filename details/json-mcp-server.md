## JSON MCP Server

### Description
JSON MCP Server is an open-source Model Context Protocol (MCP) server that lets LLMs and tools query and manipulate JSON data. It provides standardized tools for working with JSON documents, including JSONPath-based querying and advanced operations on arrays, strings, numbers, and dates.

### Features
- **MCP server for JSON**
  - Implements a Model Context Protocol server focused on JSON data handling.
  - Exposes JSON operations as standardized tools for LLM integrations.

- **JSONPath querying**
  - `query` tool for querying JSON data using JSONPath syntax.
  - Supports extracting nested values and filtering data from complex JSON documents.

- **Advanced JSON operations**
  - Rich operations over JSON arrays (e.g., iteration/filtering-style behavior via JSONPath queries).
  - String-related operations via JSONPath expressions and transformations over JSON string fields.
  - Numeric-related operations through JSONPath selection and manipulation of numeric fields.
  - Date-related access and processing over date-like fields inside JSON documents.

- **JSON document processing**
  - Works over arbitrary JSON documents (objects and arrays).
  - Designed for programmatic interaction and automation via MCP-compatible clients.

- **Node.js / npm package**
  - Distributed as an npm package: `@gongrzhe/server-json-mcp` (version shown: `1.0.3`).

### Installation & Usage
- Available as npm package: `@gongrzhe/server-json-mcp`.
- Can be run via `npx` or installed globally (the README references:
  - using `npx` with a specific version,
  - installing a specific version globally,
  - and running the server after global installation).
- Refer to the project README for exact commands and configuration details.

### License
- Licensed under the **MIT License**.

### Pricing
- **Open-source, free**
  - No paid tiers are listed.
  - Usable under the terms of the MIT license.