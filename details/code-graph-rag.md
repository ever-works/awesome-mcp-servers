# Code-Graph-RAG

## Overview
Code-Graph-RAG is an MCP server that builds knowledge graphs from multi-language codebases using Tree-sitter AST parsing and Memgraph. It supports 11 programming languages and enables natural language querying of code structure and relationships including function calls, imports, and inheritance hierarchies.

## Key Details
- **Name:** Code-Graph-RAG
- **GitHub:** [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag)
- **PyPI:** code-graph-rag
- **Category:** Developer Tools / Code Analysis
- **License:** MIT

## Features
- **Multi-Language Support**
  - Parses 11 programming languages: Python, TypeScript, JavaScript, Java, C, C++, C#, Go, Rust, Ruby, PHP
  - Uses Tree-sitter for accurate AST parsing

- **Knowledge Graph Construction**
  - Builds a graph of functions, classes, modules, and their relationships
  - Tracks function calls, imports, inheritance, and containment relationships
  - Stores the graph in Memgraph for fast querying

- **Natural Language Querying**
  - Translates natural language questions into Cypher queries
  - Supports multiple LLM providers (OpenAI, Anthropic, Mistral)

- **MCP Tools**
  - index_repository, query_code_graph, get_code_snippet
  - list_projects, delete_project
  - read_file, write_file, list_directory

## Installation
pip install code-graph-rag

## Source
- [GitHub Repository](https://github.com/vitali87/code-graph-rag)
- [PyPI Package](https://pypi.org/project/code-graph-rag/)
