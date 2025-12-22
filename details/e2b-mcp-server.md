## E2B MCP Server

### Overview
E2B MCP Server is an open-source Model Context Protocol (MCP) server that connects AI agents (such as Claude with MCP support) to E2B’s secure, cloud-hosted sandboxes. It lets agents run arbitrary code in isolated remote environments rather than directly on the local machine.

### Features
- **MCP server for E2B** – Implements an MCP-compatible server that can be registered with MCP-capable AI clients.
- **Remote code execution** – Enables running arbitrary code inside E2B-managed sandboxes instead of on the host system.
- **Secure, isolated sandboxes** – Uses cloud-hosted environments to keep code execution separated from local resources.
- **Agent integration** – Designed to give Claude (and other MCP clients) programmatic access to E2B sandboxes via the MCP protocol.
- **Docker support** – Includes a `Dockerfile` for containerized deployment and reproducible environments.
- **Monorepo / workspace setup** – Organized as a pnpm workspace with multiple packages under `packages/` for modular development.
- **Configuration via repository files** – Includes configuration such as `smithery.yaml` and `.github` workflows for automation and tooling integration.

### Pricing
- **Open-source MCP server** – Available for free under the Apache-2.0 license.
- Any separate pricing for the underlying E2B cloud platform or sandboxes is not specified in this repository and would be managed independently of this MCP server.

### License
- **License:** Apache-2.0

### Links
- **Source code:** https://github.com/e2b-dev/mcp-server