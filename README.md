# computerreinvention.com

The computer reinvention experiments site, served via GitHub Pages at
[computerreinvention.com](https://computerreinvention.com).

## Structure

| Path | What | Owned by |
|---|---|---|
| `/` | Experiments index (hub) | this repo |
| `/trie/` | trie story page | **deployed from [`trie`](https://github.com/computer-reinvention/trie)** — `landing/` is synced here by its `pages.yml` workflow. Do not edit `trie/` in this repo; changes will be overwritten. |
| `/agm/` | AGM (trie-app) page | this repo |
| `/flowpilot/` | flowpilot page | this repo |
| `/soren/` | soren page | this repo |
| `/multiclaude/` | multiclaude page | this repo |
| `/chainfactory/` | ChainFactory page | this repo |

Everything is dependency-free static HTML/CSS/JS. `site.css` is shared by the
hub; each project page is self-contained and carries its own design language.
