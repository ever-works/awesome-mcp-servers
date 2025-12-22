## Dataset Viewer

**Type:** MCP server  
**Category:** mcp-server-directories-lists  
**Source:** https://github.com/privetin/dataset-viewer

### Description
Dataset Viewer is an MCP server for interacting with the Hugging Face Dataset Viewer API, enabling browsing and analysis of datasets hosted on the Hugging Face Hub.

### Features
- Integrates with the [Hugging Face Dataset Viewer API](https://huggingface.co/docs/dataset-viewer) to work with datasets on the Hugging Face Hub.
- Exposes datasets as MCP resources using the `dataset://` scheme.
- Provides multiple tools for dataset inspection and interaction (all callable via MCP):
  - **`validate`**
    - Parameters: `dataset`, `auth_token`
  - **`get_info`**
    - Parameters: `dataset`, `auth_token`
  - **`get_rows`**
    - Parameters: `dataset`, `config`, `split`, `page`, `auth_token`
  - **`get_first_rows`**
    - Parameters: `dataset`, `config`, `split`, `auth_token`
  - **`get_statistics`**
    - Parameters: `dataset`, `config`, `split`, `auth_token`
  - **`search_dataset`**
    - Parameters: `dataset`, `config`, `split`, `query`, `auth_token`
  - **`filter`**
    - Parameters: `dataset`, `config`, `split`, `where`, `orderby`, `page`, `auth_token`
  - **`get_parquet`**
    - Parameters: `dataset`, `auth_token`

### Installation
The repository README contains sections for **Prerequisites** and **Setup**, but specific installation commands or steps are not included in the provided content.

### Configuration
- **Environment variables**:
  - `HUGGINGFACE_TOKEN` – used to authenticate against the Hugging Face Hub.

### Integration
- **Claude Desktop integration**:
  - Add the MCP server configuration to your Claude Desktop config file.
  - Windows: `%APPDATA%\Claude\claude_desktop_config.json`
  - macOS: `~/Library/Application Support/Claude/claude_desktop_config.json`

*(The exact JSON configuration snippet is not present in the provided content.)*

### Pricing
- Licensed under the **MIT License** (see `LICENSE` in the repository).  
- Open-source and free to use; no paid plans or pricing tiers are mentioned in the provided content.