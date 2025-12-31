# typst-mcp

**Category:** content-management-mcp-servers  
**Brand:** johannesbrandenburger  
**Repository:** https://github.com/johannesbrandenburger/typst-mcp

## Description
`typst-mcp` is an MCP (Model Context Protocol) server that enables AI models and MCP-compatible clients to work with **Typst**, a markup-based typesetting system. It focuses on document conversion and processing between LaTeX and Typst, as well as validating and rendering Typst documents.

## Features
- **MCP server implementation for Typst**  
  - Exposes Typst-related capabilities via the Model Context Protocol for use by AI models or MCP clients.

- **LaTeX ↔ Typst conversion tools**  
  - Provides tools to convert documents between LaTeX and Typst formats (at least LaTeX → Typst; repository description emphasizes conversion between LaTeX and Typst).

- **Typst syntax validation**  
  - Validates Typst source code to help detect syntax errors before rendering or further processing.

- **Image generation from Typst code**  
  - Renders Typst documents or snippets into images (e.g., for previews or embedding in other contexts).

- **Typst document handling via MCP**  
  - Allows AI agents to interact with Typst documents programmatically through MCP (e.g., processing, conversion, validation, rendering).

- **Docker-based deployment support**  
  - Includes `Dockerfile.base`, `Dockerfile.runtime`, and `DOCKER.md` for containerized builds and runtime environments.

- **Python-based server implementation**  
  - Implemented in Python (`server.py`, `pyproject.toml`, `.python-version`), suitable for Python-oriented environments.

- **Project configuration and automation**  
  - Build script (`build.sh`) and CI/workflow configuration under `.github/workflows`.

## Pricing
No pricing information is provided in the available content. The repository appears to be an open-source project (a `LICENSE` file is present), but specific licensing and cost details should be confirmed in the repository’s `LICENSE` file.