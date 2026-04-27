# EnigmAgent MCP

EnigmAgent MCP is an encrypted local vault MCP server that resolves `{{PLACEHOLDER}}` secrets at runtime so API keys never appear in LLM prompts, logs, or context windows.

## Key Details
- **Name:** EnigmAgent MCP
- **Category:** Security / Credentials & Secrets MCP Servers
- **Provider / Brand:** Agnuxo1 (open source, MIT)
- **URL (repository):** https://github.com/Agnuxo1/enigmagent-mcp
- **npm:** https://www.npmjs.com/package/enigmagent-mcp
- **Glama:** https://glama.ai/mcp/servers/Agnuxo1/enigmagent-mcp (Security score A, build/test passed)
- **Use Case Focus:** Local credential isolation for AI agents; prevents secret leakage to LLM context.

## Features
- **AES-256-GCM encryption** with **Argon2id** key derivation for the local vault.
- **Runtime placeholder resolution** — agents write `{{API_KEY}}`, the MCP swaps the real value only at the moment of upstream tool execution.
- **Zero cloud, zero telemetry** — vault stays on the developer's machine.
- **One-line setup:** `npx enigmagent-mcp`.
- **MCP-compatible** — plugs into Claude Desktop, Cursor, Windsurf, VS Code MCP, and any MCP-capable client.
- **MIT licensed**, fully open source.

## Integration & Setup
- **Install:** `npx enigmagent-mcp` (no global install required)
- **Add to MCP client config** (e.g. `claude_desktop_config.json`):
  ```json
  {
    "mcpServers": {
      "enigmagent": { "command": "npx", "args": ["enigmagent-mcp"] }
    }
  }
  ```
- **Documentation:** README at https://github.com/Agnuxo1/enigmagent-mcp

## Pricing
Free and open source (MIT license).