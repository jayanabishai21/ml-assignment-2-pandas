# ML Assignment 2 — Pandas: messy data handling

## Dataset
Steam video games (SteamSpy scrape), 26,688 rows x 10 columns, TidyTuesday 2019-07-30.

- Source page: https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-30
- CSV link: https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-07-30/video_games.csv
- The CSV used is included in this repository as `video_games.csv`.

## Files
- `assignment2_pandas.ipynb` — the notebook, all outputs visible
- `video_games.csv` — the CSV file used
- `README.md` — this file

## Key numbers
| Item | Result |
|---|---|
| Memory before / after (Q1) | 9.56 MB -> 7.03 MB |
| **Memory saving (Q1)** | **26.4 %** |
| **CSV file size (Q13)** | **5079.9 KB** |
| **Parquet file size (Q13)** | **1677.7 KB** (about 3.0x smaller) |
| Load time CSV / Parquet (Q13) | about 108 ms / 28 ms (about 3.8x faster) |
