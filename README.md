# Project Risk Identification Assistant (v2.2)

A single-file HTML tool to assess project delivery and governance risks and export matched items to XLS.

## Quick start

Open `index.html` in any modern browser.

## todo
1. Move plotted risks to prevent overlay of risks on plot
2. add back standard risks matrix

Changes
## Print fix
This version includes a print fix so **Print Matched** shows the results. If you haven't generated results yet, the tool will auto-populate before calling `window.print()`.

## add ploter for risk table

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
