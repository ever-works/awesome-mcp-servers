# LINE MCP Server

**Category:** Messaging MCP Servers  
**Brand:** LINE  
**Source:** https://github.com/amornpan/py-mcp-line

## Description

A Python Model Context Protocol (MCP) server that integrates with the LINE Messaging (Bot) API, allowing language models to read and analyze LINE conversations via a standardized interface.

## Features

### Core Functionality
- MCP server implementation for LINE Bot integration
- Enables language models to access and analyze LINE conversations
- Asynchronous operation using Python’s `asyncio`
- Environment-based configuration with `python-dotenv`
- Comprehensive logging system
- LINE Bot webhook event handling
- Message storage in JSON format (e.g., `data/messages.json`)
- FastAPI integration for HTTP/API endpoints
- Pydantic models for request/response data validation
- Support for multiple LINE message types:
  - Text messages
  - Sticker messages
  - Image messages

### Implementation & Structure
- Python 3.8+ based project
- Main implementation in `src/line/server.py`
- Package initialization in `src/line/__init__.py`
- Data directory (`data/`) for stored messages
- Test suite under `tests/` (e.g., `tests/test_line.py`)
- Configuration via `.env` with example in `.env.example`
- Docker support via `Dockerfile`
- Dependency management via `requirements.txt`

### Technology Stack
- **Frameworks/Libraries:**
  - FastAPI
  - Pydantic
  - `python-dotenv`
  - `mcp-server`
  - `line-bot-sdk`
  - `uvicorn` (ASGI server)

## Prerequisites

- Python 3.8+
- Required Python packages (as listed in `requirements.txt`):
  - fastapi
  - pydantic
  - python-dotenv
  - mcp-server
  - line-bot-sdk
  - uvicorn

## Pricing

Open-source project; no pricing information provided in the source content.