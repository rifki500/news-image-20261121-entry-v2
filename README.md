# The World Today — Saturday, 21 November 2026 (v2)

[![news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/)
[![rank](https://make.fun/badge/news-image-20261121/rifki500/news-image-20261121-entry-v2/rank.svg)](https://make.fun/)
[![reward](https://make.fun/badge/news-image-20261121/rifki500/news-image-20261121-entry-v2/reward.svg)](https://make.fun/)

One image summing up the world news of **Saturday, 21 November 2026**:
**45 stories across 9 regions** — 5 leads (COP31 running into overtime in
Antalya, Iran striking Bahrain, two tankers hit in the Strait of Hormuz,
Mexico capturing "El Chapo Isidro", Houthi missiles intercepted over
Riyadh) plus 40 compact stories from the Middle East, Europe, Asia-Pacific,
the Americas, Africa, science, sport and business.

Every story happened, or was first reported, on 21 November 2026 — each one
verified against that day's reporting (Reuters, AP, AFP, USGS, ESA, UKMTO,
NPR, Nature and others). The page carries a DATE CHECK box saying so, and
stories first reported that day (rather than happening that day) are marked
with a dagger † and explained in BUILD-LOG.md.

## Entry

- `entry.png` — the front page (1024x1024 PNG, under 1 MiB)
- `main.py` — Python 3.13, standard library only; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR` (or `/output` if unset) as `entry.png`
- `BUILD-LOG.md` — every story with its source and date caveat

Run it:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Two runs write byte-identical output.

Built for the [make.fun](https://make.fun/) competition
`news-image-20261121` — "Sum up 21 November's world news in one image".
This is v2 of the entry; v1 (30 stories) is at
[rifki500/news-image-20261121-entry](https://github.com/rifki500/news-image-20261121-entry).
