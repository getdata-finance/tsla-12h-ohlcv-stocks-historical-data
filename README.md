# TSLA 12h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_065_rows-blue)](https://getdata.finance/datasets/tsla) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/tsla)

### -> [**Download the full TSLA dataset on getdata.finance**](https://getdata.finance/datasets/tsla)

**TSLA 12h OHLCV stocks historical data** — ultra high-quality 12h OHLCV for **Tesla**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 12h OHLCV** for **Tesla** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/tsla) · **3,065** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `TSLA_12h.csv` (77 rows, `2026-05-13` -> `2026-09-01`, 8.36 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/tsla)** — **3,065** `12h` rows (full `1m`: 615,796), **11 timeframes**, `2011-05-09` -> `2026-09-01`.

## Download sample

**[TSLA_12h.csv](https://github.com/getdata-finance/tsla-12h-ohlcv-stocks-historical-data/blob/main/TSLA_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/tsla-12h-ohlcv-stocks-historical-data/main/TSLA_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/tsla-12h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/tsla-12h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/tsla-12h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/tsla](https://getdata.finance/datasets/tsla)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/tsla))** |
|---|--:|---|
| Instrument | Tesla · US stocks | Tesla · US stocks |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 77 | **3,065** |
| Size | 8.36 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Period | `2026-05-13` -> `2026-09-01` | `2011-05-09` -> `2026-09-01` |
| File | `TSLA_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Coverage report | — | [TSLA coverage](https://getdata.finance/coverage/tsla) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/tsla)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/tsla) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`TSLA_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-05-13T12:00:00+00:00 | 439.9 | 459.48 | 436.33 | 451.2 | 101646.41769 |
| 2026-05-14T12:00:00+00:00 | 451.2 | 458.02 | 447.28 | 449.5 | 95444 |
| 2026-05-15T12:00:00+00:00 | 449.5 | 449.5 | 428.09 | 428.31 | 120047.22567 |
| 2026-05-18T12:00:00+00:00 | 428.31 | 428.31 | 411.42 | 416.04 | 100438 |
| 2026-05-19T12:00:00+00:00 | 416.04 | 416.04 | 399.75 | 410.35 | 80904 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-26T12:00:00+00:00 | 349.65 | 351.06 | 341.74 | 345.08 | 43691 |
| 2026-08-27T12:00:00+00:00 | 345.08 | 354.75 | 344.12 | 353.52 | 53995 |
| 2026-08-28T12:00:00+00:00 | 353.52 | 357.73 | 344.16 | 347.61 | 54979 |
| 2026-08-31T12:00:00+00:00 | 347.61 | 367.96 | 345.92 | 366.87 | 67129 |
| 2026-09-01T12:00:00+00:00 | 366.87 | 366.87 | 352.01 | 355.26 | 46469 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('TSLA_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('TSLA_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('TSLA_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **TSLA** archive on **[getdata.finance](https://getdata.finance/datasets/tsla)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **3,065** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full TSLA dataset on getdata.finance](https://getdata.finance/datasets/tsla)**

---
*GetData · TSLA 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/tsla)*
