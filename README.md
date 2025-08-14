# Project Risk Identification Assistant (v2.2)

A single-file HTML tool to assess project delivery and governance risks and export matched items to XLS.

## Quick start (local)

Open `index.html` in any modern browser.

## Print fix
This version includes a print fix so **Print Matched** shows the results. If you haven't generated results yet, the tool will auto-populate before calling `window.print()`.

## GitHub setup

```bash
# 1) Create a new, empty repo on GitHub (no README or .gitignore)
# 2) Then run locally:
git clone <YOUR_REPO_SSH_OR_HTTPS_URL>
cd <your-repo-folder>

# If cloning an empty repo, create a main branch
git checkout -b main

# Copy the files from this bundle into the repo folder, then:
git add .
git commit -m "Add Project Risk Identification Assistant v2.2 (single-file HTML)"
git push -u origin main
```

## File layout

```
.
├── index.html       # The complete tool
├── .gitignore
└── README.md
```

## Optional next steps
- Split CSS/JS into separate files if you prefer smaller diffs in commits.
- Add a GitHub Pages site to host the tool (Settings → Pages → Deploy from branch → `/root` or `/docs`).
- Add release tags for each version (e.g., `v2.2`).
