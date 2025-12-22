# Windows CLI MCP Server

MCP server for secure, controlled command-line access on Windows systems, supporting PowerShell, CMD, Git Bash, and remote execution via SSH from within MCP-compatible LLM tools (e.g., Claude Desktop).

## Features
- **Windows command-line access** via the Model Context Protocol (MCP)
- **Multi-shell support**:
  - PowerShell
  - Command Prompt (CMD)
  - Git Bash
- **SSH support**:
  - Execute commands on remote systems via SSH
  - Managed via configured SSH connection profiles
- **Resource exposure to MCP clients**:
  - View configured SSH connections as resources
  - View current working directory
  - View server configuration as MCP resources
- **Security controls**:
  - Command and SSH command blocking (including full paths and case variations)
  - Working directory validation
  - Maximum command length limits
  - Command logging and history tracking
  - Smart argument validation
  - Ability to restrict allowed paths and directories
  - Ability to configure blocked commands
- **Configurable behavior**:
  - Custom security rules
  - Shell-specific settings
  - SSH connection profiles
  - Path restrictions
  - Blocked command lists
  - Directory restrictions for all operations
- **MCP client integration**:
  - Works with MCP-compatible tools such as Claude Desktop
  - Can be launched via `npx @simonb97/server-win-cli`
  - Supports specifying a custom configuration file via `--config`

## Pricing
- Not specified in the provided content.

## Links
- Source / repository: https://github.com/SimonB97/win-cli-mcp-server
- NPM package: https://www.npmjs.com/package/@simonb97/server-win-cli