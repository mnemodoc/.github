## mnemodoc

Open-source tooling for **local, private AI** — run document intelligence on your own machine and send nothing to the cloud unless you choose to.

The flagship is **[mnemodoc-server](https://github.com/mnemodoc/mcp-server)**: an MCP server that indexes your project documentation with Ollama embeddings and serves hybrid (semantic + keyword) search to Claude Code, Cursor, Zed and any MCP client. One static binary, no runtime dependencies, your data never leaves the box.

### Projects

| Repo | What it is |
|---|---|
| [mcp-server](https://github.com/mnemodoc/mcp-server) | The MCP server — local doc indexing & hybrid search (Crystal) |
| [zed-mnemodoc](https://github.com/mnemodoc/zed-mnemodoc) | Zed extension — wires the server into Zed's AI assistant |
| [homebrew-tap](https://github.com/mnemodoc/homebrew-tap) | `brew install mnemodoc/tap/mnemodoc-server` |
| [vfox-mnemodoc-server](https://github.com/mnemodoc/vfox-mnemodoc-server) | mise / vfox plugin |

### Philosophy

Local when privacy demands it, cloud when it's simpler or cheaper — the skill is knowing which. mnemodoc is the proof for the hard half: AI that runs entirely on your own infrastructure.

Maintained by [Nicolas Rodriguez](https://github.com/n-rodriguez).