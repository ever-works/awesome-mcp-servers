# GhidraMCP

**Description**

GhidraMCP is a Ghidra plugin and MCP (Model Context Protocol) server that connects the Ghidra reverse engineering suite to AI assistants. It enables automated and interactive binary analysis, decompilation assistance, and code exploration through natural-language interaction with AI models.

**Category:** Testing & Debugging Tools  
**Tags:** reverse-engineering, debugging, development  
**Source:** https://github.com/13bm/GhidraMCP

---

## Features

- **MCP Integration**
  - Implements the Model Context Protocol (MCP) inside Ghidra.
  - Exposes Ghidra context and data to external AI assistants via MCP.

- **AI-Powered Binary Analysis**
  - Allows AI assistants to connect to Ghidra for automated binary analysis workflows.
  - Supports AI-assisted exploration of disassembly and decompilation output.

- **Natural Language Interface**
  - Lets users ask questions about binaries in plain English.
  - Enables conversational querying of reverse engineering data (functions, structures, etc.).

- **Deep Code Insights**
  - Retrieves detailed function information from Ghidra.
  - Provides access to decompiled code for use by AI models.

- **Binary Structure Analysis**
  - Exposes binary imports, exports, and memory layout information.
  - Facilitates structured inspection of program components.

- **Automated Security Analysis**
  - Supports AI-assisted identification and reasoning about potential security vulnerabilities.
  - Helps with triaging and reviewing suspicious code regions.

- **Socket-Based Architecture**
  - Uses a socket-based MCP server for communication between Ghidra and AI assistants.
  - Designed for high-performance, interactive sessions.

- **Cross-Platform Compatibility**
  - Works on all operating systems supported by Ghidra.

- **Bridge Script**
  - Includes a Python bridge script (`ghidra_server.py`) to run the MCP server side.

---

## Requirements

- **Ghidra:** 11.2.1 or newer
- **Java:** 17 or newer
- **Python:** 3.8+ (for the bridge script)

---

## Pricing

GhidraMCP is an open-source project hosted on GitHub. No pricing or paid plans are specified in the available content.