# APITemplate.io MCP Server

## Overview
APITemplate.io MCP Server is a Model Context Protocol (MCP) integration that exposes APITemplate.io’s image and PDF generation capabilities via a simple API endpoint (`https://mcp.pipedream.net/v2`). It enables automated creation and management of templated PDFs and images from JSON data within MCP-compatible applications.

## Features
- **Static MCP Server Endpoint**  
  - Single static server URL: `https://mcp.pipedream.net/v2`  
  - Works for all clients; authentication is handled when adding the server to your application

- **Account Connection & Configuration**  
  - Connect an APITemplate.io account via Pipedream  
  - Configure and manage linked accounts and clients  
  - Access basic account information through a dedicated tool

- **Document & Image Generation**  
  - **Create PDF**  
    - Generate PDF files using JSON data and a predefined APITemplate.io template  
    - Output delivered as a generated PDF resource accessible via CDN
  - **Create Image**  
    - Generate images (JPEG plus PNG) using JSON data and a predefined template  
    - Suitable for dynamic visual content (e.g., marketing images, social graphics, etc.)

- **Object Management**  
  - **List Generated Objects**  
    - Retrieve all generated PDFs and images associated with your account  
    - Useful for auditing, retrieval, and downstream automation
  - **Delete an Object**  
    - Delete a selected PDF or image from the CDN  
    - Marks the corresponding transaction as deleted in the system

- **Tooling / Actions (MCP Tools)**  
  - `List Generated Objects` – list all generated assets  
  - `Delete an Object` – remove a specific asset from CDN  
  - `Create a PDF` – generate PDF from JSON + template  
  - `Create an Image` – generate JPEG/PNG from JSON + template  
  - `Account Information` – fetch account-related details

## Category
- Media Processing MCP Servers

## Tags
- Document generation  
- Image generation  
- Automation

## Pricing
No pricing information is provided for the APITemplate.io MCP Server in the supplied content.