# TSLA 12h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_043_rows-blue)](https://getdata.finance/datasets/tsla) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/tsla)

### -> [**Download the full TSLA dataset on getdata.finance**](https://getdata.finance/datasets/tsla)

**TSLA 12h OHLCV us stocks historical data** — ultra high-quality 12h OHLCV for **TSLA**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **TSLA** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/tsla) · **3,043** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `TSLA_12h.csv` (90 rows, `2026-03-24` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/tsla)** — **3,043** `1m` rows (~0.23 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-31`.

## Download sample

**[TSLA_12h.csv](https://github.com/getdata-finance/tsla-12h-ohlcv-stocks-historical-data/blob/main/TSLA_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/tsla-12h-ohlcv-stocks-historical-data/main/TSLA_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/tsla-12h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/tsla-12h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/tsla-12h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/tsla](https://getdata.finance/datasets/tsla)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/tsla))** |
|---|--:|---|
| Instrument | TSLA · US stocks | TSLA · US stocks |
| Timeframes | `12h` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 90 | **3,043** |
| Size | 0.01 MB | ~0.23 MB |
| Period | `2026-03-24` -> `2026-07-31` | `2011-05-09` -> `2026-07-31` |
| File | `TSLA_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Coverage report | — | [TSLA coverage](https://getdata.finance/coverage/tsla) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/tsla)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/tsla) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`TSLA_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-24T12:00:00+00:00 | 386.86 | 393.39 | 381.83 | 389.15 | 144005 |
| 2026-03-25T12:00:00+00:00 | 389.15 | 402.09 | 389.15 | 391.72 | 124877 |
| 2026-03-26T12:00:00+00:00 | 391.72 | 391.72 | 377.74 | 377.94 | 134400 |
| 2026-03-27T12:00:00+00:00 | 377.94 | 377.94 | 365.36 | 367.88 | 159341.0413223141 |
| 2026-03-30T12:00:00+00:00 | 367.88 | 373.05 | 358.02 | 361.1 | 146023 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T12:00:00+00:00 | 312.11 | 316.31 | 303.69 | 307.99 | 75909.4728383076 |
| 2026-07-28T12:00:00+00:00 | 307.99 | 310.09 | 299.71 | 306.28 | 69760 |
| 2026-07-29T12:00:00+00:00 | 306.28 | 307.67 | 296.36 | 297.3 | 103280 |
| 2026-07-30T12:00:00+00:00 | 297.3 | 309.84 | 297.3 | 307.87 | 76422 |
| 2026-07-31T12:00:00+00:00 | 307.87 | 314.39 | 300.97 | 310.33 | 67052 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **TSLA** archive on **[getdata.finance](https://getdata.finance/datasets/tsla)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **3,043** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full TSLA dataset on getdata.finance](https://getdata.finance/datasets/tsla)**

---
*GetData · TSLA 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/tsla) · 2026-08-05 UTC*
