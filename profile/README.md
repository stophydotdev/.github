<div align="center">
  <a href="https://stophy.dev">
    <img src="https://raw.githubusercontent.com/stophydotdev/stophy/main/assets/logo.png" alt="Stophy logo" height="96">
  </a>

  <h3>Search, read, and act on the web.</h3>
  <p>One API gives AI agents the live web: search, any page as Markdown or JSON, and a cloud browser.</p>

  <a href="https://stophy.dev/signup">
    <img src="https://img.shields.io/badge/Get_started-4b5563?style=for-the-badge" alt="Get started">
  </a>
  <a href="https://docs.stophy.dev">
    <img src="https://img.shields.io/badge/Docs-4b5563?style=for-the-badge" alt="Docs">
  </a>
  <a href="https://docs.stophy.dev/api-reference/introduction">
    <img src="https://img.shields.io/badge/API_reference-4b5563?style=for-the-badge" alt="API reference">
  </a>
</div>

<br>

<div align="center">
  <a href="https://github.com/stophydotdev/stophy/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/stophydotdev/stophy" alt="License">
  </a>
  <a href="https://www.npmjs.com/package/stophy">
    <img src="https://img.shields.io/npm/dm/stophy?label=npm%20downloads" alt="npm downloads">
  </a>
  <a href="https://pypi.org/project/stophy/">
    <img src="https://img.shields.io/pypi/dm/stophy?label=pypi%20downloads" alt="PyPI downloads">
  </a>
  <a href="https://x.com/stophydotdev">
    <img src="https://img.shields.io/badge/follow-@stophydotdev-4b5563?logo=x" alt="Follow on X">
  </a>
</div>

---

## Why Stophy

An agent that needs the live web usually needs a search API, a scraper and a headless browser. Each has its own key, bill and failure modes. Stophy is one API, one key and one prepaid balance for all three.

Try it without a key:

```bash
npx -y @stophy/cli search "bun runtime" --limit 2
```

## What it does

| Feature | What it does |
| --- | --- |
| **Search** | The web, news, images, papers and YouTube in one call. |
| **Scrape** | Any page as Markdown, HTML, links, a screenshot or JSON. Site parsers for Amazon, Reddit, LinkedIn, Google Maps and more are chosen by URL. |
| **Crawl and Map** | List a site's URLs, or read the whole site in the background. |
| **Extract** | The fields you name, each checked against the page. |
| **Parse** | PDF, Word, Excel, PowerPoint and HTML files, or a picture of text, to Markdown. |
| **Browser** | Cloud browser sessions you drive over CDP, and tasks that click through a site from a goal in plain words. |
| **Monitors** | Watch pages, a site section or a search on a schedule. Each change comes with its diff. |

## Use it from

| From | Install |
| --- | --- |
| TypeScript | `npm install stophy` |
| Python | `pip install stophy` |
| Rust | the [`stophy` crate](https://github.com/stophydotdev/stophy/tree/main/crates/stophy) |
| A terminal or a script | `curl -fsSL https://stophy.dev/install \| bash` |
| An agent over MCP | `stophy mcp` |
| Claude Code, Cursor, Gemini CLI | `npx skills add stophydotdev/stophy` |

## Repositories

- **[stophy](https://github.com/stophydotdev/stophy)**: the SDKs, the CLI, the MCP server, the agent skills and the docs.
- **[mcp](https://github.com/stophydotdev/mcp)**: Stophy's hosted MCP server. The source lives in `stophy`.
- **[sirathic](https://github.com/stophydotdev/sirathic)**: a free Islamic answering engine. Answers cite the Quran, graded hadith and scholars' rulings.

## Pricing

Pay as you go in dollars, and the balance never expires. See [pricing](https://docs.stophy.dev/account/pricing).

## Also from us

**[AgentFS](https://github.com/stophydotdev/agentfs)** is cloud storage for AI agents.
