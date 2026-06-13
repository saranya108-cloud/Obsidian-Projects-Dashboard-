# FABEL_CONTEXT - Read This First

Hello, AI assistant. This file explains how to work in this repository safely. Read it before touching anything.

## What This Repo Is

This is a personal AI projects command-center packet: Markdown notes that track projects, next steps, progress, and AI handoffs. It is meant to work well in Obsidian, GitHub, and phone review.

It is not a full Obsidian vault, and it must never contain private personal, medical, financial, password, or account information.

## How To Read The Dashboard

1. Start at [AI_PROJECTS_DASHBOARD.md](AI_PROJECTS_DASHBOARD.md). Project status lives there.
2. Individual projects can be created from [AI_PROJECT_TEMPLATE.md](AI_PROJECT_TEMPLATE.md), with YAML frontmatter for `type`, `status`, `priority`, and `progress`.
3. [PROJECT_LOG.md](PROJECT_LOG.md) is the dated history, with newest entries at the top.
4. A project note's `Next Steps` section is the source of truth for what to do next.

## Files That Matter

| File | Role |
|------|------|
| `README.md` | Repo index |
| `AI_PROJECTS_DASHBOARD.md` | Main overview |
| `AI_PROJECT_TEMPLATE.md` | Template for new project notes |
| `PROJECT_LOG.md` | Dated change log |
| `NEXT_STEPS.md` | Setup and workflow checklist |

## Rules For Working Here

- Ask before deleting, renaming, or reorganizing anything.
- Prefer small, reviewable Markdown edits.
- Do not add build steps, package installs, or new tooling unless explicitly asked.
- Never add private data, even if it shows up elsewhere in conversation.
- Keep the dashboard format consistent and phone-reviewable.
- When making a meaningful change, add a dated line to [PROJECT_LOG.md](PROJECT_LOG.md).

## How To Propose Changes

1. Say what should change and why in one or two sentences.
2. Make the smallest version of the change that works.
3. If a change touches more than a couple of files, pause and confirm first.
4. Keep commit messages short and descriptive.

When in doubt: ask, keep it small, keep it Markdown.
