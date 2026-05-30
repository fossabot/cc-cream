---
description: Remove cc-cream's statusLine wiring from settings.json. Run this BEFORE /plugin uninstall cc-cream (this command lives in the plugin and disappears with it).
allowed-tools: Bash(node:*)
---

Removing cc-cream's status-bar wiring from `~/.claude/settings.json`. Run `/plugin uninstall cc-cream` afterwards to drop the plugin. Already removed it? The uninstaller still lives in the cache — run `node ~/.claude/plugins/cache/cc-cream/cc-cream/<version>/src/install.js --uninstall` (npm-free, always present); `npx -y -p cc-cream cc-cream-setup --uninstall` also works, but only once the published version has aged past npm's safe-chain guard.

!`node ${CLAUDE_PLUGIN_ROOT}/src/install.js --uninstall $ARGUMENTS`
