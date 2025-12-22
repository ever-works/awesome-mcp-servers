# Postman MCP Server

**Description**

Postman MCP Server is an open-source Model Context Protocol (MCP) server that runs Postman Collections locally via Newman, executes API tests, and returns structured pass/fail results through MCP.

## Features

- **MCP server for API testing**
  - Implements a server compatible with the Model Context Protocol.
  - Enables LLM/MCP clients to trigger and manage Postman Collection runs.

- **Postman Collections execution via Newman**
  - Runs Postman Collections locally using Newman (the Postman CLI runner).
  - Leverages Newman’s collection execution engine to perform API requests and validations.

- **Automated API test execution**
  - Executes tests defined inside Postman Collections.
  - Produces outcomes for individual requests and test scripts.

- **Pass/fail reporting through MCP**
  - Returns API test results as pass/fail status via MCP.
  - Makes test outcomes machine-readable for downstream tools and agents.

- **Repository structure for development and usage**
  - `src/` for source code implementation of the MCP server.
  - `test/` for automated tests.
  - `example/` for example usage or configuration.
  - `prompts/` potentially for MCP/LLM prompt templates or examples.
  - Includes configuration and tooling files (`Dockerfile`, `vitest.config.ts`, `tsconfig*.json`, `.husky`, `.github`) to support development, testing, and CI workflows.

## Pricing

Pricing information is not specified in the repository. The project is publicly available on GitHub; refer to the repository for license and usage terms.