# Home Assistant MCP Server

## Overview
Home Assistant MCP Server is an open-source Model Context Protocol (MCP) server that connects large language models (LLMs) to a Home Assistant instance, enabling them to view and control smart home entities such as lights, switches, sensors, and more.

- **Category:** mcp-server-directories-lists  
- **Brand:** Home Assistant  
- **Source:** [GitHub – tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp)

## Features
- **Home Assistant integration**  
  - Allows LLMs to access and manage Home Assistant entities.  
  - Supports interaction with common entities such as lights, switches, sensors, and other Home Assistant devices.

- **MCP server for LLM tooling**  
  - Exposes Home Assistant functionality through the Model Context Protocol for compatible LLM clients.  
  - Designed to let agents or LLM-based tools query state and issue control commands via a standardized interface.

- **Configuration & environment setup**  
  - Example environment configuration via `.env.example`.  
  - Git-ignored environment handling (`.gitignore`) to keep local configuration separate.

- **Containerization & deployment**  
  - `Dockerfile` provided for container-based deployment.

- **Testing & quality tooling**  
  - Test suite in the `__tests__` directory.  
  - Jest configuration files (`jest.config.*`, `jest.setup.*`, `jest-resolver.cjs`) for automated testing.  
  - ESLint configuration (`.eslintrc.json`) for code quality and consistency.

- **Documentation**  
  - `docs` directory for project documentation and usage guides.

- **Platform & implementation details**  
  - Node.js/JavaScript/TypeScript-based implementation (indicated by `package.json`, Jest configs, and `.ts` setup files).  
  - Script provided for Claude Desktop on macOS setup (`claude-desktop-macos-setup.sh`).

- **Source availability & licensing**  
  - Source code available on GitHub.  
  - Includes a `LICENSE` file specifying the open-source license terms.

## Pricing
- The project is an open-source GitHub repository.  
- No pricing or commercial plans are specified in the available content; usage is governed by the license included in the repository.