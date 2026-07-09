---
description: Remove the claude-ig Instagram content skill and its agents from this machine
---

Run the official claude-ig uninstaller to remove everything `/ig-install` added:

```bash
curl -fsSL https://raw.githubusercontent.com/NicoJunk/claude-ig/main/uninstall.sh | bash
```

This deletes the `ig` and `ig-*` skill folders from `~/.claude/skills/` and the `ig-*` agent files from `~/.claude/agents/`.

After the script finishes, confirm to the user that the claude-ig skill and agents were removed, and that a restart of Claude Code may be needed to fully clear them from the active session.
