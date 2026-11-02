# ai-tools

Tools I use with AI coding agents.

## herdr-mods

Mods for the [Herdr](https://herdr.dev) app. Each folder is one package: `mods/<name>/`, a `RECIPE.md` an agent can rebuild it from, a `preview.png`, and a `keys.json` when the mod needs keys.

- [mod-manager](herdr-mods/mod-manager): install, update, remove and AI-edit Herdr mods from one dialog (`ctrl-shift-m`).
- [files-changes-colorized](herdr-mods/files-changes-colorized): Files and Changes panels with colored file icons and Git status colors.

To install one, ask your agent to read `~/.config/herdr-app/AGENTS.md` and add the folder. Mod Manager can also install either from its Marketplace tab.
