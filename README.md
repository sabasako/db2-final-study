# DB2 Final Study

Static, multi-page study site for **KIU Databases II** (final exam, 2026).

Each module is its own HTML page, with a shared collapsible left sidebar (☰, top-left)
for navigation. Links are real pages, so **middle-click opens them in a new tab**.

## Pages

| File | Topic |
|------|-------|
| `index.html` | Landing page |
| `5-transactions.html` | 5.4 — Transactions & Concurrency Control |
| `6.1-6.2-consistency.html` | 6.1–6.2 — Consistency & Conflict Resolution |
| `6.3-6.4-consensus-lwt.html` | 6.3–6.4 — Consensus & Lightweight Transactions |
| `7-mongodb.html` | 7 — MongoDB & Sharding |
| `final-exam-prep.html` | Final exam sample tasks + solutions |

## Reading features (every page)

- **Aa** button (top-right): font size, content width, light / dark / system theme — shared across all pages.
- Page counter (bottom-right): hover/click for a clickable section outline with live scroll-spy.
- Fully responsive; print-friendly (controls hidden, light background).

## View locally

Just open `index.html` in a browser — no build step, no server required.
(Optional local server: `python3 -m http.server` then visit `http://localhost:8000`.)

## Host it

It's plain static files, so any static host works:

- **GitHub Pages:** push this repo to GitHub → Settings → Pages → deploy from the default branch root. Site goes live at `https://<user>.github.io/<repo>/`.
- **Netlify / Vercel / Cloudflare Pages:** drag-and-drop the folder, or connect the repo. No build command; publish directory is the repo root.

## License

Personal study material.
