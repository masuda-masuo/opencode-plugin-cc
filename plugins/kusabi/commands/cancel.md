---
description: Cancel an active opencode job
argument-hint: '[job-id]'
disable-model-invocation: true
allowed-tools: Bash(node:*)
---

Cancel an opencode job through the companion runtime.

Raw slash-command arguments:
`$ARGUMENTS`

Run:
```bash
node "${CLAUDE_PLUGIN_ROOT}/scripts/kusabi-companion.mjs" cancel "$ARGUMENTS"
```

Return the command stdout verbatim, exactly as-is.
