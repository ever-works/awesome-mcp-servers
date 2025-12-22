# Linear MCP Server

The Linear MCP server provides a standardized interface for AI models and agents to securely access and manage data from a Linear workspace.

## Features
- Standardized MCP server for interacting with Linear workspaces.
- Secure access for AI models and agents to Linear data.
- Supports listing, retrieving, creating, and updating core Linear resources:
  - Comments
  - Cycles
  - Documents
  - Issues
  - Issue statuses
  - Issue labels
  - Projects
  - Teams
- Tools for both workspace-wide queries and user-specific views (e.g., issues assigned to the authenticated user).

## Endpoints
- `https://mcp.linear.app/mcp`
- `https://mcp.linear.app/sse`
- `mcp-remote`

## Tools
- `list_comments` — Retrieve a list of comments.
- `create_comment` — Create a new comment.
- `list_cycles` — Retrieve all cycles.
- `get_document` — Retrieve a specific document.
- `list_documents` — List all documents.
- `get_issue` — Get details of a specific issue.
- `list_issues` — List issues in the workspace.
- `create_issue` — Create a new issue.
- `update_issue` — Update an existing issue.
- `list_issue_statuses` — Retrieve all available issue statuses.
- `get_issue_status` — Retrieve details of a specific issue status.
- `list_my_issues` — List issues assigned to the authenticated user.
- `list_issue_labels` — Retrieve all available issue labels.
- `list_projects` — List all projects.
- `get_project` — Retrieve details of a specific project.
- `create_project` — Create a new project.
- `update_project` — Update an existing project.
- `list_teams` — List all teams.

## Pricing
- Not specified in the provided documentation.