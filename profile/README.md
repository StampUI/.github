# StampUI

**Source-owned UI blocks for React and Next.js.** Components install as real `.tsx` files in your repo through a CLI: no runtime dependency, no wrapper abstraction, no lock-in after install. Because the code lives in your repository, AI coding tools (Claude Code, Cursor, Copilot) can inspect, refactor, and extend it like code you wrote yourself.

```bash
npx stampui add hero-section
```

## Repositories

| Repo | What it is |
|------|------------|
| [ui](https://github.com/StampUI/ui) | The free component and block source: 94 MIT `.tsx` files (64 core components, 30 composed blocks), self-contained and CI-typechecked. Also home of the open [block manifest spec](https://github.com/StampUI/ui/blob/main/docs/block-manifest.md). |
| [cli](https://github.com/StampUI/cli) | The [`stampui`](https://www.npmjs.com/package/stampui) CLI: init, add, search, update (with a lock file, so copied code keeps an upgrade path). |
| [mcp](https://github.com/StampUI/mcp) | The [`@stampui/mcp`](https://www.npmjs.com/package/@stampui/mcp) MCP server: lets agents browse and stamp blocks from inside Claude Code, Cursor, and other MCP clients. |

## Open source and commercial

Everything in the public repos is MIT and stays MIT. StampUI also sells pro blocks and full-page templates at [stampui.com](https://stampui.com); that commercial catalog lives outside these repos and funds the maintenance of the free core.

## Get involved

- Browse the catalog and live previews at [stampui.com](https://stampui.com)
- Issues labeled [`good first issue`](https://github.com/StampUI/ui/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) are a solid starting point
- Questions and ideas: [Discussions](https://github.com/StampUI/ui/discussions)
- Security reports: support@stampui.com (see each repo's SECURITY.md)
