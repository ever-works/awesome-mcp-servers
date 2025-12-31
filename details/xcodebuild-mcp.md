# xcodebuild MCP

## Overview
xcodebuild MCP is a Model Context Protocol (MCP) server for building iOS Xcode workspaces and projects. It runs Xcode builds and tests and returns compilation errors and diagnostics to LLM-based tools, enabling automated iOS build workflows directly from environments like Visual Studio Code (e.g., with Cline or Roo Code).

- **Category:** Development Tools – MCP Servers
- **Source:** https://github.com/ShenghaiWang/xcodebuild
- **Technology focus:** iOS, Xcode, build automation, MCP

## Features
- **MCP server for Xcode projects**
  - Implements a Model Context Protocol server dedicated to Xcode-based iOS projects.
  - Supports building Xcode workspaces and projects from an LLM or editor integration.

- **iOS build automation**
  - Triggers `xcodebuild` operations programmatically via MCP tools.
  - Automates compilation and testing workflows for iOS apps.

- **Error and diagnostics feedback to LLMs**
  - Captures compilation errors and warnings from Xcode builds.
  - Feeds structured error information back to LLM clients for automated debugging and code fixes.

- **Editor / tool integration**
  - Designed to work with MCP-aware tools such as:
    - Visual Studio Code extensions (e.g., Cline, Roo Code).
  - Enables a “build and inspect errors” loop entirely from within the LLM / editor environment.

- **Available MCP tools**
  - `build` – run an Xcode build for the configured project or workspace.
  - `test` – execute tests through Xcode tooling.
  - `folder` – interact with or reference the project folder (listed twice in repo, likely read/browse support; exact semantics defined in server implementation).

- **Python-based distribution**
  - Distributed as a Python package: `mcpxcodebuild`.
  - Can be run as a module with `python -m mcpxcodebuild`.
  - Includes project metadata in `pyproject.toml` and typical Python tooling files.

- **Flexible installation options**
  - **Using `uv` / `uvx` (recommended):**
    - Run mcpxcodebuild directly via `uvx` without explicit installation.
  - **Using `pip`:**
    - Install via `pip install mcpxcodebuild`.
    - Run the server with `python -m mcpxcodebuild`.

- **Configuration for MCP clients**
  - Supports configuration for Claude.app (and, by extension, other MCP-compatible clients) via MCP server configuration entries (details in repository README beyond the provided excerpt).

## Pricing
- No pricing information is provided in the available content. The repository includes a `LICENSE` file indicating it is an open-source project; specific license terms should be checked in the GitHub repository.