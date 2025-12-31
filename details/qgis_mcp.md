## qgis_mcp

**Category:** AI Integration – MCP Servers  
**Brand:** jjsantos01  
**Source:** https://github.com/jjsantos01/qgis_mcp

### Overview
qgis_mcp is a Model Context Protocol (MCP) server that links QGIS Desktop with Claude AI. It lets Claude directly interact with and control QGIS projects, supporting prompt-driven GIS workflows such as project setup, layer management, and spatial data operations from within an MCP-compatible client.

### Features
- **MCP Server for QGIS**  
  - Implements the Model Context Protocol to expose QGIS functionality to LLMs.
  - Designed to be used from Claude and other MCP-compatible clients.

- **QGIS Desktop Integration**  
  - Connects to a running QGIS Desktop environment.  
  - Allows remote control of QGIS actions via natural language prompts.

- **Prompt-Assisted GIS Workflows**  
  - Prompt-assisted project creation (e.g., setting up new QGIS projects).  
  - Layer management via prompts (adding, organizing, modifying layers).  
  - General GIS workflow automation mediated by an LLM.

- **Plugin and Python-based Implementation**  
  - Includes a `qgis_mcp_plugin` directory, indicating a QGIS plugin component to integrate MCP into the QGIS UI or runtime.  
  - Python-based server code under `src/qgis_mcp` and `main.py` for running the MCP server.

- **Development & Configuration Files**  
  - `pyproject.toml` for dependency and build configuration.  
  - `.python-version` for Python environment specification.  
  - `.gitignore` and `uv.lock` for environment and dependency management.  
  - `CONTRIBUTING.md` for contribution guidelines.

### Pricing
- No pricing information is provided in the available content; the project appears to be an open-source GitHub repository.
