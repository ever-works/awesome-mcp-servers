# investor-agent

**Category:** Finance Market Data MCP Servers  
**Tags:** market-data, stocks, analysis  
**Source:** https://github.com/ferdousbhai/investor-agent

## Overview
investor-agent is a Model Context Protocol (MCP)-compatible agent/server that integrates with Yahoo Finance to provide stock market data and options-related information for use by AI assistants and tools.

## Features
- MCP-compatible server implementation for investor-focused workflows.
- Integration with Yahoo Finance as the primary data source.
- Fetches stock market data for equities.
- Provides options-related data and recommendations (e.g., options chains and analytics) for AI-driven analysis.
- Designed to be consumed by AI assistants and other tools via MCP.
- Organized command and skill structure (e.g., `commands/`, `skills/investment-analysis/`) to support investment-analysis workflows.

## Technical Details
- Distributed as a GitHub repository with Python-based project files (`pyproject.toml`, `.python-version`).
- Includes a `chat.py` entry point/script for interactive usage or integration.
- Uses a structured skills directory (`skills/investment-analysis`) to encapsulate investment analysis logic.
- MCP-related configuration present via `.claude-plugin` directory.

## Pricing
- No pricing information is provided in the available content; the repository appears to be an open-source project (LICENSE file present), but specific license terms and any usage costs should be confirmed in the LICENSE and project documentation on GitHub.
