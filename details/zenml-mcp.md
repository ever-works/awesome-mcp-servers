# ZenML MCP

**Description:**  
ZenML MCP is an MCP (Model Context Protocol) server that connects MCP clients (such as Cursor or Claude Desktop) to ZenML MLOps and LLMOps pipelines, enabling orchestration control and pipeline insights directly through LLM-based tools.

**Website:** https://github.com/zenml-io/mcp-zenml

**Category:** mcp-middleware-orchestration  
**Tags:** mlops, orchestration, pipelines

---

## Features

- **MCP server for ZenML**  
  - Implements a Model Context Protocol server for interacting with ZenML from compatible MCP clients.

- **Client integrations**  
  - Designed to work with MCP-enabled tools such as:  
    - Cursor  
    - Claude Desktop  
  - Allows these tools (and other MCP clients) to manage and inspect ZenML resources via natural language.

- **MLOps and LLMOps pipeline access**  
  - Connects to existing ZenML MLOps and LLMOps pipelines.  
  - Exposes orchestration and operational information to LLM agents.

- **Orchestration capabilities**  
  - Enables LLMs and MCP clients to interact with pipeline orchestration (e.g., triggering or managing runs, depending on ZenML project setup and permissions).

- **Pipeline insights**  
  - Provides access to pipeline metadata and state via MCP, such as:  
    - Pipeline definitions and configurations  
    - Run status and history  
    - Execution details and related artifacts (as supported by the ZenML backend)

- **Open-source implementation**  
  - Source code publicly available on GitHub.  
  - Licensed under the MIT License, allowing broad use, modification, and integration.

- **Containerization support**  
  - Includes a `Dockerfile` for building container images of the MCP server.  
  - Provides a `.dockerignore` file to optimize Docker build context.

- **Automation & CI configuration**  
  - Contains GitHub Actions workflows under `.github/workflows` for automated checks and/or releases (details in repository).

- **Versioning and releases**  
  - Maintains a `VERSION` file and `RELEASE.md` for tracking and documenting releases.

- **Agent and client setup docs**  
  - `AGENTS.md` and `CLAUDE.md` provide guidance on configuring agents and using the MCP server with Claude / MCP-compatible tools.

---

## Pricing

- No pricing information is provided in the available content.  
- The project is open source under the MIT license; usage terms are defined by that license rather than a pricing plan.

---

## License

- **License:** MIT License

---

## Source

- **Repository:** https://github.com/zenml-io/mcp-zenml
- **Brand:** zenml
- **Slug:** zenml-mcp