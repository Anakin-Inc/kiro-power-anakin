# Anakin Power for Kiro

Gives [Kiro](https://kiro.dev) live web data through [Anakin](https://anakin.io)'s hosted MCP server: scrape pages to markdown or structured JSON, search the web, run deep research, map and crawl sites, run pre-built Wire actions on hundreds of websites, monitor pages for changes, compare AI answer engines and drive a cloud browser.

## Install

1. In Kiro, open the **Powers** panel.
2. Choose **Add Custom Power → Import power from GitHub** and enter `https://github.com/Anakin-Inc/kiro-power-anakin`.
3. The first time Kiro uses an Anakin tool, it opens your browser to sign in to Anakin and approve access. There's no API key to copy. New accounts get 300 free credits, no card required.

## What's included

| File | Purpose |
|---|---|
| `plugin.json` | Power manifest ([Agent Plugins](https://agent-plugins.org) format) with the keywords that activate it |
| `mcp.json` | Connects to `https://mcp.anakin.io/mcp` (Streamable HTTP, OAuth 2.1 with dynamic client registration) |
| `skills/` | When and how to use each tool family |

| Skill | Covers |
|---|---|
| `anakin-web-data` | Scrape, map and crawl |
| `anakin-research` | Web search and deep research |
| `anakin-wire` | Pre-built actions on websites (Wire) |
| `anakin-monitoring` | Watching pages for changes |
| `anakin-browser` | Natural-language tasks in a cloud browser |

## Example prompts

- "Scrape https://example.com/pricing and summarize the plans."
- "Map docs.example.com and list every page under /api."
- "Research the top open-source vector databases and compare their licenses."
- "Watch https://example.com/changelog and tell me when it changes."

## Privacy

Anakin's [Connectors and Plugins Privacy Policy](https://anakin.io/connector-privacy) covers this power: what the tools collect, who receives it, how long it is kept and how to delete it. Tools that change something (Wire write actions, new monitors, browser tasks) are marked so Kiro asks before running them.

## Support

- Email: support@anakin.io
- Help center: https://anakin.io/support
- Docs: https://anakin.io/docs

## License

Apache-2.0. Skills are maintained in [Anakin-Inc/agent-skills](https://github.com/Anakin-Inc/agent-skills) and copied here.
