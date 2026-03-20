## Overview

Obsidian GitHub MCP Server provides AI assistants with access to Obsidian vaults stored in GitHub repositories. It combines the power of Obsidian's knowledge management with GitHub's version control and collaboration features.

## Features

### GitHub Integration
- Access Obsidian vaults from GitHub repositories
- Support for public and private repositories
- Branch-based vault access
- Commit history navigation
- Multi-repository support

### Vault Operations
- Read note contents
- Search across all notes
- Navigate bidirectional links
- Query frontmatter metadata
- Discover tags and categories

### Knowledge Base Analysis
- Graph view analysis
- Link relationship mapping
- Tag clustering
- Orphaned note detection
- Content similarity analysis

### Collaboration
- Team knowledge base access
- Version-controlled documentation
- Distributed note-taking
- Change tracking and history

## Use Cases

- Team documentation management
- Research collaboration
- Technical documentation access
- Knowledge base search and retrieval
- Documentation generation
- Content analysis and insights
- Learning material organization
- Project wikis and notes

## Obsidian Features Supported

- Markdown files with Obsidian syntax
- Wiki-style links [[Note Name]]
- Backlinks and forward links
- YAML frontmatter
- Tags (#tag and frontmatter tags)
- Aliases
- Embeds and transclusions

## Technical Implementation

Connects to GitHub API to access repository contents, parses Obsidian markdown format, and resolves internal links and references. Respects GitHub rate limits and authentication.

## Security

Supports GitHub authentication via:
- Personal access tokens
- OAuth apps
- GitHub Apps
- Fine-grained permissions

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Requires GitHub credentials for private repository access.