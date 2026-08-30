## Features

- Indexes codebases into a typed semantic graph: functions, types, modules as nodes; CALLS, IMPORTS, DATAFLOW, and EFFECTS as typed edges
- 40+ MCP tools for call-chain tracing, data-flow analysis, semantic search, and invariant checking
- Supports JavaScript, TypeScript, and JSX/TSX projects; runs locally via stdio transport
- Zero-telemetry design: all analysis runs on-device, no data leaves the machine
- Incremental re-indexing on code changes

## Use Cases

- AI coding agents navigating code structure without reading files line by line
- Call-chain and data-flow queries across large monorepos
- Semantic code search for functions, types, and patterns
- Invariant checking and dependency analysis

## Comparison to Traditional Code Search

Unlike grep or file-reading approaches, Grafema builds a semantic graph so agents can traverse call chains, follow data flow, and understand code relationships structurally. Supports 40+ targeted query tools rather than freeform search.

## Pricing

Free and open source (FSL-1.1-Apache-2.0). No telemetry, no accounts, no usage limits.
