# Markdownify MCP Server

Model Context Protocol (MCP) server that converts a wide range of files and web content into clean Markdown for easier LLM consumption.

Source: [GitHub – zcaceres/markdownify-mcp](https://github.com/zcaceres/mcp-markdownify-server)

## Features

- **MCP-compatible server**  
  - Implements the Model Context Protocol so tools/clients that support MCP can call it as a content-conversion backend.

- **Multi-format to Markdown conversion**  
  Converts diverse inputs into Markdown, including:
  - PDFs  
  - PPTX presentations  
  - HTML and general web content  
  - YouTube transcripts  
  - Images (converted via OCR or similar pipeline, as exposed by the server)  
  - Audio files (converted via transcription pipeline, as exposed by the server)  
  - Other file types supported by the tools configured in the server ("and more" as documented in the repo).

- **Designed for LLM workflows**  
  - Produces Markdown specifically optimized for large language model consumption and downstream processing.

- **Scripted setup and tooling**  
  - `setup.sh` for Unix-like environments.  
  - `setup.bat` present for Windows-oriented setup work (Windows support is still being validated).  
  - Dockerfile for container-based deployment.

- **Polyglot tooling and configuration**  
  - Python project configuration (`pyproject.toml`, `.python-version`, `uv.lock`).  
  - Node/TypeScript tooling (`package.json`, `pnpm-lock.yaml`, `tsconfig.json`).  
  - Suitable for integration into different development and deployment environments.

- **Open-source development**  
  - Public Git repository with commit history and issue tracking.  
  - Community contributions invited, including help improving Windows support.

## Notes / Platform Support

- The maintainer is actively seeking help to fully validate and finalize **Windows support**. PRs exist, but Windows testing is limited; behavior on Windows may be experimental or incomplete.

## Pricing

- **Open-source project** hosted on GitHub.  
- Usage rights and any redistribution conditions are defined by the repository’s `LICENSE` file (no separate pricing plans are listed).