# Perch releases

The website for Perch, Karo Budget and just for run, plus Perch's DMGs and
Sparkle update feed. Deployed on Netlify (static, no build step; see `netlify.toml`).

- `/` — Perch (`index.html`, `privacy.html`)
- `/karo-budget/` — Karo Budget (`karo-budget/index.html`, `karo-budget/privacy.html`)
- `/just-for-run/` — just for run (`just-for-run/index.html`, `just-for-run/privacy.html`)
- `assets/apps/` — the iPhone apps' icons, screenshots and link-preview images

Produced by `scripts/release.sh` in the (private) app repo, never edit by hand:
`downloads/Perch-<version>.dmg`, `downloads/*.delta`, `Perch.dmg` (latest), `appcast.xml`.
