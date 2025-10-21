# 🌍📊 HyperManifold

> Connecting TradFi ↔ Crypto, every single day — with data, logic, and a dash of fun.
>  Decentralized research · Open discussion · A public knowledge base for everyone

[![docs zh](https://img.shields.io/badge/docs%20zh-中文文档-blue)](./README_zh.md)  [![license](https://img.shields.io/badge/license-CC_BY_NC_ND_4.0-red)](./LICENSE)

------

## 🔗 Latest Reports
- 2025-10-21 · EN → [Market Overview](./reports/20251021/EN/market_overview_EN.md) · [BTC](./reports/20251021/EN/BTCUSDT_EN.md) · [ETH](./reports/20251021/EN/ETHUSDT_EN.md)
- 2025-10-20 · EN → [Market Overview](./reports/20251020/EN/market_overview_EN.md) · [BTC](./reports/20251020/EN/BTCUSDT_EN.md) · [ETH](./reports/20251020/EN/ETHUSDT_EN.md)
- 2025-10-19 · EN → [Market Overview](./reports/20251019/EN/market_overview_20251019_EN.md) · [BTC](./reports/20251019/EN/BTCUSDT_20251019_EN.md)· [ETH](./reports/20251019/EN/ETHUSDT_20251019_EN.md) 

------

## 📂 0. Report Tree & Quick Links

**Fixed structure**

```
reports/
├── <YYYY-MM-DD>/
│   ├── CN/                      # Chinese
│   │   ├── market_overview.md   # Market overview (free)
│   │   ├── BTCUSDT.md           # BTC deep-dive (free)
│   │   └── ETHUSDT.md           # ETH deep-dive (free)
│   └── EN/                      # English
│       ├── market_overview.md
│       ├── BTCUSDT.md
│       └── ETHUSDT.md
└── ...
```
> Note: Type 1 **Comprehensive Overview** (macro + crypto-macro + majors at a glance) is updated **daily for free**. Type 2 **Single-Asset Deep-Dive** is currently **free for BTC/ETH**.

------

## 🤝 1. About Maintainer and project

As an **AI Startup Founder** and long-term explorer of quantitative research, I’ve built—on my own time—an end-to-end pipeline from data → indicators → inference → reports, and I use a multi-agent system to automate the strategy into daily outputs. This repository is open-sourced and free to make analyses with consistent methodology and sufficient evidence more reproducible, discussable, and improvable—knowledge should be shared, not mythologized. (Nothing here constitutes investment advice; the documentation is licensed under CC BY-NC-ND 4.0.)

 We blend **global macro liquidity** (central-bank liquidity, dollar dynamics, fiscal pulse, etc.) with **crypto microstructure** (volume, flows, volatility, price structure) into a coherent, reviewable output — two flavors:

1. **Market Overview** (free): a bird’s-eye flow from **macro → on-chain bridge → market structure**
2. **Single-Asset Deep-Dive**: multi-timeframe (W/D/H4) + dimension scoring + key levels + scenario framing

Our vibe is **open-minded**, cross-disciplinary, and decentralized. We love rigorous evidence chains but keep the reading experience human. We respect statistics and unified “rule-of-thumb” **calibration**, while acknowledging narrative and reflexivity. We believe **open methods + clear conclusions** beat “mystery sauce” in a volatile world.

------

## 🎯 2. Who Is This For

- 📈 **Traders / quants** seeking a fast alignment of *macro ↔ market*
- 🔗 **Web3 / DeFi participants** who want daily structural snapshots & key-level heat
- 🔭 **Tech / finance observers** interested in how liquidity and on-chain flows transmit to prices
- 🤔 **Curious humans** — zero-barrier reading; learn the “why,” step by step

> We don’t offer investment advice. We offer **verifiable analysis and frameworks** to help you form your own view.

------

## 🧪 3. Methodology

Core recipe: **Multi-Timeframe (W/D/H4) × Macro Injection × Structured Scoring**.
 In one line: **Fix the “environment” first, read the “structure” second, time the “pace” last.**

### 3.1 Multi-Timeframe (W/D/H4)

- **Weekly (W)**: big-cycle posture and structural backdrop
- **Daily (D)**: mid-cycle state and inflection checks
- **4-hour (H4)**: execution rhythm and alignment tests

> **HTF Gate**: W/D decide the baseline; H4 only aligns/refines rhythm. If W and D disagree, **D leads execution**, **W biases direction**.

### 3.2 Macro Injection

We inject the **“water level”** of the environment into technical reading:

- Track **central-bank & fiscal liquidity** (RRP/TGA/reserves), **DXY**, **rates** to describe **MWI** (macro water index) and **NL7** (net 7-day injections/withdrawals).
- Add the **stablecoin bridge** (e.g., **SMR** share, **CUE** capital-use efficiency, **SLP** 7-day net issuance) to judge **macro → on-chain → market** transmission quality & lag.
- If macro and bridge align, **raise confidence**; if they diverge, **lower confidence**. (Divergence ≠ instant reversal; think **drag/lag**.)

### 3.3 Structured Scoring (comparable across time)

We break the market into consistent dimensions:

- **Price structure & patterns** (key levels, completion/validation of structures)
- **MA system** (20/50/200 positions, slopes, golden/death crosses)
- **Momentum** (MACD zero-axis & bars; RSI zones & divergences)
- **Flows** (OBV/CMF directionality & persistence)
- **Trend strength** (DMI/ADX organizational clarity)
- **Volatility & location** (ATR/nATR, KC band positioning: mid/upper/lower/outside)
- **Multi-TF resonance** (W/D/H4 alignment; volume-backed reclaim/loss of key MAs)

> **Note**: README outlines **framework & calibration only**. We keep weights, rule conflicts, and some thresholds in code/internal docs and iterate. Our priority: **evidence chains + unified wording**, not esoteric parameters.

### 3.4 Output & Visualization

- **One-screen glance**: core verdict + 3–5 hard evidence bullets + a micro macro-transmission sentence
- **Tables**: unified snapshot of indicators based on the **last closed candle only**
- **Emoji cues**: 🟢 (pro-bull) | 🔴 (pro-bear) | 🟡 (neutral/range) for fast scanning

------

## 📊 4. Data & Signals

| Category                     | Key fields / calibration examples                            | What it’s for                                                | Sources                    |
| ---------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------- |
| **Macro liquidity**          | MWI (-10~+10), NL7 (7-day net), RRP, TGA, bank reserves, DXY, UST10Y | External liquidity & risk appetite, split into “quality vs. pulse” | Federal Reserve            |
| **Stablecoin bridge**        | SLP (7-day net), **SMR** (stablecoin share %), **CUE** (capital-use %) | Transmission quality & lag from macro → on-chain → market    | On-chain                   |
| **Market core data**         | OHLCV (W/D/H4), open-candle down-weighting                   | Aligns to exchange `server_time`; snapshots use **last closed only** | Binance · Bybit · Coinbase |
| **MA system**                | MA20/50/200 (MA730 as a valuation anchor if needed)          | Structure & tiering; cross & slope consistency               | Indicator system           |
| **Momentum**                 | MACD (axis, bar expansion/contract), RSI(7/14)               | Priority: zero-axis > cross > bars                           | Indicator system           |
| **Flows**                    | OBV vs EMA9, CMF(21), vol ratio (vol/EMA)                    | Price-volume resonance & persistence                         | Indicator system           |
| **Trend strength**           | DMI/ADX (>25 = “trend regime”)                               | Organizational strength & alignment with price direction     | Indicator system           |
| **Vol & bands**              | ATR / nATR (%), KC upper/mid/lower                           | “Healthy” vs “outside-the-band” rhythm context               | Indicator system           |
| **Sentiment/Leverage**(opt.) | Fear & Greed, funding (median/extremes)                      | Surface sentiment & leverage cool-downs/overheats            | Indicator system           |

> ⛳️ **Unified calibration**: values/thresholds in reports come **only** from inputs + fixed rules. If something is missing, we **say “data not provided”** — we don’t guess.

------

## 🗂 5. What You’ll See

### 5.1 Market Overview (daily, free)

- **Macro 1-screen read**: MWI, NL7, DXY, reserves — synthesized
- **Bridge snapshot**: SMR / CUE / SLP transmission quality
- **Majors at a glance**: BTC/ETH/SOL/BNB posture + scoring summary
- **Three-scenario frame**: down / range / rebound — probabilities, time windows, *framework* triggers
- **Risk matrix**: macro, liquidity, technicals, sentiment, and events — concise

### 5.2 Single-Asset Deep-Dive (BTC/ETH free)

- **Dimension breakdown**: structure / MAs / momentum / flows / trend / vol / resonance
- **Indicator snapshot (last_closed)**: certainty only
- **Key-level heat**: S/R list + distance vs close
- **Multi-TF resonance**: W/D/H4 alignment & “reclaim/break” clauses
- **Scenario framing**: probability buckets, target zones, invalidations (**no trade advice**)

------

## ⚠️ 6. Disclaimer (must read)

- **No investment advice**: everything here (charts, tables, scores, scenarios) is for research/education only.
- **Learning/research use**: personal learning, academic discussion, and **non-commercial sharing**.
- **Strictly no commercial use**: **no** paid reprints, paid communities/courses/media, or any monetized redistribution **without written consent**. We reserve the right to pursue legal action **globally**.
- **Attribution**: non-commercial citations are welcome — keep the project name and repo link; avoid misleading excerpts.
- **Risk**: crypto assets are highly volatile; past ≠ future. You are solely responsible for your decisions.

------

## 🧭 7. Release

- **Frequency**: daily (UTC baseline); reports live under `<YYYY-MM-DD>` directories.
- **Visualization**: key plots (e.g., MA channel / momentum evolution / KC bands) are generated on build and embedded or linked by relative path.
- **Naming rules**:
  - Overview: `market_overview.md`
  - Single-asset: `<SYMBOL>.md` (e.g., `BTCUSDT.md`)
  - Languages: separate `CN/` and `EN/` folders; open an issue to request more languages

------

## 🤗 8. Contributing

- **Issues**: calibration, visualization, structure — all feedback welcome.
- **Tone**: **neutral, measured, evidence-first**. Fun is fine; avoid hype.
- **Scope**: no “signals,” position sizing, or risk advice PRs; no “call-out” content.

------

## ❓ 9. FAQ

**Q: Why do some cells say “data not provided”?**
 A: We prefer “no fill-in” to wrong numbers. We don’t guess.

**Q: Will you cover more assets?**
 A: Yes. We prioritize majors and high-liquidity names, then expand; community voting via Issues is welcome.

**Q: Why no “trade calls”?**
 A: Clear **reasoning** outlives point-in-time “levels.” Trading is personal; we focus on **evidence and frameworks**.

------

## 💬 10. Contact & Thanks

- Join the **Issues** for ideas / bug reports / requests
- If this helps, drop a **⭐ Star** — it fuels the daily grind
- Thanks to everyone using, critiquing, and contributing — **let’s co-build open crypto research infra** 🙌

------

## 📜 License

- Documents / reports / images / charts: **CC BY-NC-ND 4.0**

**Non-commercial · No derivatives · Attribution required.** Any commercial use without written permission is prohibited and may trigger legal actions.

------

> *“Decentralization doesn’t mean ‘no center’ — it means everyone can be a center.”*
>  May transparent methods light the way through volatility.
