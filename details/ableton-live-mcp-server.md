# Ableton Live MCP Server

## Overview
Ableton Live MCP Server is an open-source Model Context Protocol (MCP) server that enables LLMs and other MCP clients to control and interact with Ableton Live via OSC (Open Sound Control). It builds on the AbletonOSC implementation and exposes Ableton Live’s OSC addresses as MCP tools.

- **Type:** Open-source MCP server
- **Category:** Media processing MCP servers
- **Use cases:** LLM-driven music production, session automation, remote control of Ableton Live
- **Source:** https://github.com/Simon-Kansara/ableton-live-mcp-server

## Features
- **MCP-based control interface**  
  - Implements the Model Context Protocol (MCP) to communicate with LLMs and other MCP clients.  
  - Exposes Ableton Live control as MCP tools.

- **OSC integration with Ableton Live**  
  - Uses Open Sound Control (OSC) for message transport to/from Ableton Live.  
  - Based on the [AbletonOSC](https://github.com/ideoforms/AbletonOSC) project for low-level Ableton integration.

- **Extensive OSC-to-tools mapping**  
  - Exhaustively maps available AbletonOSC OSC addresses to MCP tools.  
  - Allows broad access to Ableton Live controls via standardized MCP tool calls.

- **Two-component architecture**  
  - `mcp_ableton_server.py`: MCP server implementation exposing tools.  
  - `osc_daemon.py`: Daemon responsible for handling OSC communication with Ableton Live.

- **LLM-driven interaction**  
  - Designed so LLMs can programmatically control, automate, and query Ableton Live sessions by calling MCP tools.

- **Python-based implementation**  
  - Implemented in Python with dependencies:
    - `python-osc` for OSC communication  
    - `fastmcp` for MCP server scaffolding  
    - `uv` for project and dependency management

## Installation
**Requirements**
- `python-osc`
- `fastmcp`
- `uv`
- AbletonOSC (installed and configured in Ableton Live as per its documentation)

**General setup steps (from available info)**
1. Install `uv` following: https://docs.astral.sh/uv/getting-started/installation  
2. Clone the repository from GitHub.  
3. Install the project and dependencies using `uv`.  
4. Install and configure AbletonOSC in Ableton Live following the AbletonOSC project instructions.

## Usage
- Run the OSC daemon (`osc_daemon.py`) to handle OSC communication between the MCP server and Ableton Live.  
- Run the MCP server (`mcp_ableton_server.py`) to expose the OSC-mapped controls as MCP tools for clients (e.g., LLMs) to call.

*(The repository content snippet does not include detailed command-line examples or flags; refer to the README in the GitHub repo for exact run commands and configuration.)*

## Pricing
- No pricing information is provided in the available content. The presence of a `LICENSE` file in the repository indicates it is an open-source project; consult the GitHub repository’s LICENSE file for exact licensing terms.