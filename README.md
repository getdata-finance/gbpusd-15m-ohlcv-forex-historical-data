# GBPUSD 15m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-615_367_rows-blue)](https://getdata.finance/datasets/gbpusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/gbpusd)

### -> [**Download the full GBPUSD dataset on getdata.finance**](https://getdata.finance/datasets/gbpusd)

**GBPUSD 15m OHLCV forex historical data** — ultra high-quality 15m OHLCV for **British Pound / US Dollar**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **British Pound / US Dollar** (Forex)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/gbpusd) · **615,367** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `GBPUSD_15m.csv` (3,698 rows, `2026-07-09` -> `2026-09-02`, 350.24 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/gbpusd)** — **615,367** `15m` rows (full `1m`: 9,194,075), **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[GBPUSD_15m.csv](https://github.com/getdata-finance/gbpusd-15m-ohlcv-forex-historical-data/blob/main/GBPUSD_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/gbpusd-15m-ohlcv-forex-historical-data/main/GBPUSD_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/gbpusd-15m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/gbpusd-15m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/gbpusd-15m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/gbpusd](https://getdata.finance/datasets/gbpusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/gbpusd))** |
|---|--:|---|
| Instrument | British Pound / US Dollar · Forex | British Pound / US Dollar · Forex |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 3,698 | **615,367** |
| Size | 350.24 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Period | `2026-07-09` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `GBPUSD_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Coverage report | — | [GBPUSD coverage](https://getdata.finance/coverage/gbpusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/gbpusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/gbpusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GBPUSD_15m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:45:00+00:00 | 1.34266 | 1.34335 | 1.34231 | 1.34319 | 3012 |
| 2026-07-09T14:00:00+00:00 | 1.34319 | 1.34419 | 1.34319 | 1.34325 | 4142 |
| 2026-07-09T14:15:00+00:00 | 1.34325 | 1.34343 | 1.34265 | 1.3432 | 4794 |
| 2026-07-09T14:30:00+00:00 | 1.3432 | 1.34356 | 1.34268 | 1.34297 | 4435 |
| 2026-07-09T14:45:00+00:00 | 1.34297 | 1.34298 | 1.34185 | 1.3422 | 5129 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:00:00+00:00 | 1.35067 | 1.35081 | 1.35038 | 1.35046 | 4070 |
| 2026-09-02T01:15:00+00:00 | 1.35046 | 1.35082 | 1.35041 | 1.35077 | 2839 |
| 2026-09-02T01:30:00+00:00 | 1.35077 | 1.35086 | 1.35026 | 1.35045 | 3054 |
| 2026-09-02T01:45:00+00:00 | 1.35045 | 1.35053 | 1.35024 | 1.3505 | 2007 |
| 2026-09-02T02:00:00+00:00 | 1.3505 | 1.35051 | 1.35026 | 1.35026 | 132 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GBPUSD_15m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GBPUSD_15m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('GBPUSD_15m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **GBPUSD** archive on **[getdata.finance](https://getdata.finance/datasets/gbpusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **615,367** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full GBPUSD dataset on getdata.finance](https://getdata.finance/datasets/gbpusd)**

---
*GetData · GBPUSD 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/gbpusd)*
