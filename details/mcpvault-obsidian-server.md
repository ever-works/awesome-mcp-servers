## Overview

MCPVault is a universal AI bridge for Obsidian vaults using the Model Context Protocol standard. It provides safe read/write access to personal knowledge bases while preventing common issues like YAML frontmatter corruption.

## Features

### Safe Vault Access
- Intelligent YAML frontmatter parsing
- Corruption prevention mechanisms
- Atomic file operations
- Backup before modifications
- Rollback capabilities

### Read Operations
- Read individual notes
- Search vault contents
- Query by tags and frontmatter
- Navigate linked notes
- List vault structure

### Write Operations
- Create new notes safely
- Update existing notes
- Append to notes
- Modify frontmatter
- Add tags and links

### AI Assistant Features
- MCP-compatible interface
- Works with any MCP client
- Standard protocol compliance
- Extensible tool system

## Frontmatter Protection

Advanced YAML parsing and validation:
- Preserve existing frontmatter structure
- Validate YAML syntax before writing
- Merge frontmatter updates safely
- Handle edge cases and special characters
- Support for complex frontmatter schemas

## Use Cases

- Personal knowledge management
- Research note automation
- Daily note generation
- Template-based note creation
- Knowledge graph construction
- Content extraction and summarization
- Cross-note analysis
- Automated tagging and categorization

## Supported Note Features

- Standard markdown syntax
- YAML frontmatter
- Tags (inline and frontmatter)
- Internal links [[Note]]
- Embeds ![[Note]]
- Code blocks
- Tables and lists
- Callouts and highlights

## Technical Implementation

Lightweight design focused on safety and reliability. Uses robust YAML parsing libraries and file system monitoring to prevent data loss.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP-enabled AI assistants. Requires local Obsidian vault access.

## Configuration

Simple configuration pointing to vault location:
- Auto-detection of vault structure
- Configurable backup settings
- Custom exclusion patterns
- Read-only mode option