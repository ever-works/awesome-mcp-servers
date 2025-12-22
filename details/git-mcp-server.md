# Git MCP Server

**Brand:** model-context-protocol  
**Slug:** `git-mcp-server`  
**Category:** mcp-server-directories-lists  
**Source:** [PyPI – mcp-server-git](https://pypi.org/project/mcp-server-git/)

## Overview

Git MCP Server (`mcp-server-git`) is a Python-based Model Context Protocol (MCP) server that allows LLM-based MCP clients to programmatically read, search, and manipulate local Git repositories. It exposes a set of Git-focused tools for inspecting repository state, diffs, commits, branches, and logs, and for performing common Git operations.

> Note: The project is in early development; available tools and behavior may change over time.

## Features

### General
- Model Context Protocol server tailored for Git repositories.
- Enables LLM/MCP clients to interact with local Git repositories programmatically.
- Supports reading, searching, and manipulating Git repository state.
- Distributed as a Python package (`mcp-server-git`) on PyPI.
- Version example: `2025.12.18` (released Dec 18, 2025).

### Tools / Operations
Each tool is exposed as an MCP tool with the listed parameters.

- **`git_status`**  
  - Parameters: `repo_path`  
  - Exposes repository status for the given path.

- **`git_diff_unstaged`**  
  - Parameters: `repo_path`, `context_lines`  
  - Exposes the diff for unstaged changes in the specified repository, with configurable context lines.

- **`git_diff_staged`**  
  - Parameters: `repo_path`, `context_lines`  
  - Exposes the diff for staged changes in the specified repository, with configurable context lines.

- **`git_diff`**  
  - Parameters: `repo_path`, `target`, `context_lines`  
  - Exposes a generic diff against a specified `target` (e.g., branch, commit, etc.) with configurable context lines.

- **`git_commit`**  
  - Parameters: `repo_path`, `message`  
  - Creates a commit in the specified repository with the provided commit message.

- **`git_add`**  
  - Parameters: `repo_path`, `files`  
  - Stages one or more files in the specified repository.

- **`git_reset`**  
  - Parameters: `repo_path`  
  - Performs a reset operation in the specified repository (behavior such as mode is not described in the provided content).

- **`git_log`**  
  - Parameters: `repo_path`, `max_count`, `start_timestamp`, `end_timestamp`  
  - Exposes the commit log for a repository, with optional limits on number of entries and time range.

- **`git_create_branch`**  
  - Parameters: `repo_path`, `branch_name`, `base_branch`  
  - Creates a new branch from a specified base branch.

- **`git_checkout`**  
  - Parameters: `repo_path`, `branch_name`  
  - Checks out the specified branch in the target repository.

- **`git_show`**  
  - Parameters: `repo_path`, `revision`  
  - Shows information for a given revision (e.g., commit) in the repository.

- **`git_branch`**  
  - Parameters: `repo_path`, `branch_type`, `contains`, `not_contains`  
  - Exposes branch information, supporting optional filtering by branch type and commit containment.

## Installation & Usage

### Install with `uv` (recommended)
- No dedicated install step required when using [`uv`](https://docs.astral.sh/uv/).
- Use [`uvx`](https://docs.astral.sh/uv/guides/tools/) to run the server directly:
  - Command: `uvx mcp-server-git` (as referenced by the one-click install buttons).

### Install with `pip`
- Install package:
  ```bash
  pip install mcp-server-git
  ```
- Run as a module after installation:
  ```bash
  python -m mcp_server_git
  ```

## Configuration & Integrations

### Claude Desktop
- Can be configured for use with Claude Desktop by adding the server to `claude_desktop_config.json` (exact JSON not included in the provided content).

### VS Code / VS Code Insiders
- One-click install links are provided for VS Code and VS Code Insiders.
- Configuration used by these buttons (conceptually):
  - Command: `uvx`
  - Args: `["mcp-server-git"]`
- Integrates as an MCP server named `git` in VS Code via the MCP extension workflow.

## Pricing

- No pricing information is provided in the available content. The project is distributed as a Python package on PyPI; no paid plans or commercial tiers are described.