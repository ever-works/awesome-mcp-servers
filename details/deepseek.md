## Deepseek R1 MCP Server

**Category:** MCP server directories & lists  
**Repository:** https://github.com/66julienmartin/MCP-server-Deepseek_R1

## Overview
A Model Context Protocol (MCP) server implementation that connects Claude Desktop to DeepSeek’s language models (R1 and V3), exposing them as tools within the MCP ecosystem. The main focus is Deepseek R1, a language model optimized for reasoning tasks with an 8,192-token context window.

## Features
- **MCP Server for DeepSeek Models**
  - Implements an MCP server specifically for Deepseek R1.
  - Designed to connect Claude Desktop with DeepSeek’s R1 and V3 language models.
  - Exposes DeepSeek models as tools within the MCP ecosystem.

- **Reasoning-Optimized Model Support**
  - Supports Deepseek R1, described as optimized for reasoning tasks.
  - Handles a context window of up to 8,192 tokens.

- **Node.js/TypeScript Implementation**
  - Implemented in Node.js with TypeScript.
  - Uses the Node.js MCP SDK for improved type safety and error handling.
  - Aims for stable compatibility with Claude Desktop.

- **Project Structure & Assets**
  - `src/` directory for server source code.
  - `.env.exemple` file to illustrate environment variable configuration.
  - `Dockerfile` for containerized deployment.
  - `tsconfig.json` for TypeScript configuration.
  - `package.json` and `package-lock.json` for dependency management and scripts.
  - `LICENSE` file indicating it is distributed as open source.

- **Security & Assessment**
  - Includes an external security assessment badge (MseeP.ai Security Assessment Badge) linked from the README.

## Technology Stack
- Node.js
- TypeScript
- Model Context Protocol (MCP)
- Claude Desktop integration
- DeepSeek R1 and V3 language models
- Docker (for containerization)

## Pricing
- Not specified in the provided content (hosted as an open-source GitHub project; no pricing information given).