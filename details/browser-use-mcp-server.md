# Browser Use MCP Server

**Category:** Code Execution & Automation MCP Servers  
**Slug:** browser-use-mcp-server  
**Repository:** https://github.com/kontext-dev/browser-use-mcp-server  
**Brand:** kontext-dev

## Description
Browser Use MCP Server is an MCP (Model Context Protocol) server that packages the `browser-use` automation framework and exposes it via SSE transport. It provides a Dockerized environment with Chromium and VNC for remote, automated browser control and web interaction, suitable for browsing, scraping, and other headless or remotely controlled browser tasks.

## Features
- **MCP Server for `browser-use`**
  - Wraps the `browser-use` browser automation framework as an MCP-compatible server.
  - Enables LLM tools / MCP clients (e.g., editors like Cursor) to control a browser via MCP.

- **SSE Transport**
  - Uses Server-Sent Events (SSE) for communication between MCP clients and the browser automation backend.

- **Dockerized Browser Environment**
  - Includes a Docker setup to run the service in a containerized environment.
  - Ships with a Dockerfile for reproducible builds and deployment.
  - Designed to bundle a Chromium-based browser inside the container.

- **Chromium Integration**
  - Runs Chromium in a headless or automation-ready mode within the container.
  - Suitable for automated browsing, form filling, navigation, and scraping workflows.

- **VNC Support for Remote Control**
  - Provides VNC support for remote visual control and inspection of the browser running inside the container.
  - Allows users to connect to the running browser session for debugging or manual intervention.

- **Configuration & Environment Management**
  - `.env.example` for environment-variable-based configuration.
  - `.dockerignore` and `.gitignore` for clean container and repository management.

- **Code Quality & Tooling**
  - Python project configuration files such as `.flake8`, `.pylintrc`, `.python-version`.
  - Security and linting setup with `.bandit.yml` and `.mega-linter.yml`.
  - Contributor documentation via `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md`.

- **Open Source License**
  - Distributed with a LICENSE file (see repository for specific terms).

## Use Cases
- Automating web browsing from MCP-enabled editors or tools.
- Running web scraping or data extraction workflows via a standardized MCP interface.
- Remote visual debugging of automated browser sessions through VNC.
- Containerized, reproducible browser automation environments for development or CI.

## Pricing
- Not specified in the available content. The project is hosted on GitHub and includes a LICENSE file; see the repository for licensing and usage terms.