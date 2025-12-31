# Discogs MCP Server

**Category:** Data Access & Integration · MCP Servers  
**Brand:** discogs

An MCP server that integrates with the Discogs API to provide structured, tool-style access to Discogs’ music database for search and catalog operations.

---

## Features

- **Discogs API integration**
  - Connects directly to the official Discogs API
  - Designed for structured search and catalog queries over the Discogs music database
- **MCP server implementation**
  - Implements the Model Context Protocol (MCP) to expose Discogs operations as tools
  - Can be integrated into MCP-compatible clients/agents
- **Search and catalog operations**
  - Oriented around searching releases, artists, labels, and related catalog data (per project description)
  - Structured responses suitable for automation and downstream processing
- **Configuration via environment files**
  - `.env.example` provided for environment variable setup (e.g., API keys, credentials, or configuration)
  - `.env.test` for test configuration
- **Docker support**
  - `Dockerfile` included for containerized deployment
- **TypeScript/Node.js project structure**
  - `src/` directory for server implementation
  - `tests/` directory for automated tests
  - `scripts/` for auxiliary tooling and automation
  - Uses `package.json` and `pnpm-lock.yaml` for dependency management
- **Development tooling**
  - ESLint configuration (`eslint.config.js`) for linting
  - Prettier configuration (`.prettierrc.json`, `.prettierignore`) for code formatting
  - VS Code settings in `.vscode/`
  - GitHub workflows/configuration in `.github/`
- **Documentation and metadata**
  - `README.md` as primary project documentation
  - `TOOLS.md` likely describing available MCP tools/operations
  - `CHANGELOG.md` for version and change tracking
- **Licensing**
  - Open-source license included in `LICENSE` (exact license type not specified in the provided content)

---

## Pricing

- Not specified in the provided content. The repository appears to be open source; refer to the project’s license and README for any usage or commercial terms.

---

## Source

- **Repository:** https://github.com/cswkim/discogs-mcp-server
