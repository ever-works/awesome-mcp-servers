# AgentRPC MCP Server

## Description
AgentRPC MCP Server is a universal RPC layer for AI agents that exposes functions across languages and network boundaries through the AgentRPC protocol. It lets you connect tools and services running in private VPCs, Kubernetes clusters, or multiple cloud environments and access them via Model Context Protocol (MCP) or OpenAI‑compatible tool definitions.

- **Category:** mcp-middleware-orchestration  
- **Brand:** agentrpc  
- **Source:** https://github.com/agentrpc/agentrpc  
- **License:** Apache-2.0

## Features

- **Universal RPC interface**  
  - Wraps functions in a common RPC layer so AI agents can invoke them uniformly.  
  - Works across different programming languages and frameworks.

- **Cross-network connectivity**  
  - Access functions deployed in private VPCs.  
  - Supports services running inside Kubernetes clusters.  
  - Works across multiple cloud environments and network boundaries.

- **MCP integration**  
  - Exposes tools via the Model Context Protocol (MCP).  
  - Designed to act as an MCP server so AI systems that speak MCP can discover and call registered tools.

- **OpenAI-compatible tools**  
  - Publishes function/tool definitions in an OpenAI‑compatible schema.  
  - Can be used with OpenAI, Anthropic, LiteLLM, OpenRouter, and other OpenAI‑style tool consumers.

- **AgentRPC protocol**  
  - Uses the AgentRPC protocol as the transport and invocation layer.  
  - Allows AI tools to connect to and invoke remote functions without dealing with language‑specific or infrastructure‑specific wiring.

- **Multi-language support**  
  - Intended to connect functions regardless of implementation language.  
  - SDKs present in the repository for Go (`sdk-go`), Node.js (`sdk-node`), and Python (`sdk-python`).

- **Orchestration and remote execution**  
  - Orchestrates calls from AI agents to back-end services and tools.  
  - Enables remote execution of functions over the network while presenting them as local tools to the agent.

## Pricing

No explicit pricing information is provided in the referenced content. The GitHub repository is available under the Apache-2.0 open-source license.