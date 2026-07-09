---
description: Remove the humanizer skill from this machine
---

Remove everything `/humanizer-install` added:

```bash
rm -rf ~/.claude/skills/humanizer
```

After the command finishes, confirm to the user that the humanizer skill was removed, and that a restart of Claude Code may be needed to fully clear it from the active session.
