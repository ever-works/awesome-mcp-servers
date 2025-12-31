# bazi-mcp

**Category:** AI Integration – MCP Servers  
**Developer:** cantian-ai  
**License:** ISC  
**Source:** https://github.com/cantian-ai/bazi-mcp

An MCP server that provides Bazi (八字, Four Pillars of Destiny) chart generation and analysis, exposing traditional Chinese astrology / metaphysics calculations to LLMs.

![bazi-mcp demo](https://github.com/cantian-ai/bazi-mcp/raw/HEAD/assets/bazi-mcp-demo.png)

---

## Features

- **MCP Server for Bazi**
  - Implements the Model Context Protocol (MCP) so tools/LLMs can call Bazi-related functions programmatically.
  - Designed to integrate Bazi calculations directly into AI agents and chat environments.

- **Bazi Chart Generation**
  - Generates a full Bazi (Four Pillars of Destiny) chart from birth data (implied by its role as a “Bazi calculator”).
  - Encodes traditional Chinese metaphysics structures for use by LLMs.

- **Bazi Analysis Interface**
  - Exposes functions for Bazi chart interpretation and analysis to AI systems.
  - Targets improved accuracy over generic “AI fortune-telling” by basing outputs on structured metaphysics calculations.

- **Developer-Friendly Implementation**
  - Distributed as an open-source GitHub repository.
  - Includes configuration and project files such as:
    - `Dockerfile` for containerized deployment.
    - TypeScript configuration (`tsconfig.json`).
    - Node.js project metadata (`package.json`, `package-lock.json`).
    - VS Code configuration directory (`.vscode`).
    - Formatting configuration (`.prettierrc.json`).
    - MCP-related metadata files (`glama.json`, `smithery.yaml`).

- **Open Source & Collaboration**
  - Public repository with active community signals (stars and forks).
  - Licensed under the ISC license for permissive reuse and modification.

---

## Technical Stack

- **Language:** TypeScript / Node.js (inferred from `tsconfig.json`, `package.json`).
- **Deployment:** Docker support via included `Dockerfile`.
- **Protocol:** Model Context Protocol (MCP) for tool-style integration with LLMs.

---

## Pricing

- Not specified in the provided content. The project is open source under the ISC license; usage is governed by that license rather than a pricing plan.