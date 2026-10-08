## Overview

An MCP server that clones git repositories and generates tools for navigating package documentation structured in specific folders like hooks, components, and utils. Supports private repos via tokens, fuzzy search across files, and optional source code reading. Dual modes: read existing docs or get guidance to create them.

## Features

- Automatic MCP tool generation from docs structure
- Multi-module support (hooks, components, utilities, etc.)
- Configurable naming patterns (kebab, camel, snake, pascal, original)
- Tools for listing, overview, and details
- Fallback to package.json for version info
- Custom docs path and clone location
- Fuzzy search with prioritization (exact/partial name/content)
- Optional source code reading (--include-src)

## Usage Modes

**Read Documentation Mode** (`read-docs-{name}`):
Requires --name and --git-repo-path. Generates tools prefixed with package name.

**Create Documentation Mode** (`create-read-docs`):
No repo needed; provides setup instructions via get-create-docs-instructions tool.

## Configuration

CLI args:
- `--name`: Package name (required for read mode)
- `--git-repo-path`: Git URL (http/ssh, required for read mode)
- `--personal-token`: For private repos (GitHub/GitLab/Bitbucket)
- `--branch`: Default main
- `--docs-path`: Default docs
- `--clone-location`: Default ~/.temp-repo
- `--mode`: normal (default) or two-step
- `--include-src`: Enable source reading (default false)

## Operating Modes

**Normal Mode**:
Individual tools per module: `{name}-get-{module}-list`, `{name}-get-{module}-details`, `{name}-get-{module}-overview`, `{name}-fuzzy-search`.

**Two-Step Mode**:
5 generic tools: `{name}-get-overview`, `{name}-get-overall-list`, `{name}-get-module-overview/list/detail`, `{name}-fuzzy-search`.

## Cursor Integration

JSON configs provided for Mac/Linux/Windows, with examples for auth, custom paths, modes.

## Documentation Structure

`docs/read-docs-mcp.json`:
```json
{
  "name": "SomeLibrary",
  "moduleList": ["hooks", "components"],
  "fileName": "overview.md",
  "moduleFolderNamingPattern": "kebab"
}
```

Module `read-module-docs-mcp.json` for tool customization.

Files: list.md, overview.md, {item}.md.

## License

MIT