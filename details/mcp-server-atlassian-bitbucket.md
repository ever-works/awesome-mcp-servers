# mcp-server-atlassian-bitbucket

**Category:** repository-code-analysis-mcp-servers  
**Brand:** Atlassian  
**Repository:** https://github.com/aashari/mcp-server-atlassian-bitbucket

Node.js/TypeScript MCP server that integrates with Atlassian Bitbucket Cloud, enabling AI systems (LLMs) to interact with Bitbucket workspaces, repositories, and pull requests via the Model Context Protocol.

---
## Features

- **Bitbucket Cloud integration**
  - Connects directly to Atlassian Bitbucket Cloud.
  - Works with Bitbucket workspaces, repositories, and pull requests.

- **MCP (Model Context Protocol) server**
  - Exposes Bitbucket functionality over the standard MCP interface.
  - Designed for use by AI systems / LLMs.

- **Repository and workspace tools**
  - List workspaces.
  - List repositories.
  - Get repository details.
  - Search across repositories (where supported by Bitbucket APIs).

- **Pull request tools**
  - List pull requests.
  - Get pull request details.
  - Comment on pull requests.

- **Operations exposed as tools**
  - `list`-style tools for enumerating workspaces, repositories, and pull requests.
  - `get`-style tools for retrieving specific items.
  - `comment` tools for adding comments to PRs.
  - `search` tools for searching relevant Bitbucket entities.

- **Implementation details**
  - Implemented in Node.js and TypeScript.
  - Configurable via environment variables (example config in `.env.example`).
  - Includes scripts and GitHub workflow configuration in the repo.

---
## Pricing

Open-source GitHub project. No pricing information is provided in the available content.
