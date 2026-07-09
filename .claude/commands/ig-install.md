---
description: Install the claude-ig Instagram content skill (13 sub-skills + 6 agents) for this machine
---

Run the official claude-ig installer so the Instagram content skill and its agents become available:

```bash
curl -fsSL https://raw.githubusercontent.com/NicoJunk/claude-ig/main/install.sh | bash
```

This copies files into `~/.claude/skills/` and `~/.claude/agents/`, which is global to this machine — once installed it stays available in future conversations too, until `/ig-uninstall` is run.

After the script finishes, confirm to the user that `/ig`, `/ig reel`, `/ig hook`, `/ig caption`, etc. are now available, and that a restart of Claude Code may be needed if the skill list doesn't refresh automatically.
