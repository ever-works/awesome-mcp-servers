# mcp_massive

**Category:** Finance Market Data MCP Servers  
**Source:** https://github.com/massive-com/mcp_massive

An experimental Model Context Protocol (MCP) server that exposes the Massive.com financial market data API as MCP tools, enabling LLMs and MCP-compatible clients (e.g., Claude Code / Claude Desktop) to query a wide range of real-time and historical market data.

---

## Features

### Market Data Coverage
- Access to all Massive.com API endpoints via MCP tools
- Support for multiple asset classes:
  - Stocks
  - Options
  - Forex
  - Crypto
- Data types exposed include:
  - Aggregates and bars for supported instruments
  - Real-time trades
  - Historical trades
  - Real-time quotes
  - Historical quotes
  - Market snapshots
  - Ticker details and reference data
  - Dividends data
  - Splits data
  - Financial fundamentals
  - Market status
  - Market holidays

### MCP Integration
- Implements the Model Context Protocol (MCP) server interface
- Designed for LLM-friendly access to market data
- Exposes Massive.com endpoints as MCP tools for:
  - Querying instruments and tickers
  - Fetching time-series market data
  - Retrieving reference and fundamentals information
  - Checking market status and holiday schedules

### Client & Environment Integration
- Works with Claude Code (CLI) as an MCP server
  - Configurable via `claude mcp add` command
  - Supports local and global installation scopes via Claude CLI
- Works with Claude Desktop as an MCP server
  - Configurable through `claude_desktop_config.json`
  - Allows setting environment variables such as `MASSIVE_API_KEY` and `HOME`

### Technical Requirements
- Python 3.10+
- Massive.com API key (required to access the underlying data)
- Astral UV toolchain (`uvx` command support required)
- Installable directly from GitHub via `uvx` with a tagged version (e.g., `v0.6.0`)

### Project Status
- Marked as experimental
- Subject to potential breaking changes across versions

---

## Installation & Setup (Summary)

### Prerequisites
- Python 3.10 or later
- Massive.com API key
- Astral UV installed with `uvx` available in PATH

### Claude Code (CLI)
- Install Claude Code globally via npm
- Add the Massive MCP server using a command of the form:
  - `claude mcp add massive -e MASSIVE_API_KEY=your_api_key_here -- uvx --from git+https://github.com/massive-com/mcp_massive@v0.6.0 mcp_massive`
- Optional: use `-s <scope>` to change install scope

### Claude Desktop
- Configure MCP server in `claude_desktop_config.json` with:
  - `command`: path to `uvx`
  - `args`: `--from`, Git repo URL with version tag, and `mcp_massive`
  - `env`: includes `MASSIVE_API_KEY` and `HOME`

---

## Pricing

No pricing details are specified in the provided content. A Massive.com API key is required; its cost or plan structure is not described here.