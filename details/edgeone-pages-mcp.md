# edgeone-pages-mcp

**Category:** Content Management MCP Servers  
**Brand:** Tencent EdgeOne  
**Source:** https://github.com/TencentEdgeOne/edgeone-pages-mcp

## Overview
edgeone-pages-mcp is a Model Context Protocol (MCP) service/server that allows programmatic deployment of web content to Tencent EdgeOne Pages. It enables LLMs and MCP-compatible clients to publish HTML content, folders, or full-stack projects and get publicly accessible URLs in response.

## Features
- **MCP-compliant service**
  - Implements an MCP server that can be integrated with MCP-compatible clients and tooling.
  - Designed for use by LLMs and automated workflows.

- **Web content deployment to EdgeOne Pages**
  - Deploy raw HTML content directly.
  - Deploy folders containing static site assets.
  - Deploy full-stack projects (as supported by EdgeOne Pages).

- **Public URL generation**
  - After deployment, returns a publicly accessible URL for the deployed site/content.
  - Suitable for quickly sharing generated pages or demos.

- **Programmatic publishing**
  - Enables automated, code-driven publishing workflows from within agents or tools.
  - Integrates into conversations or tools where an LLM needs to generate and host web content.

- **Repository structure & assets**
  - `src/` for core service implementation.
  - `examples/` to demonstrate typical usage patterns.
  - `assets/` for additional supporting files (e.g., demo or documentation resources).
  - `tools/` for development or build utilities.

- **Configuration & tooling**
  - TypeScript-based project (`tsconfig.json`).
  - NPM package configuration (`package.json`, `package-lock.json`).
  - `.prettierrc` for code formatting and `.gitignore` / `.npmignore` for repository and package hygiene.

- **Licensing**
  - Distributed with a `LICENSE` file in the repository (specific license details should be confirmed in that file).

## Pricing
- Not specified in the provided content. The repository appears to be open-source; any usage-based costs would relate to Tencent EdgeOne Pages itself and are not described here.