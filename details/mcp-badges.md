### MCP Badges

**Description**  
A collection of reusable, embeddable badges for Model Context Protocol (MCP) projects, allowing maintainers to indicate MCP support and capabilities in READMEs and documentation.

---

#### Features
- **Multiple badge types**  
  - `default` – generic MCP badge.  
  - `server` – indicates an MCP server.  
  - `client` – indicates an MCP client.  
  - `dev` – for development-related or ecosystem tooling.

- **Configurable parameters**  
  - `status` (for `default` badges) – e.g. `on`, `off` to show MCP enabled/disabled.  
  - `features` (for `server` and `client` badges) – list features supported by the MCP server or client (as indicated in the README).

- **Simple embed options**  
  - Direct image URLs from `https://badge.mcpx.dev`.  
  - Markdown image syntax examples.  
  - HTML `<img>` tag examples.

- **Hosted badge service**  
  - Badges are generated via a remote endpoint (`https://badge.mcpx.dev`) with query parameters for type, status, and features.

---

#### Usage Examples
- **Default badge**
  - Markdown: 
    ```md
    ![](https://badge.mcpx.dev "MCP")
    ```
  - HTML: 
    ```html
    <img src="https://badge.mcpx.dev" title="MCP" />
    ```

- **Default badge with status**
  - Enabled:
    ```md
    ![](https://badge.mcpx.dev?status=on "MCP Enabled")
    ```
    ```html
    <img src="https://badge.mcpx.dev?status=on" title="MCP Enabled" />
    ```
  - Disabled:
    ```md
    ![](https://badge.mcpx.dev?status=off "MCP Disabled")
    ```
    ```html
    <img src="https://badge.mcpx.dev?status=off" title="MCP Disabled" />
    ```

- **Server badge**
  - Markdown:
    ```md
    ![](https://badge.mcpx.dev?type=server "MCP Server")
    ```

*(Client and dev badges follow the same pattern using `type=client` or `type=dev`, and `features` where applicable.)*

---

#### Pricing
- Not specified; the project is provided as an open-source GitHub repository.

---

#### Links
- **Source code:** https://github.com/mcpx-dev/mcp-badges