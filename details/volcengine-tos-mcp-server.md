# VolcEngine TOS MCP Server

A sample MCP (Model Context Protocol) server for VolcEngine Torch Object Storage (TOS) that lets LLMs explore and retrieve TOS objects via natural language.

- **Category:** File Management MCP Servers / Storage
- **Brand:** VolcEngine
- **Source:** https://github.com/dinghuazhou/sample-mcp-server-tos
- **Version:** v0.2.0
- **Use cases:** Search and access files, images, videos, and text stored in TOS from LLM-based applications.

## Features

### Natural-language access to TOS
- Manage and explore VolcEngine TOS resources through an MCP server.
- Query stored data using natural language prompts.
- Supports search and retrieval across multiple content types: video, image, and text.
- Integrates with VolcEngine cloud MCP products to build intelligent application scenarios.

### Tools (Capabilities)

#### 1. `list_buckets`
- **Type:** SaaS tool.
- Lists available TOS buckets in the connected VolcEngine account.
- Designed for quickly viewing all accessible TOS storage buckets.
- **Example prompt:** `列举火山引擎 TOS 的存储桶列表。`

#### 2. `list_objects`
- **Type:** SaaS tool.
- Lists objects within a specified TOS bucket.
- Each request returns some or all objects in a bucket (up to 1000 objects per call).
- Supports request parameters as filters to return a subset of objects (e.g., prefix/selection conditions).
- **Example prompt:** `列举火山引擎 TOS 的 example 桶下的对象。`

#### 3. `get_object`
- **Type:** SaaS tool.
- Retrieves a single object from TOS by bucket name and full object path.
- For text-like objects (e.g., plain text files, CSV files), returns the textual content directly.
- For binary objects (e.g., images, videos), returns Base64-encoded content suitable for downstream processing.
- **Example prompt:** `读取火山引擎 TOS 桶example下对象名为example.txt的文件内容`

### Platform compatibility
- Can be used from:
  - 方舟
  - Python environments
  - Cursor and similar MCP-capable clients

### Authentication & Configuration
- Uses VolcEngine credentials obtained from the VolcEngine management console.
- Authentication via access key ID, secret access key, and region; optional security token.
- Configuration through environment variables (e.g. in a `.env` file):

| Environment variable        | Description                                   | Default |
|-----------------------------|-----------------------------------------------|---------|
| `VOLCENGINE_ACCESS_KEY`     | VolcEngine account ACCESS KEY                 | -       |
| `VOLCENGINE_SECRET_KEY`     | VolcEngine account SECRET KEY                 | -       |
| `VOLCENGINE_REGION`         | VolcEngine TOS region                         | -       |
| `TOS_ENDPOINT`              | VolcEngine TOS endpoint                       | -       |
| `SECURITY_TOKEN`            | Optional VolcEngine security token            | -       |
| `TOS_BUCKETS`               | Optional: restrict to specific TOS buckets    | -       |

### Service activation (underlying TOS product)
- TOS service can be enabled via: https://console.volcengine.com/tos

## Pricing
- No pricing information is provided in the available content for this MCP server implementation.
- Underlying VolcEngine TOS usage is subject to VolcEngine’s own pricing (not detailed here).