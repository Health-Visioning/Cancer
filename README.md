# Cancer Development Simulation

An interactive, browser-based model of how cancer develops over a lifetime — built around a "two dice" analogy for cell division and calibrated against published research on aging, mutagens, DNA repair, and inherited risk.

**Live demo:** _(add your GitHub Pages link here once published — see below)_

## What it does

- Simulates 10 organs aging from 0–100, each with its own realistic cell-division rate.
- Marks replication errors ("hits") and cancer formation (two hits) live on the chart as the simulation runs.
- Four adjustable controls, each grounded in cited literature:
  - **Systemic roll frequency** — chronic inflammation / inflammaging
  - **Mutagen exposure** — smoking, UV, alcohol (duration-dependent, per Doll & Peto 1978)
  - **Repair & immune surveillance** — DNA repair capacity, with age-related immunosenescence
  - **Loaded die** — inherited mutation (Knudson's two-hit hypothesis)
- Full reference list and an explicit "what this model is missing" section for honesty about its limitations.

## How to publish this on GitHub Pages (free hosting, ~5 minutes)

1. **Create a GitHub account** at [github.com](https://github.com) if you don't have one.
2. **Create a new repository:**
   - Click the **+** icon (top right) → **New repository**
   - Name it something like `cancer-dice-model`
   - Set it to **Public**
   - Click **Create repository**
3. **Upload the files:**
   - On the new repo page, click **uploading an existing file**
   - Drag in `index.html` (the file in this same folder) and this `README.md`
   - Click **Commit changes**
4. **Turn on GitHub Pages:**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar)
   - Under "Build and deployment," set **Source** to **Deploy from a branch**
   - Set **Branch** to `main` and folder to `/ (root)` → **Save**
5. **Wait ~1 minute**, then refresh that Pages settings page — it will show your live URL, something like:
   `https://yourusername.github.io/cancer-dice-model/`
6. That's your shareable link. Any time you want to update the simulation, upload a new `index.html` to the same repo and the live page updates automatically within a minute or two.

No server, no cost, no expiration — GitHub Pages will host this indefinitely for free as long as the repo exists.

## Alternative one-click hosts

If you'd rather skip GitHub entirely:

- **[Netlify Drop](https://app.netlify.com/drop)** — drag `index.html` onto the page, get a live link instantly, no account required for a quick share (create an account to keep the link permanent).
- **[Vercel](https://vercel.com)** — similar drag-and-drop deploy flow.

## License / attribution

Add your own name/organization and license terms here if you want to formally claim authorship or set reuse terms (e.g., MIT, CC BY-NC).
