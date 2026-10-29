# CLAUDE.md

This repository is the `vasilesk` Claude Code marketplace. It holds no plugins itself: `.claude-plugin/marketplace.json` lists plugins that live in their own repositories.

## Adding a plugin

- Add an entry to `plugins` with `source: {"source": "github", "repo": "vasilesk/<repo>"}`, a `description` matching the plugin's own `plugin.json`, and a `category`.
- Do not set `version` in the entry: the plugin's `plugin.json` is the single source of the version, and a value here would go stale.
- Do not pin `ref`/`sha` unless a plugin needs it: without them users get the plugin repository's default branch, so a plugin release needs no change here.
- Add the plugin to the table in `README.md`.
- Run `claude plugin validate .` before pushing.
