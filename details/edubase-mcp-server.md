# EduBase MCP Server

**Category:** Documentation & Learning Resources  
**Brand:** EduBase  
**Repository:** https://github.com/EduBase/MCP  
**Developer Docs:** https://developer.edubase.net

An open-source Model Context Protocol (MCP) server that connects Claude and other MCP-compatible LLM clients to the EduBase e-learning platform, enabling AI agents to work with your EduBase account and perform actions programmatically.

## Features

- **MCP server for EduBase**
  - Implements the Model Context Protocol specifically for the EduBase platform.
  - Exposes EduBase functionality to MCP-compatible LLM clients (e.g., Claude Desktop).

- **EduBase account integration**
  - Connects to a user’s EduBase account so the AI agent can act on the user’s behalf.
  - Intended to interact with EduBase’s e-learning, quiz, and exam management capabilities (as provided by the underlying platform and APIs).

- **Multiple transport protocols**
  - Supports `stdio` transport.
  - Supports `SSE` (Server-Sent Events) transport.
  - Supports streamable `HTTP` transport.

- **LLM / AI agent compatibility**
  - Designed to be used by Claude and other LLM-based tools that support MCP.
  - Enables automated workflows and agent-style operations within the EduBase environment.

- **Open-source implementation**
  - Source code available on GitHub.
  - Licensed under the MIT License.
  - Includes configuration files such as Dockerfile, TypeScript config, and build artifacts for deployment and development workflows.

## Technical Details

- **Language / stack**: TypeScript/Node.js (inferred from `tsconfig.json` and `package.json`).
- **Deployment**: Dockerfile included for containerized deployment.
- **Inspector / tooling**: `inspector.sh` script and `.pre-commit-config.yaml` for development workflows.

## Pricing

- Not specified in the provided content. The MCP server itself is open source under the MIT License; any EduBase platform pricing or account requirements are not detailed here.

## License

- **MIT License** (see `LICENSE` file in the repository).