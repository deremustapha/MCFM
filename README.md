# Cross-FM project page

A single self-contained `index.html` (no build step, no external dependencies —
all CSS is inline) for a GitHub Pages project site, in the style of pages like
emgbench.github.io.

## Publish it (pick one)

**Option A — dedicated `<user>.github.io` repo (simplest, gives you a clean root URL):**
1. Create a new GitHub repo named exactly `<your-username>.github.io`.
2. Push this folder's `index.html` to that repo's root (`main` branch).
3. In the repo's Settings → Pages, set Source = `main` / `/ (root)`. Save.
4. Live in a minute or two at `https://<your-username>.github.io/`.

**Option B — as a page for an existing project repo:**
1. Copy `index.html` into that repo, either at the root or under `docs/`.
2. Settings → Pages → Source = `main` / `/ (root)` (or `/docs`, matching where you put it).
3. Live at `https://<your-username>.github.io/<repo-name>/`.

## Before publishing, fill in

Search the file for these placeholders and replace them:
- `[Author One]`, `[Author Two]`, `[Author Three]`, `[Institution 1]`, `[Institution 2]`
- The `href="#"` Paper link, and the `REPLACE_ME` GitHub code links (two spots)
- The BibTeX block's `journal`/`year` if needed

Everything else (datasets table, results tables, ablation table, findings) is filled in
with the real numbers already produced by the project's experiment scripts.
