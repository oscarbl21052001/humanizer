---
description: Install the humanizer skill (removes AI-writing tells from text) for this machine
---

Install the humanizer skill by fetching its `SKILL.md` directly from the source repo and placing it under this machine's personal skills directory:

```bash
mkdir -p ~/.claude/skills/humanizer
curl -fsSL https://raw.githubusercontent.com/blader/humanizer/main/SKILL.md -o ~/.claude/skills/humanizer/SKILL.md
```

This is global to this machine — once installed it stays available in future conversations too, until `/humanizer-uninstall` is run.

After the command finishes, confirm to the user that the humanizer skill is now available, and that a restart of Claude Code may be needed if the skill list doesn't refresh automatically.
