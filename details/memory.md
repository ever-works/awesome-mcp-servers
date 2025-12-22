# Memory

**Category:** MCP Server – Directories & Lists  
**Source:** <https://github.com/madhukarkumar/anthropic-mcp-servers/blob/main/src/memory>

## Overview
Memory is an MCP (Model Context Protocol) server that provides a knowledge graph–based persistent memory system for LLMs. It enables models to store, link, and later recall structured information across interactions, supporting longer-term context and more consistent behavior over time.

## Features
- **Knowledge graph–based memory**  
  Stores information as interconnected entities and relations rather than flat text, enabling structured recall and reasoning.

- **Persistent storage**  
  Maintains data across sessions so LLMs can build and reuse knowledge over time instead of starting from scratch each run.

- **Structured information handling**  
  Designed to work with structured data (e.g., entities, attributes, relationships) rather than only unstructured natural language.

- **Linking of information**  
  Supports creating links between related pieces of data, allowing the LLM to navigate and retrieve connected facts and concepts.

- **Recall capabilities**  
  Provides mechanisms for retrieving previously stored information so the LLM can reference past context, decisions, or user-specific details.

- **MCP server implementation**  
  Exposes its capabilities via the Model Context Protocol, making it compatible with MCP-enabled tools and agents.

## Use Cases
- Long-term user or session memory for conversational agents.
- Storing and relating domain knowledge for LLM-powered tools.
- Building applications that require incremental knowledge accumulation and cross-session recall.

## Pricing
Pricing information is not specified in the provided content. The linked GitHub repository should be consulted for license and usage details.