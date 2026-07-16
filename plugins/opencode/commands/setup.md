---
description: Check that opencode is installed and the local server can start
argument-hint: ''
disable-model-invocation: true
allowed-tools: Bash(node:*)
---

Check the opencode companion setup.

Run:
```bash
node "${CLAUDE_PLUGIN_ROOT}/scripts/opencode-companion.mjs" setup
```

Return the command stdout verbatim, exactly as-is.

If it reports that the opencode CLI is missing, tell the user to install it from https://opencode.ai and to authenticate a model provider with `opencode auth login` before using this plugin.
