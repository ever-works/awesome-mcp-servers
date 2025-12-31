# Git Repo Research MCP Server

Model Context Protocol (MCP) server for semantic code search and repository analysis, enabling LLMs to research and explore Git repositories without cloning them locally.

## Overview
- **Type:** MCP server / developer tool
- **Category:** Repository & code analysis MCP servers
- **Use case:** Programmatic exploration of Git repositories (local or remote) with semantic search, summaries, and file access, to guide LLM-based code generation and research.

## Features
- **Repository Indexing**
  - Create searchable FAISS indexes from Git repositories
  - Supports both local and remote repositories
  - Designed for scalable, semantic search over repository content

- **Semantic Search**
  - Query repository content using natural language
  - Retrieve relevant code snippets and files based on semantics, not just keyword matching
  - Uses Amazon Bedrock embedding models (e.g., Titan Embeddings) with FAISS for vector search

- **Repository Summary & Structure**
  - Generate directory structures for repositories
  - Identify key files such as `README` and other important entry points
  - Useful for quick orientation in unfamiliar codebases

- **GitHub Repository Search**
  - Search GitHub repositories in AWS-related organizations
  - Filter repositories by license and keywords
  - Supports higher rate limits when a `GITHUB_TOKEN` is provided

- **File & Directory Access**
  - Access repository files and directories through the MCP server
  - Handles both text and binary content
  - Enables tools/LLMs to inspect specific files or paths directly

- **MCP Integration**
  - Designed to be added to MCP-compatible clients (e.g., Amazon Q, Claude MCP tooling)
  - Configurable via JSON MCP config with environment variables for AWS and GitHub
  - Works on multiple platforms, with specific config guidance for Windows (stdio + `uv` tooling)

## Prerequisites
- **Installation Requirements**
  - `uv` (fast Python package installer and resolver)
  - Python 3.12 or newer (`uv python install 3.12`)
  - AWS credentials configured with access to Amazon Bedrock
  - Node.js (for UVX installation support)

- **AWS Requirements**
  - AWS CLI configured with credentials that can access Amazon Bedrock
  - Access to Bedrock embedding models (e.g., Titan Embeddings)
  - Environment variables: `AWS_REGION`, `AWS_PROFILE`

- **Optional Requirements**
  - `GITHUB_TOKEN` environment variable for increased GitHub API rate limits when searching repositories

## Installation & Configuration
- Install and run via `uvx` / `uv` as an MCP server.
- Add to your MCP client config (e.g., Amazon Q, Claude) with:
  - `command`: `uvx` (or `uv` on Windows with `tool run --from ...`)
  - `args`: `["awslabs.git-repo-research-mcp-server@latest"]` (or equivalent Windows tool invocation)
  - `env`: set `AWS_PROFILE`, `AWS_REGION`, `FASTMCP_LOG_LEVEL`, `GITHUB_TOKEN` as needed
  - `type`: `stdio` (Windows example)
  - `timeout`, `disabled`, `autoApprove` options available in config

## Pricing
- Not specified in the provided content. (Assume open-source MCP server; AWS and GitHub usage may incur their own standard service costs.)