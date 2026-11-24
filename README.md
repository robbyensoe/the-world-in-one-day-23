# The World in One Day — 23 November

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/robbyensoe/the-world-in-one-day-23/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/robbyensoe/the-world-in-one-day-23/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

**Monday 23 November 2026, on one page.**

`entry.png` is a front page that sums up the world's news of Monday
23 November 2026 — the day Nvidia's board brought Jensen Huang back and
the stock leapt 31% in its best day since 2003, Ukraine confirmed its
sea drones had sunk a Russian warship in a Libyan port, and the longest
climate summit on record closed in Turkey without a deal. Thirteen
stories, one image: the Huang comeback, Benghazi, the Cikande factory
fire, BepiColombo at Mercury, COP31's collapse, Kyiv under bombardment,
the Riemann proof claim, the 2035 Women's World Cup, and the day's
smaller print.

## How it runs

`main.ts` (Node 22, standard library only) verifies the image is a
complete PNG/JPEG within the gate's limits (≤1 MiB, ≤1024×1024) and
copies it to `/output/entry.png`:

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The artwork is original editorial illustration; every headline was
typeset programmatically so the text stays crisp. Story selection and
sources are listed in `SOURCES.md`. Built for the make.fun bounty
[Sum up 23 November's world news in one image](https://make.fun/bounty/news-image-20261123).
