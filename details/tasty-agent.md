# tasty-agent

**Category:** Finance & Market Data MCP Servers  
**Tags:** trading, brokerage, automation

## Overview
`tasty-agent` is an MCP server that integrates with the Tastytrade platform via the Tastyworks API, enabling AI agents (such as Claude) to place and manage trades on a Tastytrade account.

Source: <https://github.com/ferdousbhai/tasty-agent>

## Features
- **MCP server for trading**
  - Exposes trading functionality as tools/endpoints compatible with AI agents.
  - Designed to let agents manage a Tastytrade portfolio programmatically.

- **Tastytrade / Tastyworks integration**
  - Connects to Tastytrade using the Tastyworks API.
  - Supports authenticated operations against a live Tastytrade brokerage account (details in repo configuration).

- **Trading operations**
  - Place trades via the Tastyworks API (exact order types and instruments depend on Tastytrade/Tastyworks capabilities and repository configuration).
  - Manage existing trades and positions (e.g., modify or close trades) through exposed MCP commands/skills.

- **Agent-oriented structure**
  - Contains `skills/trading` and `commands` directories indicating organized trading-related skills and commands for AI agents.
  - `agent.py` defines the main agent behavior / orchestration of trading actions.
  - `background.py` suggests background or scheduled operations (e.g., periodic checks or portfolio management tasks).

- **Developer tooling & tests**
  - `tests` directory for validating behavior.
  - `.claude-plugin` configuration present, indicating straightforward integration with Claude as a tool/plugin.

- **Implementation details**
  - Python-based project (Python version constrained by `.python-version`).
  - MIT licensed, allowing modification and reuse.

## Pricing
- Not applicable. This is an open-source project released under the MIT License; no pricing plans are listed in the repository.