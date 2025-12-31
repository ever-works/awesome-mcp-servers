# Google Directory MCP Server

**Category:** Cloud & DevOps MCP Servers  
**Brand:** Google Workspace  
**Slug:** google-directory-mcp-server

## Overview
The Google Directory MCP Server provides MCP-based access to Google Workspace Directory, enabling management of domain users, groups, and group memberships directly from compatible MCP clients.

## Features
- **MCP-based Google Directory integration**
  - Connects Google Workspace Directory to MCP-compatible clients via a static server URL (`https://mcp.pipedream.net/v2`).
  - Authentication handled when adding the server to an MCP-enabled application.

- **User management**
  - **List Users**: Retrieve a list of directory users in your Google Workspace domain.
  - **Get User**: Fetch detailed information about a specific user.
  - **Create User**: Create new users in the directory.

- **Group management**
  - **List Groups**: Retrieve a list of directory groups.
  - **Get Group**: Fetch detailed information about a specific group.
  - **Create Group**: Create new groups in the directory.

- **Group membership management**
  - **Add Member to Group**: Add users or other members to a specified group.

- **Tooling model**
  - Exposes 7 actions as MCP tools for use within compatible chat or automation clients.

## Use Cases
- Centralized management of Google Workspace users and groups from an MCP client.
- Automating user provisioning and group creation.
- Managing group memberships programmatically via MCP tools.

## Pricing
Pricing information is not specified in the provided content.

## Links
- Source / App Page: https://mcp.pipedream.com/app/google_directory
- MCP Server URL: `https://mcp.pipedream.net/v2`
- Action Documentation:
  - List Users: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/list-users/list-users.mjs
  - List Groups: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/list-groups/list-groups.mjs
  - Get User: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/get-user/get-user.mjs
  - Get Group: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/get-group/get-group.mjs
  - Create User: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/create-user/create-user.mjs
  - Create Group: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/create-group/create-group.mjs
  - Add Member to Group: https://github.com/PipedreamHQ/pipedream/blob/master/components/google_directory/actions/add-member-to-group/add-member-to-group.mjs

## Media
- Brand Logo: https://ssl.gstatic.com/docs/doclist/images/drive_2022q3_32dp.png
- Image: https://workspace.google.com/static/img/products/admin/admin-hero.png
