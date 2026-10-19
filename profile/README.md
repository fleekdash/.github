# FleekDash

The WordPress admin operating layer: a React powered hub that replaces
wp-admin with a modern workspace for posts, ecommerce, integrations, AI and
extensible apps.

## Build on FleekDash

Extending FleekDash is deliberately boring: an extension is a normal
WordPress plugin plus one `fleekdash.json` manifest. From there you get app
routes, settings screens, menu badges, modals, notifications and a typed SDK
over postMessage, all inside the FleekDash design system.

| Repo | What it is |
|---|---|
| [`fleekdash/extension-starter`](https://github.com/fleekdash/extension-starter) | The living scaffold: clone it, `pnpm install`, build, activate. Your first extension in about ten minutes. |
| [`fleekdash/devkit`](https://github.com/fleekdash/devkit) | A local dev canvas: a mock FleekDash host that answers the real SDK protocol, so you can iterate without a WordPress install. |
| [`fleekdash/extensions`](https://github.com/fleekdash/extensions) | The open source extension collection: one directory per installable WP plugin, shipped as release zips. |
| [`fleekdash/snippets`](https://github.com/fleekdash/snippets) | Community fleeklets: drop in PHP snippets for `wp-content/fleeklets/`. |

Start with the starter, prototype in the devkit, and browse the extensions
repo for real world examples. [`extensions/todo-system`](https://github.com/fleekdash/extensions/tree/main/extensions/todo-system)
is a full task manager that doubles as a live tour of every extension API
capability.

Everything in these repos is GPLv2+ or MIT: copy it, extend it, ship your own.

## Contributing

PRs are welcome on all public repos. Keep docs and code comments in English,
follow each repo's contributing notes, and run its CI gates locally before
pushing.
