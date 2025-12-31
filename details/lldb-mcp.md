# lldb-mcp

**Category:** Testing & Debugging Tools  
**Tags:** debugging, binary-analysis, development  
**Source:** https://github.com/stass/lldb-mcp

## Overview

lldb-mcp is an MCP (Model Context Protocol) server that integrates the LLDB debugger with AI assistants (e.g., Claude). It allows an AI model to start, control, and interact with LLDB debugging sessions for binaries, core files, and running processes, enabling natural-language, AI-assisted debugging and binary analysis workflows.

## Features

### LLDB–MCP Integration
- Runs LLDB as a Model Context Protocol (MCP) server.  
- Exposes LLDB functionality to AI models to:
  - Start and manage debugging sessions.
  - Inspect program state and disassembly.
  - Analyze binaries and core dumps.
  - Perform interactive debugging via natural language prompts.

### Session Management Commands
- `lldb_start` – start a new LLDB debugging session.  
- `lldb_terminate` – terminate an existing LLDB session.  
- `lldb_list_sessions` – list active LLDB sessions.

### Program Loading
- `lldb_load` – load a binary into LLDB.  
- `lldb_attach` – attach to an existing running process.  
- `lldb_load_core` – load a core file for post‑mortem analysis.

### Execution Control
- `lldb_run` – start execution of the loaded program.  
- `lldb_continue` – resume execution after breakpoints or stops.  
- `lldb_step` – single-step into instructions/lines.  
- `lldb_next` – step over function calls.  
- `lldb_finish` – run until the current function returns.  
- `lldb_kill` – terminate the debugged process.

### Breakpoints and Watchpoints
- `lldb_set_breakpoint` – set breakpoints (e.g., by function, file:line, or address).  
- `lldb_breakpoint_list` – list all configured breakpoints.  
- `lldb_breakpoint_delete` – delete specific or all breakpoints.  
- `lldb_watchpoint` – set watchpoints to monitor memory locations.

### Inspection and Analysis
- `lldb_backtrace` – show the current call stack.  
- `lldb_print` – inspect variable or expression values.  
- `lldb_examine` – inspect memory at given addresses.  
- `lldb_info_registers` – display CPU register state.  
- `lldb_frame_info` – show information about the current frame.  
- `lldb_disassemble` – disassemble code around the current PC or a given range.  
- `lldb_process_info` – show information about the debugged process.

### Thread Management
- `lldb_thread_list` – list threads in the target process.  
- `lldb_thread_select` – select and focus on a specific thread.

### General / Miscellaneous
- `lldb_command` – run arbitrary LLDB commands directly.  
- `lldb_expression` – evaluate expressions in the target context.  
- `lldb_help` – get help on available LLDB-MCP commands.

### Example Program
- Includes `examples/overflow.c`, a C program that triggers a buffer overflow under certain arguments.  
- Intended as a sample target for demonstrating AI-guided debugging (e.g., compile with `cc overflow.c` and debug the resulting `a.out` via the MCP interface).

### Debugging Aids
- Ability to pass raw `lldb_command` for advanced or custom LLDB usage.  
- `--debug` flag (mentioned under Debugging Tips) for more verbose behavior when troubleshooting the tool itself.

### Licensing
- Licensed under the BSD 2‑Clause license.

## Installation

From the repository:

```bash
git clone https://github.com/stass/lldb-mcp.git
cd lldb-mcp
pip install mcp
```

Then configure your Claude (or other MCP-compatible) setup to use the lldb-mcp server.

## Pricing

No pricing information is provided; the project is an open-source repository under the BSD 2‑Clause license.