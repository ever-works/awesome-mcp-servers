---
name: isaac-sim-mcp
slug: isaac-sim-mcp
brand: NVIDIA
brand_logo: https://www.nvidia.com/etc/designs/nvidiaGDC/clientlibs_base/images/NVIDIA-Logo.svg
source_url: https://github.com/omni-mcp/isaac-sim-mcp
category: ai-integration-mcp-servers
tags:
  - simulation
  - robotics
  - 3d-modeling
images:
  - https://github.com/omni-mcp/isaac-sim-mcp/raw/HEAD/assets/isaac-sim-mcp-demo.png
  - https://developer.nvidia.com/sites/default/files/akamai/omniverse/isaac/isaac-sim-key-visual.jpg
featured: false
---

## Description

Isaac Sim MCP is an MCP server and NVIDIA Omniverse / Isaac Sim extension that enables natural‑language control of Isaac Sim, Isaac Lab, and other OpenUSD‑based simulations. It uses the Model Context Protocol (MCP) framework to translate conversational AI inputs into precise simulation actions, connecting MCP tools with embodied intelligence and robotics workflows.

## Features

- **MCP-based simulation control**
  - Implements a Model Context Protocol (MCP) server for Isaac Sim.
  - Bridges the MCP ecosystem with embodied / robotics simulation use cases.
- **Natural-language interaction**
  - Translates conversational or natural-language requests into concrete simulation operations.
  - Designed to control NVIDIA Isaac Sim, Isaac Lab, and other OpenUSD-based simulations.
- **Omniverse extension integration**
  - Ships as an Isaac Sim / Omniverse extension (`isaac.sim.mcp_extension`).
  - Runs inside Isaac Sim and connects to the external MCP server process.
- **Local MCP server endpoint**
  - Starts a dedicated Isaac Sim MCP server that listens on `localhost:8766` by default.
  - Server can be started via the included `isaac_mcp/server.py` module.
- **CLI and MCP tooling compatibility**
  - Compatible with the generic `mcp[cli]` Python package for running/inspecting MCP servers.
  - Supports development workflows via MCP inspect tools.
- **Configurable extension environment**
  - Uses Isaac Sim’s Python environment and settings (e.g., `envPath`, archive directories, online index options).
  - Logs startup and server thread status for debugging.

## Requirements

- NVIDIA Isaac Sim installed and configured.
- Ability to install and enable custom Isaac Sim / Omniverse extensions.
- Python environment compatible with `mcp[cli]` and the provided `server.py`.

## Installation

### 1. Install and enable the Isaac Sim extension

- Place the project folder where Isaac Sim can load extensions, for example:
  - `~/Documents/isaac-sim-mcp`
  - Extension subfolder: `isaac.sim.mcp_extension`
- Enable the `isaac.sim.mcp_extension` in Isaac Sim.
- Verify successful startup from the log output, which should include lines similar to:
  - `startup trigger on_startup for: isaac.sim.mcp_extension-0.1.0`
  - `Isaac Sim MCP server started on localhost:8766`

### 2. Install and run the MCP server

```bash
uv pip install "mcp[cli]"
uv run /home/ubuntu/Documents/isaac-sim-mcp/isaac_mcp/server.py
```

- The repository root is typically: `~/Documents/isaac-sim-mcp`.

### 3. Development mode

- For development, start the MCP inspect tooling (via `mcp[cli]`) to interactively test and debug the MCP server and its tools.

## Pricing

- Open-source project hosted on GitHub. No pricing information or paid plans are specified in the available content.

## License

- Includes a `LICENSE` file in the repository. Refer to the project’s `LICENSE` on GitHub for exact terms.