# Chroma MCP Server

**Description**

Chroma is an MCP-compatible vector database server that exposes Chroma’s vector database capabilities (semantic document search, metadata filtering, and document management) over the Model Context Protocol, with persistent on-disk storage.

---

## Features

- **MCP server implementation**  
  - Implements a Model Context Protocol (MCP) server for use with MCP-compatible clients (e.g., Claude Desktop).  
  - Exposes vector database operations via standardized MCP tools and resources.

- **Vector database backed by Chroma**  
  - Uses the Chroma vector database as the underlying storage and search engine.  
  - Supports semantic similarity search over stored documents.

- **Persistent storage**  
  - Documents and vector data are stored on disk for persistence across restarts.  
  - Default data directory: `src/chroma/data`.

- **Document management (CRUD tools)**  
  - `create_document`  
    - Creates a new document in the vector store.  
    - Parameters: `document_id`, `content`, `metadata`.  
  - `read_document`  
    - Retrieves a document by its ID.  
    - Parameters: `document_id`.  
  - `update_document`  
    - Updates an existing document’s content and/or metadata.  
    - Parameters: `document_id`, `content`, `metadata`.  
  - `delete_document`  
    - Deletes a document from the store.  
    - Parameters: `document_id`.  
  - `list_documents`  
    - Lists stored documents with basic pagination.  
    - Parameters: `limit`, `offset`.

- **Search operations**  
  - `search_similar`  
    - Performs semantic similarity search against stored documents.  
    - Parameters:  
      - `query` – text query to embed and search.  
      - `num_results` – number of similar results to return.  
      - `metadata_filter` – filter results by document metadata.  
      - `content_filter` – filter results by document content.

- **Metadata and content filtering**  
  - Search can be constrained by metadata fields (e.g., tags, types) using `metadata_filter`.  
  - Additional content-based constraints can be applied via `content_filter`.

- **Resource-based document storage**  
  - Documents are exposed through MCP resources mapped to Chroma’s storage.  
  - Resource path: `src/chroma/data`.

- **Error handling**  
  - Provides explicit error messages for common failure cases, including:  
    - `Document already exists [id=X]`  
    - `Document not found [id=X]`  
    - `Invalid input: Missing document_id or content`  
    - `Invalid filter`  
    - `Operation failed: [details]`.

- **Development-friendly project structure**  
  - Standard Python project layout with `pyproject.toml`.  
  - Includes `.gitignore`, version pinning via `.python-version`, and contribution guidelines (`CONTRIBUTING.md`).

---

## Configuration

- **Claude Desktop integration**  
  Add the server configuration to your Claude Desktop config file:
  - **Windows**:  
    `C:\Users\<username>\AppData\Roaming\Claude\claude_desktop_config.json`
  - **macOS**:  
    `~/Library/Application Support/Claude/claude_desktop_config.json`

- **Data storage location**  
  - Default on-disk data directory:  
    - `src/chroma/data`

---

## Pricing

- Open-source, self-hosted GitHub project.  
- No pricing plans or paid tiers are specified in the available content.