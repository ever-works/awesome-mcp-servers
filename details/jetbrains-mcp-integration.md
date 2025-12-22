## JetBrains MCP Integration

**Status:** Deprecated – core MCP functionality has been integrated into all IntelliJ-based IDEs starting with version 2025.2. This NPM-based proxy server is no longer maintained.

### Description
JetBrains MCP Integration is a Model Context Protocol (MCP) proxy server that lets agents work with code directly inside JetBrains IDEs. It sits between an MCP client and a JetBrains IDE, forwarding requests so tools and agents can interact with the codebase in IntelliJ-based environments.

### Features
- MCP proxy server that forwards requests from an MCP client to a JetBrains IDE
- Designed for IntelliJ-based IDEs, including:
  - IntelliJ IDEA
  - PyCharm
  - WebStorm
  - Android Studio
  - Other IntelliJ-platform IDEs
- Enables agents to work with and operate on code directly inside JetBrains development environments
- Distributed as an NPM package for use alongside JetBrains IDE tooling

### Compatibility & Related Components
- Works with JetBrains IDEs via the JetBrains **MCP Server** plugin: <https://plugins.jetbrains.com/plugin/26071-mcp-server>
- Intended for setups where an external MCP client (e.g., another editor or tool) needs to interact with a JetBrains IDE instance

### Migration & Deprecation Notes
- This repository is no longer maintained.
- Its core functionality is built into all IntelliJ-based IDEs as of version **2025.2**.
- New and existing users should migrate to the built-in MCP functionality in JetBrains IDEs (see JetBrains official documentation on MCP servers for details).

### Pricing
- Open-source project hosted on GitHub
- No licensing or pricing details are specified in the provided content; typically used free of charge as an open-source integration.