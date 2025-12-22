# PIF MCP Server

## Overview
PIF MCP Server (MCP-PIF) is an experimental Model Context Protocol (MCP) server implementing the Personal Intelligence Framework in Haskell. It provides a JSON-native lambda calculus runtime with metacircular evaluation, enabling language models to perform pure computation, evolve their own tools via metaprogramming, and maintain continuity of work across sessions through structured reasoning, file operations, and journal-based documentation.

## Features

### Metaprogramming & Runtime
- JSON-native lambda calculus runtime.
- Designed specifically as an MCP (Model Context Protocol) server.
- Metacircular evaluation: tools can inspect and transform other tools.
- Enables language models to evolve tools dynamically through metaprogramming.
- Homoiconic but constrained system (code and data share structure, within safety limits).
- Deterministic, fuel-bounded execution to keep computations inspectable and controlled.
- Provides a middle ground between:
  - Fixed APIs, and
  - Unrestricted arbitrary code execution.
- Frames the language model as an “executive function” operating a generic, metamorphic computer interface.

### Lambda Calculus Primitives
- Simple vocabulary of lambda calculus primitives focused on **pure computation only**.
- Three core metaprogramming primitives:
  - `quote`
  - `eval`
  - `code_of`
- Metacircular system built on these primitives:
  - Tools can analyze and transform other tools’ code.
  - Facilitates safe, evolvable computation.
- Asymmetric `quote` / `eval` design so eval’d code does **not** accidentally inherit the wrong tool context.
- When `eval` runs quoted code, it uses a controlled context including bindings such as:
  - `__tool_name`
  - `__self`
  - `code_of`
  - `__eval_depth`

### Personal Intelligence & Collaboration
- Part of the Personal Intelligence Framework (PIF) for human–AI collaboration.
- Tools for file operations to manage and reference external artifacts.
- Structured reasoning utilities to support complex, multi-step thinking.
- Journal-based documentation for:
  - Recording decisions and intermediate steps.
  - Maintaining a running narrative of work.
- Supports continuity across sessions, helping preserve context and progress over time.
- Oriented toward evolving, long-lived human–AI workflows rather than single isolated interactions.

### Safety & Boundaries
- Safe, inspectable, evolvable computation model:
  - Pure computation within the lambda calculus runtime.
  - Deterministic, fuel-bounded execution prevents unbounded or opaque behavior.
- Clear “event horizon” for metaprogramming:
  - Updating the **server code itself** (e.g., primitive set, parsing strategies, evolution/evaluation mechanisms) is **not** part of the metaprogramming loop.
  - The list of primitives and core evaluation process are fixed at runtime and cannot be modified by the language model.
  - This separation preserves a stable and predictable core while still allowing tool evolution within defined limits.

### Implementation Details
- Implemented in **Haskell**.
- Organized into core runtime and tools modules (e.g., `Core/`, `Tools/`).
- Uses JSON as the primary representation for lambda calculus terms and tool definitions.

## Pricing
- Distributed as an open-source GitHub repository.
- No pricing information or paid plans are specified; usage is assumed to be free under the project’s open-source license (check the repository for exact licensing terms).