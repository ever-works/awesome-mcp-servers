## Overview

mcp-probe-kit is a spec-driven development workflow MCP server for AI coding agents (Claude Code, Cursor, Codex, Cline and other MCP clients). It gives agents an orchestrated software-development lifecycle instead of free-form edits.

## Workflow

- start_feature / start_bugfix orchestration with structured plans
- Resumable plans with heartbeats, recoverable across sessions
- A converge gate that refuses to close a task without requirements, spec, implementation, test and review evidence
- Project memory and cross-session history so a new conversation can restore prior development context

## Installation

```bash
npx -y mcp-probe-kit@latest
```

No API keys required. Runs locally over stdio.

## Links

- Repository: https://github.com/mybolide/mcp-probe-kit
- Documentation: https://mcp-probe-kit.bytezonex.com/
- npm: https://www.npmjs.com/package/mcp-probe-kit
- Official MCP Registry: `io.github.mybolide/mcp-probe-kit`

## License

MIT
