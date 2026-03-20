## Overview

The Hugging Face MCP (Model Context Protocol) Server connects your MCP-compatible AI assistant (for example Codex, Cursor, VS Code extensions, Zed, ChatGPT or Claude Desktop) directly to the Hugging Face Hub. Once connected, your assistant can search and explore Hub resources and use community tools, all from within your editor, chat or CLI.

## Key Features

### Hub Resource Access

- **Models**: Search and explore 500,000+ machine learning models
- **Datasets**: Access diverse datasets for training and evaluation
- **Spaces**: Interactive ML demos and applications
- **Papers**: Research papers and documentation

### Community Tools

Run community tools via MCP-compatible Gradio apps hosted on Spaces:
- Pre-built AI tools
- Custom Gradio applications
- Interactive demos
- Model inference interfaces

### Documentation Search

Search the Hugging Face documentation with natural language queries:
- Transformers library documentation
- Hub API references
- Best practices and tutorials
- Model cards and usage examples

## Transformers Inference Integration

### Multiple Backend Support

Transformers' models are compatible with different inference servers:
- vLLM for high-performance serving
- SGLang for efficient inference
- transformers serve CLI for local deployment
- Support for models of diverse modalities

### Transformers Serve Features

The transformers serve CLI spawns a local server offering:
- OpenAI SDK compatibility (de facto standard for LLM conversations)
- Continuous Batching (CB) for dynamic request grouping
- Shared forward passes on GPU for higher utilization
- Significantly better throughput

## MCP Client Integration

The MCPClient:
- Connects to MCP servers that expose tools
- Feeds these tools to an LLM (via AsyncInferenceClient)
- Manages execution requests when LLM decides to use a tool
- Relays Tool's output back to the LLM

## Setup

To get started:
1. Visit https://huggingface.co/settings/mcp while logged in
2. Select your MCP-compatible client:
   - Cursor
   - VS Code
   - Zed
   - Claude Desktop
   - ChatGPT
   - Other MCP-compatible tools

## Compatible Clients

- Codex
- Cursor IDE
- VS Code extensions
- Zed editor
- ChatGPT
- Claude Desktop
- Any MCP-compatible assistant

## Use Cases

- Model discovery and exploration
- Dataset search and analysis
- Running inference on community models
- Interactive ML demos
- Documentation lookup during development
- Research paper exploration
- Model card review
- Gradio app integration

## Spaces as MCP Servers

Hugging Face Spaces can function as MCP servers, enabling:
- Deployment of custom tools
- Interactive AI applications
- Community-built utilities
- Specialized ML workflows

## Technical Capabilities

- Natural language search across Hub resources
- Direct model inference
- Gradio app execution
- Documentation querying
- Paper search and retrieval
- Dataset exploration

## Pricing

Free access to Hugging Face Hub. Pro and Enterprise tiers available for enhanced features and compute resources.