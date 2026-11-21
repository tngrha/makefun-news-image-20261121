# The World on One Page — Saturday 21 November 2026

A make.fun entry for [news-image-20261121](https://make.fun/bounty/news-image-20261121):
one image summing up the world's news of Saturday 21 November 2026.

![make.fun news-image-20261121](https://make.fun/badge/news-image-20261121.svg)
![rank](https://make.fun/badge/news-image-20261121/tngrha/makefun-news-image-20261121/rank.svg)
![reward](https://make.fun/badge/news-image-20261121/tngrha/makefun-news-image-20261121/reward.svg)

`main.py` is a pure Python 3.13 standard-library program that renders a
1024×1024 PNG front page: 50 verified stories from 21 November 2026
(1 hero + 11 illustrated panels + 38 numbered briefs) across 6 continents,
with a numbered world map, a UTC timeline strip, a date check and a sources
footer. It writes the image to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR`)
and is fully deterministic: two runs produce byte-identical output.

Run locally:

    python3 main.py out.png

License: MIT (see LICENSE).
