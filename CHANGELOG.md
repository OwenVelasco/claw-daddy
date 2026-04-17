# Clawdius Tailer - Workspace Changelog

## 2026-04-17 — Initial Setup

### What's here
This repo is the persistent memory and workspace for Clawdius (an OpenClaw AI assistant) running on Owen Velasco's VPS.

### Setup completed today
- **GitHub SSH backup** — workspace pushes to `claw-daddy` repo on every meaningful update
- **SSH key** — `github_backup` key added to Owen's GitHub account (read/write only to this repo)
- **PAT token** — removed from system after SSH was confirmed working
- **Monthly memory cron** — fires 9 AM Eastern on the 1st of every month (system crontab + OpenClaw gateway cron backup)
  - Reviews MEMORY.md and USER.md
  - Pushes changes to GitHub
- **Workspace files** — SOUL.md, USER.md, MEMORY.md, AGENTS.md, TOOLS.md, HEARTBEAT.md

### Security
- SSH restricted to `github.com` with `IdentitiesOnly yes`
- No PAT or password auth stored anywhere
- Gateway running on VPS (Hetzner, 195.201.149.85)

### Next time I update this file
- Any new tools or integrations connected
- Changes to Owen's profile/goals/tools
- Major decisions or context changes
- Infrastructure changes

---
_This file is auto-updated by Clawdius after each significant workspace update._
## 2026-04-17 Evening — Google Workspace Setup
- Google Calendar: WORKING — can create events and send invites
- Google Drive: WORKING — created "Shared With Owen" folder
- Google Docs API: Enabled by Owen (API was disabled by default)
- Folder: https://drive.google.com/drive/u/2/folders/1TzSSI-Cqu45OnE3e_IxLwA3dos2va256
- First doc: https://docs.google.com/document/d/16jCD1beOe8WnwrUZ3r9pXtZqJh_nTGgjIqMMFvO000A
- Clawdius's Google: clawdiustailer@gmail.com
