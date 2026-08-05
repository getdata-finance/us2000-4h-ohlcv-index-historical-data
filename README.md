# US2000 4h OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-12_406_rows-blue)](https://getdata.finance/datasets/us2000) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us2000)

### -> [**Download the full US2000 dataset on getdata.finance**](https://getdata.finance/datasets/us2000)

**US2000 4h OHLCV stock index historical data** — ultra high-quality 4h OHLCV for **Russell 2000**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 4h OHLCV** for **Russell 2000** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us2000) · **12,406** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `US2000_4h.csv` (12,406 rows, `2018-10-26` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/us2000)** — **12,406** `1m` rows (~0.91 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `2018-10-26` -> `2026-07-31`.

## Download sample

**[US2000_4h.csv](https://github.com/getdata-finance/us2000-4h-ohlcv-index-historical-data/blob/main/US2000_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us2000-4h-ohlcv-index-historical-data/main/US2000_4h.csv)) · [GitHub Releases](https://github.com/getdata-finance/us2000-4h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us2000-4h-ohlcv-index-historical-data/](https://getdata-finance.github.io/us2000-4h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us2000](https://getdata.finance/datasets/us2000)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us2000))** |
|---|--:|---|
| Instrument | Russell 2000 · Stock index | Russell 2000 · Stock index |
| Timeframes | `4h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 12,406 | **12,406** |
| Size | 0.92 MB | ~0.91 MB |
| Period | `2018-10-26` -> `2026-07-31` | `2018-10-26` -> `2026-07-31` |
| File | `US2000_4h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Coverage report | — | [US2000 coverage](https://getdata.finance/coverage/us2000) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`4h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us2000)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `4h` sample · [getdata.finance](https://getdata.finance/datasets/us2000) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US2000_4h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2018-10-26T12:00:00+00:00 | 1464.3 | 1467.6 | 1460.5 | 1461.3 | 5150 |
| 2018-10-26T16:00:00+00:00 | 1461.3 | 1498.9 | 1461.3 | 1484.3 | 136022 |
| 2018-10-26T20:00:00+00:00 | 1484.3 | 1491.8 | 1484.1 | 1486.8 | 13932 |
| 2018-10-28T20:00:00+00:00 | 1486.8 | 1497.5 | 1486.8 | 1493.9 | 12159 |
| 2018-10-29T00:00:00+00:00 | 1493.9 | 1496.8 | 1486.1 | 1488.4 | 36851 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T04:00:00+00:00 | 2961.41 | 2969.77 | 2959.26 | 2967.42 | 17706 |
| 2026-07-31T08:00:00+00:00 | 2967.42 | 2971.85 | 2958.95 | 2962.36 | 22415 |
| 2026-07-31T12:00:00+00:00 | 2962.36 | 2963.3 | 2901.06 | 2927.9 | 156081 |
| 2026-07-31T16:00:00+00:00 | 2927.9 | 2941.87 | 2920.11 | 2934.82 | 98315 |
| 2026-07-31T20:00:00+00:00 | 2934.82 | 2936.56 | 2930.55 | 2932.3 | 5498 |

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

df = pd.read_csv('US2000_4h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US2000_4h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('US2000_4h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **US2000** archive on **[getdata.finance](https://getdata.finance/datasets/us2000)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **12,406** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full US2000 dataset on getdata.finance](https://getdata.finance/datasets/us2000)**

---
*GetData · US2000 4h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us2000) · 2026-08-05 UTC*
