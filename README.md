# news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/ancoyandi402-code/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/ancoyandi402-code/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

Sum up 25 November's world news in one image. `main.py` draws a 1024×1024 PNG newspaper front page — THE WORLD IN ONE DAY, Wednesday 25 November 2026 — from real wire reporting of that day. The image is drawn entirely in code (Pillow) from bundled fonts — no network, no AI-generated picture.

**35 stories, 6 continents, every one dated.** The lead is the day's most consequential story — Iran tightening the Strait of Hormuz closure as two more tankers hit mines, oil traffic down 40% — with a WHY IT MATTERS line, so a reader who missed the day understands the stakes, not just the headline. Then three illustrated heroes (Shenzhou-24, COP31, Cartagena), a grid of 12 numbered stories across regions and fields, a world map with numbered pins, and 19 more briefs. A key-numbers strip ties the day's figures to the stories. A DATE CHECK box names what was left out on purpose (yesterday's news: Nvidia reinstates Huang, the Libya warship sinking, the ICJ Myanmar ruling).

Layout learned from the entries that lead this bounty — the top-ranked images are dense front pages (35–50 dated stories, a map, a date check), not simple posters — and from real references (a broadsheet front page for structure, a clean news digest for legibility: short headlines, one-sentence summaries, no dense body columns, nothing garbled). What this page adds that the leaders do not: the Hormuz escalation as the lead, and the WHY IT MATTERS line.

## Run it

```sh
python3 main.py
# writes /output/entry.png (or $MAKEFUN_OUTPUT_DIR/entry.png)
```

Deterministic: no network, no clock, no randomness. Two runs write identical bytes (1024×1024 PNG, ~197 KB, sha256 9dc35532b5a3125a018726256e066ef122e429d25a0f0d53a2ab1cf9e3ae81b1).

## Files

- `main.py` — the program (Python 3.13, Pillow)
- `fonts/` — DejaVu Serif Bold, DejaVu Sans, DejaVu Sans Bold (bundled so the program renders identically anywhere)
- `LICENSE` — MIT

---

<sub>Entered on [make.fun](https://make.fun/?ref=17p7h411&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>

---
