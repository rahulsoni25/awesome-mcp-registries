<div align="center">

# Awesome MCP Registries [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated list of every place to publish, list and submit a [Model Context Protocol (MCP)](https://modelcontextprotocol.io) server** — the official registry, auto-indexing directories, submission-based registries, awesome lists and client galleries — **with how to submit to each**.

[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](./LICENSE)

🌐 **[English](./README.md)** · **[🇻🇳 Tiếng Việt](./README.vi.md)**

</div>

---

> **Why this list?** You finish building an MCP server and immediately hit the next question: **"where do I list it so people — and AI clients — can actually find it?"** The answer is scattered across blog posts and half-remembered tweets. This list gathers the destinations in one place, sorted by type, and tells you **how each one wants submissions** so you can go down the list. Every link is a real, working destination.

## Contents

- [Start Here — The Official Registry](#start-here--the-official-registry)
- [Auto-Indexing Directories (claim your listing)](#auto-indexing-directories-claim-your-listing)
- [Submission-Based Directories & Registries](#submission-based-directories--registries)
- [Awesome Lists (open a pull request)](#awesome-lists-open-a-pull-request)
- [Client Galleries & Marketplaces](#client-galleries--marketplaces)
- [Before You Submit — a Checklist](#before-you-submit--a-checklist)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

## Start Here — The Official Registry

Do this first: most other directories are downstream of the official registry and mirror or link back to it.

- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — The **official**, canonical MCP Registry. You publish with the `mcp-publisher` CLI (`mcp-publisher login` then `mcp-publisher publish`) using a `server.json` manifest that describes your server, packages and remotes.
- [registry.modelcontextprotocol.io](https://registry.modelcontextprotocol.io) — The live registry API that serves the published entries (browse/consume programmatically).
- [MCP Registry docs](https://modelcontextprotocol.io/registry) — Official documentation on the registry, `server.json` and the publishing flow.
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — The reference-servers repository; a PR here is the path for reference / notable community servers.

## Auto-Indexing Directories (claim your listing)

These crawl public GitHub and hosted endpoints automatically — you mainly need to make your repo discoverable and then **claim ownership** of the listing.

- [Glama](https://glama.ai/mcp/servers) — Large registry + inspector that auto-indexes open-source servers from GitHub, extracts every tool/schema/annotation, and assigns a quality score. Claim your server to manage its listing and badge.
- [PulseMCP](https://www.pulsemcp.com/) — Actively maintained directory with fast updates and strong support for remote HTTP servers. Submit at [pulsemcp.com/submit](https://www.pulsemcp.com/submit).
- [mcp.so](https://mcp.so/) — One of the largest, high-traffic MCP directories. Submit via the web form at [mcp.so/submit](https://mcp.so/submit).

## Submission-Based Directories & Registries

These expect an explicit submission — a web form, a CLI publish, or a GitHub connect flow.

- [Smithery](https://smithery.ai/) — Popular registry used by many developers; publish via the `smithery` CLI or connect a GitHub repo (declare transport, e.g. `http`).
- [Cursor Directory](https://cursor.directory/mcp) — MCP directory for the large Cursor editor community; submit via its web form.
- [mcpservers.org](https://mcpservers.org/) — Lightweight community directory; quick web / GitHub submission.
- [Fleur](https://www.fleurmcp.com/) — App-store-style marketplace for MCP; submit your server for listing.
- [mcp.run](https://mcp.run/) — Hosted registry/runtime for MCP "servlets"; publish to make servers installable.

## Awesome Lists (open a pull request)

GitHub awesome lists are PR-based and give strong backlinks. Read each list's `CONTRIBUTING` first — several require a specific one-line format (and some server catalogs require a badge/emoji per entry).

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — The canonical, largest awesome list of MCP servers. Server entries require `owner/repo` link, a Glama score badge and a language emoji; open a PR from the correct fork of *this* network.
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) — Another widely referenced awesome list (a separate GitHub network from the one above).
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) — A large early list (archived / read-only — historical reference).
- [AIAnytime/Awesome-MCP-Server](https://github.com/AIAnytime/Awesome-MCP-Server) — Actively maintained catalog with category sections (e.g. commerce, travel & logistics).
- [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers) — Very large, categorized awesome list that accepts server PRs.
- [MobinX/awesome-mcp-list](https://github.com/MobinX/awesome-mcp-list) — A concise, curated list of MCP servers.

## Client Galleries & Marketplaces

Some MCP *clients* ship their own in-app gallery or extension store — getting listed there puts your server in front of that client's users.

- [VS Code MCP](https://code.visualstudio.com/mcp) — Visual Studio Code's MCP support and curated server gallery.
- [Cursor Directory](https://cursor.directory/mcp) — Doubles as the Cursor editor's in-context MCP gallery.

## Before You Submit — a Checklist

Have these ready so any form or PR goes smoothly:

- [ ] A **public GitHub repo** with a clear README (bilingual is a plus).
- [ ] A [`server.json`](https://modelcontextprotocol.io/registry) manifest describing your server, packages and/or remotes.
- [ ] A **live endpoint** (for remote servers, a Streamable HTTP URL that responds) or an installable package.
- [ ] A **one-line description**, a category, and a few tags.
- [ ] A square logo (≥ 512×512 PNG) for directories that show one.
- [ ] **Verify your server first** with a conformance smoke test so you don't submit a broken endpoint — e.g. [mcp-conformance](https://github.com/tuanone123/mcp-conformance) (`npx mcp-conformance <url>`) or the official [MCP Inspector](https://github.com/modelcontextprotocol/inspector).
- [ ] Optional: an [`llms.txt`](https://llmstxt.org/) for AI crawlers.

## Related Awesome Lists

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — The canonical list of MCP servers themselves.
- [awesome-mcp-testing](https://github.com/tuanone123/awesome-mcp-testing) — Tools to test, evaluate and validate MCP servers before you ship them.
- [awesome-mcp-devtools](https://github.com/punkpeye/awesome-mcp-devtools) — Dev tools, SDKs and libraries for building MCP servers.
- [Model Context Protocol](https://modelcontextprotocol.io) — The official protocol site and documentation.

## Contributing

Contributions welcome — see [CONTRIBUTING.md](./CONTRIBUTING.md). In short: **the destination must be real and the link must work (HTTP 200)**, it must genuinely be a place to publish/list/submit an MCP server, one item per pull request in the right section, with a one-line factual note on *how to submit*. Add it to both `README.md` and `README.vi.md`.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](./LICENSE) — released under [CC0 1.0 Universal](./LICENSE). To the extent possible under law, the contributors have waived all copyright and related rights to this list. Each listed destination keeps its **own** terms — always check the source before use.
