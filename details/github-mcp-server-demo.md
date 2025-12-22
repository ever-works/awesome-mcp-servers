# GitHub MCP Server Demo

## Description
The GitHub MCP Server connects Warp’s agent environment to GitHub so AI agents can read from and write to repositories, issues, and pull requests, and automate common GitHub workflows directly from Warp.

## Features
- **GitHub integration via MCP**
  - Connects Warp agents to GitHub using a Personal Access Token (PAT).
  - Supports repository-level read and write operations (via `repo` scope).
  - Supports user-level read access (via `read:user` scope).
- **MCP server configuration**
  - Added to Warp via the MCP Panel and JSON configuration.
  - Once configured, available endpoints are automatically listed in the MCP UI.
- **Pull Request summarization**
  - Lists open pull requests in a repository.
  - Fetches associated comments and reviews for each pull request.
  - Produces summaries of open PRs, including clickable links back to GitHub.
  - Useful for PR triage or reviewing current development activity.
- **Issue creation from TODO comments**
  - Scans a codebase for `TODO` comments.
  - Calls a `create_issue` endpoint for each detected TODO.
  - Creates corresponding GitHub issues automatically.
  - Generates a linked list of all newly created issues.
- **End-to-end automation inside Warp**
  - Enables PR summarization and issue creation without leaving the Warp terminal.
  - Reduces manual navigation between terminal and browser for GitHub tasks.

## Setup
1. **Create a GitHub Personal Access Token**
   - Navigate to: `GitHub → Settings → Developer Settings → Personal Access Tokens`.
   - Create a new token with at least:
     - `repo`
     - `read:user`
2. **Add the MCP Server in Warp**
   - Open the **MCP Panel** from the Command Palette (`Cmd + P`).
   - Click **Add Server**.
   - Paste the JSON configuration and the GitHub access token.
   - Save to load and view all available MCP endpoints.

## Workflows
- **Workflow 1: Summarize All Open PRs**
  - Trigger Warp’s agent to summarize open pull requests.
  - The MCP server:
    - Lists all open PRs.
    - Fetches comments and reviews.
    - Compiles summaries with links to each PR.

- **Workflow 2: Create GitHub Issues from TODOs**
  - Use a saved prompt to automate issue creation from TODO comments.
  - Warp:
    - Scans the codebase for `TODO` comments.
    - Calls the `create_issue` MCP endpoint for each TODO.
    - Produces a linked list of the newly created issues.

## Pricing
Pricing information is not specified in the provided content.

## Additional Details
- **Name:** GitHub MCP Server Demo
- **Brand:** GitHub
- **Category:** mcp-server-directories-lists
- **Slug:** `github-mcp-server-demo`
- **Source URL:** https://docs.warp.dev/university/mcp-servers/github-mcp-summarizing-open-prs-and-creating-gh-issues
