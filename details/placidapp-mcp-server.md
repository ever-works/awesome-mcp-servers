## Placid.app MCP Server

**Description**  
An open-source MCP server for generating image and video creatives from Placid.app templates, enabling AI agents and MCP-compatible hosts to create marketing visuals programmatically.

---

### Features
- Generate **image creatives** using Placid.app templates.  
- Generate **video creatives** using Placid.app templates.  
- Designed to run in **MCP-compatible hosts**, so tools and agents can call it as an MCP server.  
- Enables **programmatic creation of marketing visuals** driven by AI agents or other MCP tools.  
- Uses template-based workflows via **Placid.app** (template IDs and data are sent to Placid to render assets).  
- Includes a `docs` directory for additional usage and configuration documentation (in-repo).  
- Includes a `tests` directory and Jest configuration (`jest.config.js`) for automated testing.  
- TypeScript/JavaScript-based project structure (`src`, `tsconfig.json`, `package.json`).  
- Example environment configuration via `.env.example` (indicates configuration through environment variables).  
- Dockerfile provided for **containerized deployment**.  
- `smithery.yaml` included for MCP/server metadata and integration with tools like Smithery.

---

### Pricing
- Not specified in the provided content.

---

### Technical Details
- Implementation: Node.js / TypeScript project structure (based on `package.json` and `tsconfig.json`).  
- Testing: Jest configuration present for running automated tests.  
- Configuration: Uses environment variables (example in `.env.example`).  
- Deployment: Includes a `Dockerfile` for building and running the MCP server in containers.

---

### License
- A `LICENSE` file is present in the repository; the specific license type is not specified in the provided content.

---

### Links
- Source code: https://github.com/felores/placid-mcp-server