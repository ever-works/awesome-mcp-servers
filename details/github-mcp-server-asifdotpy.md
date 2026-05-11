## Overview

This MCP server provides a comprehensive set of tools for interacting with GitHub repositories via the Model Context Protocol. It enables AI assistants to perform GitHub operations such as managing pull requests, repositories, branches, files, and secret scanning alerts.

## Features

### Pull Request Management
- List pull requests with filtering options
- Merge pull requests with customizable commit messages and merge methods
- Request Copilot reviews for pull requests
- Search pull requests using GitHub's search syntax
- Submit pending pull request reviews
- Update pull request details (title, description, base branch, state)
- Update pull request branch with expected HEAD SHA

### Repository Management
- Create new branches
- Create or update files in repositories
- Create new repositories with initialization options
- Delete files from repositories
- Fork repositories
- Get commit details
- Get file or directory contents
- Get tag details
- List branches
- List commits
- List tags
- Push files to repositories
- Search code using GitHub's code search syntax
- Search repositories

### Secret Protection
- Get secret scanning alert details by alert number
- List secret scanning alerts with filtering by resolution, secret type, and state

### User Management
- Search users using GitHub's user search syntax

## Library Usage

The exported Go API of this module should currently be considered unstable, and subject to breaking changes. In the future, we may offer stability; please file an issue if there is a use case where this would be valuable.

## License

This project is licensed under the terms of the MIT open source license. Please refer to MIT for the full terms.
