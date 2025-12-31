# RepoMapper

**Category:** Repository Code Analysis MCP Servers  
**Tags:** code-analysis, repository, tool-discovery  
**Source:** https://github.com/pdavis68/RepoMapper

## Overview

RepoMapper (RepoMap) is an open-source command-line tool and MCP (Model Context Protocol) server that generates a structured “map” of a codebase within a Git repository. It is primarily intended to help LLM-based tools and other clients discover, prioritize, and navigate chat-relevant files and code elements during AI-assisted development or code review sessions. RepoMapper is based on Aider’s “Repo map” functionality.

## Features

- **Codebase Mapping for Git Repositories**
  - Analyzes a software repository to build a structured representation (map) of its files and code elements.
  - Focuses on chat-relevant and important files to support AI-assisted workflows.

- **Dual Interface: CLI Tool and MCP Server**
  - **Command-line application** for on-demand repository analysis.
  - **MCP server** implementation so MCP-compatible clients can query and use repository maps dynamically.

- **Tree-sitter–Based Code Parsing**
  - Uses Tree-sitter to parse source code for accurate extraction of code definitions and structure.
  - Enables language-aware understanding of code elements (e.g., functions, classes, modules).

- **Importance Ranking with PageRank**
  - Applies the PageRank algorithm to rank code elements by importance.
  - Highlights the most relevant files and definitions to prioritize what is shared with or referenced by LLMs.

- **Relationship & Dependency Awareness**
  - Captures relationships between files and code definitions (e.g., references, imports, calls) to build a more meaningful map of the repository.

- **Dynamic Discovery for Clients**
  - Provides MCP endpoints so compatible tools can discover, reference, and work with relevant project files during interactive sessions.
  - Designed for integration into AI-powered development and review workflows.

- **Git-Focused Operation**
  - Operates on repositories managed with Git.

- **Open Source**
  - Source code available on GitHub.
  - Includes a LICENSE file specifying open-source terms (see repository for exact license).

## Pricing

RepoMapper is an open-source tool hosted on GitHub. No pricing or paid plans are specified in the available content; it is provided under the open-source license included in the repository.