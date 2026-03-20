## Overview

ESLint MCP Server is the official Model Context Protocol implementation from ESLint, introduced in version 9.26.0. It enables large language models and AI assistants to run ESLint for code linting and analysis, providing automated code quality assistance.

## Features

### Code Linting
- Run ESLint on JavaScript and TypeScript files
- Identify syntax errors and code smells
- Apply formatting and style rules
- Check for common bugs and anti-patterns
- Enforce coding standards

### ESLint Configuration
- Support for all ESLint configuration formats
- Plugin management and loading
- Custom rule configuration
- Shareable config support
- Environment-specific settings

### Auto-fixing
- Automatic code fixes for simple issues
- Safe transformations only
- Preview fixes before applying
- Batch fixing capabilities

### IDE Integration
- Works with AI-powered coding assistants
- Real-time linting feedback
- In-editor diagnostics
- Quick fix suggestions
- GitHub Copilot integration

## Use Cases

- AI-assisted code quality improvement
- Automated code review
- Pre-commit hook automation
- Continuous integration linting
- Learning JavaScript/TypeScript best practices
- Code style enforcement
- Security vulnerability detection

## Configuration

Start the ESLint MCP server using the `--mcp` flag:
```bash
npx eslint --mcp
```

For VS Code integration, create `.vscode/mcp.json`:
```json
{
  "command": "npx",
  "args": ["@eslint/mcp@latest"]
}
```

## Supported Rules

- ECMAScript syntax validation
- React and JSX linting
- TypeScript-specific rules
- Node.js best practices
- Accessibility checks (with plugins)
- Security rules (with plugins)
- Custom plugin rules

## Technical Implementation

Built and maintained by the ESLint team, ensuring compatibility with all ESLint features and updates. Provides standardized MCP tools for linting operations.

## Integration

Compatible with:
- GitHub Copilot
- Claude Desktop
- Cursor
- VS Code with MCP support
- Other AI-powered development tools

## Performance

Optimized for fast linting operations with caching support, incremental analysis, and parallel processing for large codebases.