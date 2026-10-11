# Contributing to FleekDash

- **One change per PR.** Extensions/snippets ship one item per PR — CI must pass first.
- **English only** in code, comments and docs on public repos.
- **Manifests are the contract.** A `fleekdash.json` must validate against the vendored schema (`schema/fleekdash-manifest.schema.json` in each repo).
- **Don't break saved state.** Renaming setting fields or option keys orphans user data — declare explicit `option_key` and keep ids stable.
- **Docs:** dev-facing docs live next to the code they describe, in English.

Review bots (Qodo and friends) may commit fixes onto PR branches — treat those commits as normal code: review them, don't rubber-stamp.
