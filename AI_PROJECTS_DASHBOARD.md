# AI Projects Dashboard

One screen to see where AI projects stand. Update the tables by hand, or let Obsidian Dataview fill them in automatically.

---

## Active Projects

| Project | Priority | Progress | Next Step |
|---------|----------|----------|-----------|
| Obsidian Projects Dashboard | medium | 80% | Use this packet for the next AI handoff |

<details>
<summary>Optional: Obsidian Dataview query</summary>

```dataview
TABLE priority, progress, deadline
FROM ""
WHERE type = "ai-project" AND status = "active"
SORT priority DESC
```

</details>

---

## Ideas & Backlog

- [ ] Add one shareable project note from the Obsidian vault.
- [ ] Decide whether each project needs its own GitHub repo link.
- [ ] Keep a short list of AI workflows that are working well.

<details>
<summary>Optional: Obsidian Dataview query</summary>

```dataview
LIST
FROM ""
WHERE type = "ai-project" AND status = "idea"
```

</details>

---

## On Hold

| Project | Why paused | Resume when |
|---------|------------|-------------|
| - | - | - |

---

## Completed

| Project | Finished | Outcome |
|---------|----------|---------|
| Dashboard packet setup | 2026-06-13 | Core command-center files created in the correct repo |

---

## Recently Touched

- 2026-06-13 - Recreated the AI Projects dashboard packet in this repository.

<details>
<summary>Optional: Obsidian Dataview query</summary>

```dataview
TABLE file.mtime AS "Last edited"
FROM ""
WHERE type = "ai-project"
SORT file.mtime DESC
LIMIT 5
```

</details>

---

## Model / Tool Watchlist

| Tool / Model | Why watching | Notes |
|--------------|--------------|-------|
| Obsidian | Note system | Keep plugin use minimal |
| GitHub | Sync and review | Keep commits small |
| AI coding assistant | Handoff support | Start from FABEL_CONTEXT.md |

---

## Important Safety Rules

1. No private data in this repo: no personal, medical, financial, password, or account information.
2. This is not a full Obsidian vault; only copy selected, shareable notes here.
3. AI assistants should read [FABEL_CONTEXT.md](FABEL_CONTEXT.md) before editing anything.
4. Prefer small edits over big rewrites so every change is easy to review on a phone.
5. Ask before deleting, renaming, or reorganizing files.

---

## Useful Links

- [FABEL_CONTEXT.md](FABEL_CONTEXT.md) - AI handoff starting point
- [AI_PROJECT_TEMPLATE.md](AI_PROJECT_TEMPLATE.md) - new project template
- [PROJECT_LOG.md](PROJECT_LOG.md) - change history
- [NEXT_STEPS.md](NEXT_STEPS.md) - setup checklist
