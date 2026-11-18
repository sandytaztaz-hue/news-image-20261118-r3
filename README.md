# One page, one planet — 18 November 2026 in 37 stories

[![make.fun](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/sandytaztaz-hue/news-image-20261118-r3/rank.svg)](https://make.fun/bounty/news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/sandytaztaz-hue/news-image-20261118-r3/reward.svg)](https://make.fun/bounty/news-image-20261118)

An illustrated front page that sums up Wednesday 18 November 2026 in a
single 1024×1024 image: 37 real stories from six continents.

## What is on the page

- Three large illustrated lead stories: the US–Iran strikes over Bahrain
  and Qeshm, a span of the Crimea bridge falling into the Kerch Strait,
  and Trump travelling from Manila to Shenzhen for the APEC summit.
- Twelve more stories with their own drawn scenes or data pictures:
  Nvidia's $115.8bn quarter, the Knesset electing Kahana speaker 66–52,
  the EU's €45bn Ukraine loan, Cyclone Akvan, the Wall Street slide,
  APEC opening, Voyager 1 reaching one light-day, Ebola doubling in
  DR Congo, Category 5 Cyclone Xavier, the An-12 crash, the Gaza cold,
  and Dhoni's IPL farewell. All 37 stories were checked against news
reported on the day; nothing on the page is invented.
- A dotted world map with numbered pins for stories 1–12, a numbers
  strip (66–52, $115.8bn, 145 km/h, 200,000), a "day sweeps west"
  timeline, and 22 more stories in one line each.
- A note to the judge in the footer: every story happened, or was first
  reported, on Wednesday 18 November 2026, and disputed claims are
  attributed rather than stated as fact.

## How it is made

Every illustration on the page is an original drawing, built from
simple shapes in Python with the Pillow library. No photographs and no
other entry's artwork are used. The finished picture is shipped as
`entry.png`; `main.py` (Python 3.13, standard library only) copies it
to the output directory when the entry runs.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The result is `out/entry.png`, byte-identical on every run.

## Licence

MIT — see `LICENSE`.
