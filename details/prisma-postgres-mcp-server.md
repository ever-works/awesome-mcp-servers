## Prisma Postgres MCP Server

**Category:** database-messaging-mcp-servers  
**Brand:** prisma  
**Website:** https://mcp.prisma.io/mcp

### Overview
The Prisma Postgres MCP Server is a Model Context Protocol (MCP) server that connects AI tools (such as LLM-based agents and editors) to PostgreSQL databases managed via Prisma. It is accessible as a remote MCP server with OAuth 2.1 authentication and is designed to let AI systems securely interact with and manage Postgres databases using Prisma’s tooling and conventions.

### Features
- **MCP-based integration**
  - Exposes database capabilities over the Model Context Protocol for standardized AI-tool integration.
  - Acts as a bridge between LLMs and Postgres databases managed by Prisma.

- **Postgres + Prisma focus**
  - Targets PostgreSQL databases specifically.
  - Operates on databases that are managed via Prisma (using Prisma’s schema and tooling).

- **Remote server with OAuth 2.1**
  - Available as a remote MCP endpoint at `https://mcp.prisma.io/mcp`.
  - Uses OAuth 2.1 for authenticated, secure access from compatible AI clients.

- **Local vs. remote usage (implied)**
  - Designed to support different usage modes (local vs. remote) for development versus production-style setups.

- **CLI alignment**
  - Integrates conceptually with Prisma’s CLI workflows, allowing AI tools to perform database-related actions similar to what engineers do with the Prisma CLI.

- **Full lifecycle database management (high-level)**
  - Intended to support common stages of database work through AI tooling, such as:
    - Schema-aware interactions with the database.
    - Managing and evolving database state across the development lifecycle using Prisma conventions.

- **AI safety and guardrails (high-level)**
  - Designed with AI safety constraints in mind so that LLMs can interact with databases under controlled, policy-driven rules.
  - Uses authentication and scoped access to reduce risks from AI-driven database operations.

- **Editor / tool integration (implied)**
  - Can be used from MCP-capable environments such as code editors (e.g., VS Code) and other AI-powered tools that speak MCP.

### Use Cases
- Letting AI agents query and work with a Postgres database that is managed with Prisma.
- Using LLMs in development workflows (e.g., in an editor) to inspect or modify Prisma-managed database state within guardrails.
- Experimenting with “vibe coding” / rapid prototyping against a real Postgres backend via MCP.

### Pricing
- FAQ mentions the question “Is the Prisma MCP Server free?”, but the provided content does not include any explicit pricing details or plan descriptions.
- Pricing status is therefore **not specified** in the available content.