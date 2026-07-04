# XAUUSD 3m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-62_619_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full XAUUSD dataset on ork.ad**](https://ork.ad/)

**XAUUSD 3m OHLCV Precious metals historical data** — ultra high-quality 3m OHLCV for **Gold / US Dollar**. Near-continuous precious-metals liquidity across global sessions. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Gold / US Dollar** (Precious metals)
- **Near-continuous precious-metals liquidity across global sessions**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **62,619** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `XAUUSD_3m.csv` (39,758 rows, `2026-03-03` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **62,619** `3m` rows (~3.7 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-22` → `2026-07-02`.

## Download sample

**[XAUUSD_3m.csv](https://github.com/ork-ad/xauusd-3m-ohlcv-metals-historical-data/blob/main/XAUUSD_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/xauusd-3m-ohlcv-metals-historical-data/main/XAUUSD_3m.csv)) · [GitHub Releases](https://github.com/ork-ad/xauusd-3m-ohlcv-metals-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/xauusd-3m-ohlcv-metals-historical-data/](https://ork-ad.github.io/xauusd-3m-ohlcv-metals-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Precious metals | Gold / US Dollar · Precious metals |
| Timeframes | `3m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 3m rows | 39,758 | **62,619** |
| Size | 2.36 MB | ~3.7 MB |
| Period | `2026-03-03` → `2026-07-02` | `2025-09-22` → `2026-07-02` |
| File | `XAUUSD_3m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`3m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `3m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_3m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-03 04:57:00 | 5364.474 | 5366.164 | 5360.564 | 5360.624 | 1764.0 |
| 2026-03-03 05:00:00 | 5360.624 | 5366.164 | 5356.014 | 5363.55 | 2846.0 |
| 2026-03-03 05:03:00 | 5363.55 | 5364.754 | 5359.924 | 5359.944 | 1515.0 |
| 2026-03-03 05:06:00 | 5359.944 | 5364.924 | 5358.744 | 5364.444 | 1575.0 |
| 2026-03-03 05:09:00 | 5364.444 | 5366.774 | 5363.464 | 5365.484 | 1774.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02 22:24:00 | 4123.54 | 4123.78 | 4122.72 | 4122.72 | 358.0 |
| 2026-07-02 22:27:00 | 4122.72 | 4124.28 | 4122.52 | 4124.28 | 606.0 |
| 2026-07-02 22:30:00 | 4124.28 | 4124.92 | 4123.37 | 4123.97 | 508.0 |
| 2026-07-02 22:33:00 | 4123.97 | 4126.26 | 4123.82 | 4124.98 | 337.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('XAUUSD_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_3m.csv', parse_dates=['time'])
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

df = pd.read_csv('XAUUSD_3m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **62,619** rows at `3m`, plus all other timeframes in the same ZIP.

**[→ Get the full XAUUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · XAUUSD 3m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*