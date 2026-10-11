# FleekDash

The WordPress admin operating layer — a React-powered hub that replaces wp-admin with a modern workspace: posts, ecommerce, integrations, AI and extensible apps.

## Build on FleekDash

| Repo | What it is |
|---|---|
| [`fleekdash/extensions`](https://github.com/fleekdash/extensions) | Open-source installable extensions — one dir per WP plugin, zipped by release CI |
| [`fleekdash/snippets`](https://github.com/fleekdash/snippets) | Community fleeklets — drop-in PHP snippets for `fleeklets/` |
| [`fleekdash/extension-starter`](https://github.com/fleekdash/extension-starter) | Living scaffold — clone it, `pnpm install`, ship a real extension |

Everything in these repos is GPLv2+ — copy, extend, and ship your own. Extensions declare themselves with a `fleekdash.json` manifest and talk to the host through the typed [`@fleekdash/contracts`](https://github.com/fleekdash/extension-starter) surface (iframe + SDK runtime).

## Contributing

PRs welcome on all public repos. Keep docs and code comments in English, follow each repo's CONTRIBUTING, and run its CI gates locally before pushing.
