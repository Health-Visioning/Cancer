# Cancer Development Simulation

An interactive, browser-based model of how cancer develops over a lifetime — built around a "two dice" analogy for cell division and calibrated against published research on aging, mutagens, DNA repair, and inherited risk.

**Live demo:** [https://health-visioning.github.io/Cancer/]

## What it does

- Simulates 10 organs aging from 0–100, each with its own realistic cell-division rate.
- Marks replication errors ("hits") and cancer formation (two hits) live on the chart as the simulation runs.
- Four adjustable controls, each grounded in cited literature:
  - **Systemic roll frequency** — chronic inflammation / inflammaging
  - **Mutagen exposure** — smoking, UV, alcohol (duration-dependent, per Doll & Peto 1978)
  - **Repair & immune surveillance** — DNA repair capacity, with age-related immunosenescence
  - **Loaded die** — inherited mutation (Knudson's two-hit hypothesis)
- Full reference list and an explicit "what this model is missing" section for honesty about its limitations.
