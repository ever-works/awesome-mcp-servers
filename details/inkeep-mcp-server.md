# Inkeep MCP Server

**Category:** AI Integration – MCP Servers  
**Slug:** inkeep-mcp-server  
**Brand:** inkeep

Python-based MCP server that connects AI assistants to your proprietary documentation and product content using Inkeep’s RAG (retrieval-augmented generation) capabilities.

![Inkeep MCP Server](https://inkeep.com/og-image.png)

---

## Overview

Inkeep MCP Server is an open-source, Python-based Model Context Protocol (MCP) server that exposes your Inkeep-powered knowledge base to AI assistants. It enables retrieval-augmented search over your docs and product content so assistants can ground responses in your own data.

License: **MIT**  
Source: [https://github.com/inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python)

---

## Features

- **RAG over proprietary content**  
  - Uses Inkeep to perform retrieval-augmented search across your documentation and product content.  
  - Designed so AI assistants can fetch relevant documents and ground their answers in your data.

- **MCP (Model Context Protocol) server implementation**  
  - Implements an MCP server in Python, suitable for tools and assistants that support MCP.  
  - Exposes RAG/search functionality via standardized MCP interfaces.

- **Python-based project**  
  - Distributed as a Python project with `pyproject.toml`.  
  - Includes development environment files such as `.python-version` and `.gitignore`.

- **Dependency management via `uv`**  
  - Uses [`uv`](https://github.com/astral-sh/uv) as the Python project manager.  
  - Supports creating virtual environments and installing dependencies through `uv`.

- **Docker support**  
  - Includes a `Dockerfile` for containerized deployment.  
  - Enables running the MCP server in a consistent, isolated environment.

- **Inkeep integration**  
  - Requires an Inkeep account and project configuration.  
  - Uses an Inkeep API key obtained from the Inkeep Dashboard’s “Projects” section.  
  - Relies on Inkeep-managed RAG indexing and search.

- **Local setup instructions (Git-based)**  
  - Clone the repository via Git.  
  - Create a virtual environment with `uv venv`.  
  - Install dependencies from `pyproject.toml` using `uv pip install -r pyproject.toml`.  
  - Run locally for development or integration testing.

---

## Requirements

- **Inkeep account** to configure and manage RAG over your content.  
- **Inkeep project and API key**, obtained from the Inkeep Dashboard (Projects section).  
- **Python environment**, managed via `uv`.  
- **Git** (for cloning the repository).  
- Optional: **Docker** (for containerized deployment).

---

## Pricing

The repository itself is open-source under the MIT license.  
No specific commercial pricing or plan details are provided in the available content. Use of the server requires an Inkeep account; any pricing for Inkeep services is not described here.

---

## Links

- **Source code:** https://github.com/inkeep/mcp-server-python  
- **Inkeep:** https://inkeep.com  
- **Brand logo:** https://inkeep.com/favicon-196x196.png