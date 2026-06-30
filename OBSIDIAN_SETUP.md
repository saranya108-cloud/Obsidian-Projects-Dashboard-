# Opening This in Obsidian (Mac)

Obsidian can only open a **local folder** as a vault — it can't open a GitHub
link directly. So the first step is getting a copy of this repo onto your
Mac, then pointing Obsidian at that folder.

## 1. Get Obsidian

Download and install from https://obsidian.md if you don't have it yet.

## 2. Clone this repo to your Mac

Open the **Terminal** app and run:

```bash
cd ~/Documents
git clone https://github.com/saranya108-cloud/obsidian-projects-dashboard-.git
```

This creates a folder at `~/Documents/obsidian-projects-dashboard-` with all
the files from this repo.

(No Terminal/git experience? Install [GitHub Desktop](https://desktop.github.com),
sign in, then `File > Clone Repository` and pick `saranya108-cloud/obsidian-projects-dashboard-`.
Note the folder path it clones to — you'll need it in the next step.)

## 3. Open the folder as a vault

1. Open the Obsidian app.
2. On the "Open vault" screen, click **Open folder as vault**
   (if Obsidian already has a vault open: `File > Open Vault...`).
3. Select the `obsidian-projects-dashboard-` folder from step 2.
4. Obsidian opens it and creates a hidden `.obsidian` settings folder inside
   — that's normal and only affects your local copy.

You should now see `README.md`, `AI_PROJECTS_DASHBOARD.md`, etc. in the file
list on the left.

## 4. Optional: enable Dataview

The auto-filling tables in `AI_PROJECTS_DASHBOARD.md` use the community
**Dataview** plugin. Without it, those code blocks just show as plain text
(not an error). To enable them:

1. `Settings > Community plugins > Browse`.
2. Search for "Dataview", install, and enable it.

## Keeping it in sync later

Any edits you make in Obsidian only change your local copy. To save them
back to GitHub, commit and push from Terminal inside that folder
(`git add -A && git commit -m "..." && git push`), or use GitHub Desktop.
