## Overview

MCP Unity bridges the Unity Editor with AI model clients like Claude Desktop, Windsurf, and Cursor via a Node.js MCP server. It enables AI-driven automation of Unity workflows.

## Features

### Execution Tools
- `execute_menu_item`: Run Unity menu items
- `select_object`: Select hierarchy objects
- `package_manager`: Manage Unity packages
- `run_tests`: Execute Unity tests
- `notify_message`: Display editor notifications

### Information Retrieval
- `get_menu_items`, `get_hierarchy`, `get_console_logs`, `get_packages`, `get_assets`, `get_tests`

### Setup
- Unity 2022.3+, Node.js 18+, npm 9+
- Configurable WebSocket port (default 8080)
- Docker support and MCP Inspector integration

## Pricing

Open-source under MIT license. No paid plans.