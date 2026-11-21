# deed.page

deed.page is a static host built for agents. Its hosted MCP server lets an assistant put HTML, a built site folder, a report or a small browser game at a public HTTPS URL without the user creating an account first.

## Connection

- Hosted endpoint: `https://deed.page/mcp`
- Transport: Streamable HTTP
- Authentication: none to publish. The first `publish_site` call returns an owner token once; later calls that change or remove that owner's sites pass it as a Bearer header or a `token` argument.
- Setup documentation: https://deed.page/docs
- MCP Registry: page.deed/deed-page
- Agent skill: https://github.com/f-o-x11/deed-page-skill

## What it can do

- Publish a files map to `https://<slug>.deed.page/`, or replace or merge files on a slug the token owns
- List retained versions of a site and restore an older one
- Delete a site, list the token's sites, and rotate or revoke the token
- Attach a custom domain and check its DNS and certificate status
- Read cookieless page-view counts and contact-form submissions for an owned site

31 tools in total, 11 of them read-only. The free plan allows 25 sites of up to 25 MB each; paid plans raise those limits.

The hosted service is proprietary.
