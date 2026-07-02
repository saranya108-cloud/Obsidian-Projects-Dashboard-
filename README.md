# Obsidian Projects Dashboard

Obsidian Projects Dashboard -- an AI-assisted project command center for tracking projects, notes, prompts, next steps, and AI handoffs.

This is a small Markdown-only vault/repo designed to be readable in Obsidian, GitHub, and phone review.

## Start Here

| File | Purpose |
|------|---------|
| [AI_PROJECTS_DASHBOARD.md](AI_PROJECTS_DASHBOARD.md) | Main project status dashboard |
| [PROJECT_OBSIDIAN_DASHBOARD.md](PROJECT_OBSIDIAN_DASHBOARD.md) | Project note for this dashboard itself |
| [AI_PROJECT_TEMPLATE.md](AI_PROJECT_TEMPLATE.md) | Template for new AI project notes |
| [FABEL_CONTEXT.md](FABEL_CONTEXT.md) | First file for AI assistants to read |
| [NEXT_STEPS.md](NEXT_STEPS.md) | Setup and workflow checklist |
| [PROJECT_LOG.md](PROJECT_LOG.md) | Dated log of meaningful changes |

## Open On Your Mac (Obsidian)

This folder is a ready-to-use Obsidian vault (it includes an `.obsidian/` config folder), so it opens directly on your Mac.

1. Get the files onto your Mac: in GitHub Desktop or Terminal, clone or pull this repo to a folder you can find (for example `~/Documents/Obsidian-Projects-Dashboard-`).
2. Open Obsidian.
3. Click **Open another vault** (the vault switcher in the bottom-left), then **Open folder as vault**.
4. Choose this repo's folder. Obsidian recognizes the existing `.obsidian/` config and opens it as a vault; click [AI_PROJECTS_DASHBOARD.md](AI_PROJECTS_DASHBOARD.md) in the file explorer to bring up the dashboard.

After the first open, this vault appears in Obsidian's vault list, so you can reopen it with one click, and Obsidian remembers which notes you had open.

> Tip: the Dataview code blocks in the dashboard only render after you install the community **Dataview** plugin (Settings → Community plugins → Browse → Dataview). Until then they show as plain code, which is fine.

## Keep It In Sync

Obsidian edits local files only — it does not talk to GitHub by itself.

- Before editing on your Mac, pull the latest changes (GitHub Desktop: **Fetch origin** then **Pull**, or `git pull` in Terminal).
- After editing, commit and push so the changes show up on GitHub and on your phone.
- Optional: the community **Obsidian Git** plugin can automate pull/commit/push from inside Obsidian.

The `.obsidian/workspace.json` file (window layout and open tabs) is intentionally not tracked in git: Obsidian rewrites it constantly, so tracking it would keep the repo permanently showing uncommitted changes.

## Safety

- Keep this repo free of private, medical, financial, password, account, or personal data.
- Keep notes short enough to review on a phone.
- Use Markdown only unless a future task explicitly asks for tooling.
- Read [FABEL_CONTEXT.md](FABEL_CONTEXT.md) before making structural changes.
