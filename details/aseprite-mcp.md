# aseprite-mcp

**Category:** media-processing-mcp-servers  
**Brand:** aseprite  
**Source:** https://github.com/diivi/aseprite-mcp

An MCP server that connects to the Aseprite API to programmatically create and edit pixel art sprites from model-generated instructions.

![aseprite-mcp demo](https://github.com/diivi/aseprite-mcp/raw/HEAD/assets/aseprite-mcp-demo.gif)

---

## Features

- **MCP server for Aseprite**  
  - Exposes Aseprite functionality through the Model Context Protocol (MCP), enabling tools/LLMs to drive sprite creation and editing.

- **Programmatic sprite creation & editing**  
  - Uses the Aseprite API to generate and modify pixel art sprites according to structured, model-provided instructions.

- **Aseprite integration**  
  - Designed specifically to work with Aseprite, leveraging its scripting/API layer for pixel-art workflows.

- **Dockerized deployment**  
  - Includes `Dockerfile`, `docker-compose.yml`, and helper scripts (`build-docker.sh`, `build-docker.ps1`) for container-based setup and running.

- **Environment-based configuration**  
  - Provides `sample.env` to configure environment variables needed to run the server and connect to Aseprite.

- **Python-based implementation**  
  - Managed with `pyproject.toml` and `requirements.txt` for dependency and environment management.

- **CI / workflows setup**  
  - `.github/workflows` directory indicates automation for testing/building via GitHub Actions.

- **Testing support**  
  - `tests` directory for automated tests of the MCP server behavior.

- **Contribution guidelines**  
  - `PR_DETAILS.md` file describing expectations for pull requests and contributions.

- **Docker setup documentation**  
  - `DOCKER.md` and `DOCKER_SETUP_SUMMARY.md` provide instructions and a summary for building and running the server with Docker.

---

## Technical Details

- **Language:** Python  
- **Deployment options:** Local Python environment or Docker/containerized setup  
- **Integration target:** Aseprite API (pixel art / sprite editor)

---

## Pricing

- Not specified in the provided content. The repository appears to be open-source; refer to the LICENSE file in the repo for usage terms.

---

## License

- A `LICENSE` file is present in the repository; consult it directly for the exact license and conditions.
