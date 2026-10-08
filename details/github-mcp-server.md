# GitHub MCP Server

## Overview

The GitHub MCP Server connects AI tools directly to GitHub's platform, enabling AI agents, assistants, and chatbots to read repositories and code files, manage issues and PRs, analyze code, and automate workflows through natural language interactions.

## Use Cases

- **Repository Management**: Browse and query code, search files, analyze commits, and understand project structure across any repository you have access to.
- **Issue & PR Automation**: Create, update, and manage issues and pull requests. Let AI help triage bugs, review code changes, and maintain project boards.
- **CI/CD & Workflow Intelligence**: Monitor GitHub Actions workflow runs, analyze build failures, manage releases, and get insights into your development pipeline.
- **Code Analysis**: Examine security findings, review Dependabot alerts, understand code patterns, and get comprehensive insights into your codebase.
- **Team Collaboration**: Access discussions, manage notifications, analyze team activity, and streamline processes for your team.

## Features

The server provides a wide range of GitHub API capabilities organized into toolsets:

- **context**: Tools that provide context about the current user and GitHub context
- **actions**: GitHub Actions workflows and CI/CD operations
- **code_security**: Code security related tools, such as GitHub Code Scanning
- **copilot**: Copilot related tools
- **dependabot**: Dependabot tools
- **discussions**: GitHub Discussions related tools
- **gists**: GitHub Gist related tools
- **git**: GitHub Git API related tools for low-level Git operations
- **issues**: GitHub Issues related tools
- **labels**: GitHub Labels related tools
- **notifications**: GitHub Notifications related tools
- **orgs**: GitHub Organization related tools
- **projects**: GitHub Projects related tools
- **pull_requests**: GitHub Pull Request related tools
- **repos**: GitHub Repository related tools
- **secret_protection**: Secret protection related tools, such as GitHub Secret Scanning
- **security_advisories**: Security advisories related tools
- **stargazers**: GitHub Stargazers related tools
- **users**: GitHub User related tools

Additionally, remote GitHub MCP Server offers special toolsets:
- **copilot**: Copilot related tools (e.g. Copilot Coding Agent)
- **copilot_spaces**: Copilot Spaces related tools
- **github_support_docs_search**: Search docs to answer GitHub product and support questions

## Configuration

### Remote Server

The remote GitHub MCP Server is hosted by GitHub and can be configured via HTTP:

```json
{
  "servers": {
    "github": {
      "type": "http",
      "url": "https://api.githubcopilot.com/mcp/"
    }
  }
}
```

Supports OAuth or Personal Access Token (PAT) authentication.

### Local Server

Run locally with Docker:

```json
{
  "mcp": {
    "servers": {
      "github": {
        "command": "docker",
        "args": [
          "run",
          "-i",
          "--rm",
          "-e",
          "GITHUB_PERSONAL_ACCESS_TOKEN",
          "ghcr.io/github/github-mcp-server"
        ],
        "env": {
          "GITHUB_PERSONAL_ACCESS_TOKEN": "${input:github_token}"
        }
      }
    }
  }
}
```

### Toolsets

Enable or disable specific groups of functionalities via the `--toolsets` flag or `GITHUB_TOOLSETS` environment variable.

- Default toolset includes: `context`, `repos`, `issues`, `pull_requests`, `users`
- Use `--toolsets all` to enable all available toolsets
- Insiders mode available via `--insiders` flag or `GITHUB_INSIDERS=true`

### CLI Utilities

The binary includes subcommands for debugging:
- `github-mcp-server tool-search "<query>"` searches tools by name, description, and input parameter names.

## Pricing

Free and open-source. The source code is available on GitHub under the MIT license.

## Installation Guides

Refer to the repository's installation guides for various MCP hosts:
- VS Code (with GitHub Copilot)
- JetBrains, Visual Studio, Eclipse, Xcode
- Claude Desktop and Claude Code CLI
- OpenAI Codex
- Cursor IDE
- Windsurf IDE
- Google Gemini CLI
- Rovo Dev CLI
- GitHub Copilot CLI

## Notes

- For GitHub Enterprise Server and Enterprise Cloud with data residency, use the `GITHUB_HOST` environment variable.
- Remote server insiders version provides early access to new features and experimental tools.
- Always keep your GitHub PAT secure; use environment variables and avoid committing tokens to version control.
