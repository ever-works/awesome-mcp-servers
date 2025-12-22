# Cloudinary MCP Server

**Description**  
A Model Context Protocol (MCP) server that lets Claude Desktop and other MCP-compatible clients upload images and videos to Cloudinary and access their URLs and metadata.

## Features
- Upload images to Cloudinary from MCP-compatible clients (e.g., Claude Desktop)
- Upload videos to Cloudinary
- Retrieve Cloudinary asset URLs after upload
- Access uploaded asset metadata
- Works as a standalone MCP server that can be added to Claude Desktop configuration
- Uses your own Cloudinary account and API credentials

## Installation & Requirements
- **Requirements**: Node.js
- **Install via npx (recommended)**:
  - Navigate to the Claude configuration directory on your system, e.g.:
    - Windows: `C:\Users\NAME\AppData\Roaming\Claude`
    - macOS: `~/Library/Application Support/Claude/`
  - Alternatively, open via Claude Desktop: **Settings → Developer → Edit Config**
  - Add the Cloudinary MCP server configuration to your MCP settings file (see repository README for exact JSON/config snippet).
- **Developer installation**:
  - Clone the repository and install dependencies if you want to modify the server or contribute to its development (details in the repo’s `README.md`).

## Configuration
- Requires a Cloudinary account.
- Obtain your API credentials from the [Cloudinary Console](https://console.cloudinary.com/settings/api-keys).
- Add these credentials to the server configuration as described in the project documentation.

## Pricing
- No pricing information is provided in the repository content. The project is distributed as an open-source GitHub repository (see the `LICENSE` file in the repo for licensing details).