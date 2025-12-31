## Mastodon MCP Server

**Description**  
An MCP (Model Context Protocol) server integration for Mastodon that allows MCP-compatible clients (such as chat or AI assistants) to interact with the decentralized social network. It supports actions like posting statuses and retrieving various Mastodon timelines and account data.

**Category**  
- Messaging MCP Servers

**Tags**  
- Social media  
- Decentralized  
- Messaging

**Integration & Configuration**  
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- Add this URL as an MCP server in any supported client; authentication happens when the server is added.  
- Works with multiple chat / MCP clients (configured per client in their settings).  

**Features**  
- **MCP Server Endpoint**  
  - Single static URL (`https://mcp.pipedream.net/v2`) usable across all compatible clients.  
  - Authentication handled when adding the server to the application.

- **Available Tools (Actions)**  
  The Mastodon MCP Server exposes Mastodon API operations as tools/actions for MCP clients. From the page and linked components:
  - **Get Accounts Following**  
    - Retrieve the accounts that a given Mastodon account is following.
  - **View Single Status**  
    - Obtain detailed information about a specific status/post.
  - **View Public Timeline**  
    - View public statuses across the server or network.
  - **View List Timeline**  
    - View statuses contained in a specific Mastodon list.
  - **View Home Timeline**  
    - View statuses from users that the authenticated account follows.
  - **View Hashtag Timeline**  
    - View public statuses containing a specified hashtag.
  - **Unpin Status from Profile**  
    - Remove (unfeature) a previously pinned status from the top of the profile.
  - **Unmute a Conversation**  
    - Resume receiving notifications for a conversation thread that was muted.
  - **Undo Favorite of a Status**  
    - Remove a status from the account’s favourites list.
  - **Undo Boost of a Status**  
    - Undo a reshare (boost) of a status.
  - **Undo Bookmark of a Status**  
    - Remove a status from the account’s private bookmarks.
  - **Post Status**  
    - Publish a new status with configurable parameters (e.g., content and other Mastodon options exposed by the underlying action).
  - **Post Multiple Statuses**  
    - Publish multiple statuses in sequence where subsequent statuses are posted as replies to the first, effectively creating a thread.
  - **Pin Status to Profile**  
    - Feature one of the account’s own public statuses at the top of the profile.

> Note: The page states there are **21 actions available as tools**; only the actions explicitly listed in the provided content are enumerated above. Additional actions exist but are not detailed in the given text.

**Pricing**  
- Not specified in the provided content.