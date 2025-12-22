# code-executor

## Description
MCP Code Executor is an MCP server that lets LLMs execute Python code inside a specified Python/Conda environment. It enables tool-based code execution with access to the libraries and dependencies defined in that environment, and is designed to support workflows where code needs to be run safely and reproducibly.

## Features
- **MCP server for code execution**: Exposes Python code execution as an MCP-compatible server for integration with LLM agents and tools.
- **Python environment control**: Runs code in a specified Python/Conda environment rather than a generic interpreter.
- **Access to environment dependencies**: Executed code can use libraries and dependencies installed in the configured environment.
- **Incremental code generation support**: Handles large code blocks that may exceed token limits by supporting incremental code generation and execution.
- **Tool-based workflows**: Designed for safe, tool-based Python execution workflows driven by LLMs.

## Pricing
- Open-source GitHub project (LICENSE file included); no commercial pricing or paid plans are specified in the provided content.