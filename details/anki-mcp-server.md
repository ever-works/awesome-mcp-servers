## Anki MCP Server

**Type:** MCP server for Anki  
**Source:** [GitHub – scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server)  
**License:** MIT  
**Works with:** Anki Desktop + [Anki-Connect add‑on](https://foosoft.net/projects/anki-connect/)

### Description
Anki MCP Server is a Model Context Protocol (MCP) server that connects locally running Anki to LLMs or MCP-compatible clients. It enables querying, reviewing, and creating spaced-repetition flashcards by interacting directly with Anki decks and cards through Anki-Connect.

### Features
- **MCP server for Anki**  
  - Implements an MCP server that exposes Anki functionality to LLMs or other MCP-aware tools.

- **Anki desktop integration**  
  - Connects to a locally running Anki instance.  
  - Requires the Anki-Connect add-on to be installed and enabled.

- **Search resources (read-only card access)**  
  - `anki://search/deckcurrent`  
    - Returns all cards from the current deck.  
    - Equivalent to the `deck:current` search in Anki.
  - `anki://search/isdue`  
    - Returns cards that are in review or learning and waiting to be studied.  
    - Equivalent to the `is:due` search in Anki.
  - `anki://search/isnew`  
    - Returns all unseen (new) cards.  
    - Equivalent to the `is:new` search in Anki.

- **Tools (card modification & creation)**  
  - `update_cards`  
    - Marks cards with given card IDs as answered.  
    - Applies an ease score for each card between `1` and `4` corresponding to Anki’s again–easy scale:  
      - `1` – Again  
      - `2` – (intermediate ease)  
      - `3` – (intermediate ease)  
      - `4` – Easy  
    - **Input:**  
      - `answers` (array): list of objects with:  
        - `cardId` (number) – ID of the card.  
        - `ease` (number) – ease rating from 1–4.
  - `add_card`  
    - Creates a new card in Anki (details of fields/parameters are defined in the implementation via Anki-Connect).

- **Spaced-repetition aware**  
  - Operates directly on Anki’s spaced-repetition data (due/new/review cards, ease scores), allowing LLMs to participate in card review flows.

### Requirements
- Anki Desktop installed and running locally.  
- Anki-Connect add-on installed in Anki.

### Pricing
- **Open-source** under the MIT License.  
- **Cost:** Free to use and self-host.