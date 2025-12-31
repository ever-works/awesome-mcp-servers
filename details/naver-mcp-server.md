# NAVER MCP Server

A Python-based MCP (Model Context Protocol) server for integrating NAVER OpenAPI search capabilities into MCP-compatible clients.

## Overview

NAVER MCP Server exposes NAVER OpenAPI as MCP tools, allowing applications like Claude Desktop or Cursor to search and retrieve various NAVER content types (blogs, news, books, images, shopping items, and more) directly through the MCP protocol.

## Prerequisites

- NAVER OpenAPI access (application required via: https://developers.naver.com/apps/#/register=datalab)

## Features

### General
- MCP server implementation wrapping NAVER OpenAPI
- Usable from MCP-compatible clients (e.g., Claude Desktop, Cursor)
- Open-source under MIT license

### NAVER MCP Tools

- **Blog Search**  
  Search blog posts on NAVER.

- **News Search**  
  Search news articles on NAVER.

- **Book Search**  
  Search books on NAVER.

- **Advanced Book Search**  
  Retrieve detailed book information using title or ISBN.

- **Adult Content Check**  
  Check whether a search term is classified as adult content.

- **Encyclopedia Search**  
  Search encyclopedia entries on NAVER.

- **Cafe Article Search**  
  Search articles within NAVER Cafes.

- **Q&A Search**  
  Search questions and answers on NAVER.

- **Local Search**  
  Search local information and places on NAVER.

- **Spelling Correction**  
  Correct spelling errors in provided text.

- **Web Search**  
  Search web pages on NAVER.

- **Image Search**  
  Search images on NAVER with filtering options.

- **Shopping Search**  
  Search shopping items on NAVER with filters.

- **Document Search**  
  Search documents on NAVER.

## Installation

The project can be installed and run as an MCP server, including from PyPI for:
- Claude Desktop (via `uv`)
- Cursor (via `uv`)
- Directly from source

(Refer to the project repository for exact commands and configuration.)

## Pricing

- Not specified (open-source MIT-licensed project; no pricing information provided).

## License

- MIT License