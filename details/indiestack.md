# IndieStack

**Category:** Search & Discovery MCP Servers
**Brand:** IndieStack

An MCP server for searching and discovering 130+ curated indie SaaS tools directly from AI coding assistants. IndieStack lets developers find alternatives to big-tech tools, compare pricing, and discover bootstrapped software without leaving their editor.

---

## Features

- Search 130+ curated indie SaaS tools by name, category, pricing, or feature
- Browse tools by category (analytics, auth, databases, email, hosting, payments, etc.)
- Compare indie alternatives to mainstream services
- Get detailed tool information including pricing, tech stack, and indie status
- Works with Claude Desktop, Cursor, VS Code, and any MCP-compatible client
- Available as a Python package via PyPI

---

## Installation

Install from PyPI:

```bash
pip install indiestack
```

---

## Integration

Add to your MCP client configuration:

```json
{
  "mcpServers": {
    "indiestack": {
      "command": "python",
      "args": ["-m", "indiestack"]
    }
  }
}
```

---

## Links

- [GitHub Repository](https://github.com/Pattyboi101/indiestack)
- [PyPI Package](https://pypi.org/project/indiestack/)
