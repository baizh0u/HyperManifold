# SOLUSDT Multi-Timeframe Market Analysis Report

**Pair**: SOLUSDT ｜ **Exchange**: binance  
**Analysis Time**: 2025-10-19T07:11:32.822000+00:00(UTC) ｜ **ASOF**: 2025-10-19 15:11:32(UTC+8)  
**Data Window**: Weekly 32 (to 2025-10-13T00:00:00) ｜ Daily 60 (to 2025-10-19T00:00:00) ｜ 4H 100 (to 2025-10-19T04:00:00)  
**last_closed (only closed candlesticks)**: W=2025-10-06T00:00:00 ｜ D=2025-10-18T00:00:00 ｜ H4=2025-10-19T00:00:00

---

## Core Conclusion

* **Market Stance**: ⚪ Consolidation  
* **Market Bias (for reference only)**: ⚪ Range-bound awaiting confirmation  
* **Confidence**: 64% ｜ **Composite Score**: -28/100  
* **Status Badges**: ⚪ Multi-timeframe divergence ｜ 🔴 Daily momentum weakening ｜ ⚪ nATR Healthy

**In One Sentence**  
SOL is currently in multi-timeframe divergence: weekly prices remain above long-term moving averages (above 200-week), but the daily timeframe turned into a pullback since mid-October, with price consistently below the 20/50-day MAs, MACD histogram extending below the zero line, RSI(14) near the lower bound of neutral, and +DI/-DI showing bears in control. On the 4H chart, prices have slightly retaken the 20 MA but remain below the 50/200 MAs; OBV broke below the 9-period average, and short-term structure has yet to confirm an upward move. On the macro side, NL7 is significantly negative (-$44.3B) with a strong USD backdrop, stablecoins only slightly net increasing and capital usage efficiency negative, with weak transmission efficiency. Overall score is -28, labeled as consolidation, with the next step to watch if daily can reclaim R1 with volume recovery.

---

## Key Indicator Snapshot

### Daily Snapshot (D, last_closed)

| Indicator               | Value                                                        | Threshold/Range     | Status Judgment       |
| ----------------------- | ------------------------------------------------------------ | ------------------- | --------------------- |
| Close Price             | 187.560                                                     | —                   | —                     |
| ΔMA20/50/200(%)         | -10.47 / -12.94 / +7.65                                     | Distance from MA (>0 above) | 🔴 Weak               |
| MACD Histogram / Zero Line / Histogram Status | -3.19 / Below zero / Expanding                          | Below zero + expanding | 🔴 Bearish Bias        |
| RSI(14)                 | 41.58                                                       | 40–60 Neutral zone  | ⚪ Neutral             |
| ADX(14) / +DI / -DI     | 23.34 / 13.93 / 26.76                                       | ADX>25 Trend        | ⚪ Transitional        |
| CMF(21)                 | 0.0901                                                      | >0 Inflow           | 🟢 Inflow              |

### 4H Snapshot (H4, last_closed)

| Indicator               | Value                                                        | Threshold/Range    | Status Judgment        |
| ----------------------- | ------------------------------------------------------------ | ------------------ | ---------------------- |
| Close Price             | 187.040                                                     | —                  | —                      |
| ΔMA20/50/200(%)         | +0.27 / -1.87 / -12.94                                       | Distance from MA   | ⚪ Neutral              |
| OBV vs EMA9             | 102,254,086.79 / 102,304,574.30 (breakdown)                  | Breakout/breakdown/high-low | 🔴 Outflow             |
| nATR(%)                 | 2.85                                                        | 1–3 Healthy range  | ⚪ Healthy              |
| KC Zone                 | Lower to mid band                                            | Outside/mid etc    | ⚪ Reverting            |

### Data Quality Notes
* Open candles: W=Y ｜ D=Y ｜ H4=Y  
* Missing fields: None  
* Skip rules: None

---

## Dimension Level Gauge

* Macro    [-3/12]  🔴 Tight  ★★☆☆☆  ████▏□□□□□  
* Structure [-6/13]  🔴 Pullback Bias  ★★☆☆☆  ███□□□□□□  
* MA       [-4/20]  🔴 System Weakening  ★★☆☆☆  ███▎□□□□□□  
* Momentum [-7/18]  🔴 Bearish momentum  ★★☆☆☆  ███▉□□□□□□  
* Capital  [0/15]   ⚪ Neutral  ★★★☆☆  █████□□□□  
* Trend    [-3/10]  🔴 Weak Trend  ★★☆☆☆  ███▏□□□□□□  
* Volatility [+1/5] ⚪ Healthy  ★★★☆☆  █████□□□□  
* Resonance [-3/7]  🔴 Multi-timeframe incoherence  ★★☆☆☆  ███▏□□□□□□  

**Composite**  [-28/100]  ⚪ Consolidation  ★★☆☆☆  ███▌□□□□□□

---

## Macro Environment Analysis

**Macro Transmission Summary**  
MWI=-2.7 → Macro tightening (score -3); NL7 at -$44.321B significantly negative (fiscal absorption dominant), stablecoins have only slightly net increased over the last 3 days (+$0.162B) and capital usage efficiency is negative; transmission efficiency score -3 shows on-chain capital failing to effectively support price, overall confidence remains medium in a consolidation environment.

### Macro Liquidity Layer (Level & Structure)

| Indicator     | Current Value | 7d Change | Structure/Definition    | Brief Impact Interpretation |
| ------------- | ------------- | --------- | ----------------------- | --------------------------- |
| MWI           | -2.7/10       | —         | Tight                    | Score -3 (bearish)          |
| NL7($B)       | -44.321       | —         | Negative pulse           | Risk appetite under pressure|
| RRP($B)       | 347.901       | -7.938    | Release (return)         | Marginal positive but insufficient |
| TGA($B)       | 851.952       | +57.898   | Drain (absorption)       | Obviously tight              |
| Bank Reserves($B) | 2,988.202 | -45.653   | Reserve decline           | Risk appetite drop           |
| CB Policy Tilt | Tightening/Hawkish | —   | Core inflation sticky     | Valuation under pressure     |

### Transmission Bridge Layer (Efficiency & Synchronization)

| Indicator             | Current Value               | Judgment Threshold/Definition  | Conclusion   | Confidence Impact |
| --------------------- | --------------------------- | ------------------------------ | ------------ | ----------------- |
| Stablecoin Supply SLP(7d,$B) | Insufficient data (last 3 days +0.162) | >+1B moderate / <+0.5B weak/negative | Weak inflow | 0%                |
| Stablecoin Buffer SMR(%)    | 8.21                      | ≥8 Ample / 6–8 Normal / <6 Tight | Ample        | +0%               |
| Capital Utilization CUE(%)  | Negative efficiency over last 3 days | >+5 Efficient / ≈0 Neutral / <-5 Negative | Negative efficiency | -                 |
| Synchrony (NL7 vs SLP)      | Negative vs weak positive | Smooth/decoupled/double negative/reverse | Decoupled lag | -                 |
| Transmission Lag            | 2–4 weeks                | Experience-based                | Normal lag   | 0%                |

### External Constraints & Threshold Monitoring

| Indicator | Current Value | Key Thresholds/Levels      | Status       | Notes                     |          |            |
| DXY       | 121.52        | MA20/MA50/key ranges       | 🔴 Suppression | Strong USD suppressing risk appetite |          |            |
| Watch Threshold | —     | SLP7d > +$1B, NL7 > $20B/7d etc | ⚪ Not reached | Watch fiscal and RRP path  |          |            |

---

## Technical Dimension Scoring
Weekly remains in long-term bullish structure (price above 200-week MA, MA20/50 above), but the last two weeks show +DI/-DI momentum weakening, ADX ~16 in a weak trend zone; daily has stayed below the 20/50-day MAs since the steep drop on 10-10, MACD histogram extending below zero, RSI(14) near lower neutral bound, +DI/-DI bears dominant; 4H short-term recovery near 20 MA but still below 50/200, OBV broke below 9-period MA, making reversal confirmation difficult. Momentum and MA systems drag scores down, while capital (daily CMF > 0) and healthy nATR provide some buffer.

| Dimension         | Score   | Key Evidence (threshold-based, may include specific values) |
| ----------------- | -------| ------------------------------------------------------------ |
| Price Structure & Patterns | -6/13 | Daily consistently below 20/50-day MA; bearish engulfing on 10-10 (Volume Ratio=2.31>1.3) → -2; recent multiple breaks below critical levels (MA20/KC mid band) → -4 |
| MA System         | -4/20  | Daily 20/50 death cross (above 200-day MA) → -2; MA20<MA50 and price below both → system weakening → -2 |
| Momentum Indicators | -7/18 | MACD below zero and histogram extending (-3.19, below zero “expanding”) → -5; RSI(14)=41.58 near lower neutral bound → -2 |
| Capital Flow      | 0/15   | Daily up-move on lower volume (Volume Ratio=0.43) → -5; CMF(21)=0.0901 > +0.05 inflow → +5 |
| Trend Strength    | -3/10  | ADX(14)=23.34 (transitional) and -DI(26.76) > +DI(13.93) aligned with price direction → -3 |
| Volatility & Position | +1/5 | 4H nATR=2.85% in healthy band; KC “lower to mid band” → +1 |
| Multi-timeframe Resonance | -3/7 | Weekly bullish bias, daily bearish bias; 4H failing to reclaim 50/200 MAs and OBV breakdown → -3 |

**Dimension Analysis**

* Price Structure & Patterns: Daily pullback structure maintained after the large bearish candle on 10-10, with bearish engulfing and volume spike, followed by multiple closes below MA20 and KC mid band, bearish structure.  
* MA System: Daily 20/50 death cross formed, price below both, shifting from strong to weak; still above 200-day MA but recovery not yet seen.  
* Momentum Indicators: MACD below zero with histogram continuing, RSI(14) near lower neutral bound, bearish momentum but not extreme.  
* Capital Flow: Daily CMF > 0 shows capital inflow, but lower volume on up moves and weakening OBV limit price elasticity.  
* Trend Strength: ADX in 20–25 transitional zone, -DI leading and aligned with downtrend, trend not strong.  
* Volatility & Position: 4H volatility within healthy band, neutral position (lower to mid KC band), higher chance of reversion but lacking confirmation pattern.  
* Multi-timeframe Resonance: Weekly long-term bullish bias diverges from daily pullback; 4H not effectively repaired, short-term direction still uncertain.

**Conflict Explanation**: Weekly maintains long-term bullish structure, but daily and 4H have weakened; execution mainly follows daily as lead, with 4H used for timing confirmation. Treat as range-bound until R1 breakout.

---

## Price Levels & Relative Distances (Based on last_closed Data)

- **Close vs MA20/50/200 (D, last_closed)**:  
  Price below 20/50-day MAs and above 200-day MA; deviations: -10.47% / -12.94% / +7.65%.  
- **KC Position (H4, last_closed)**:  
  Lower to mid band (Interpretation: outside = overspread; near mid = higher reversion probability).  
- **Support/Resistance Heatmap (Daily as main)**:  
  S1=174.250 (200-day MA, distance 7.09%) ｜ S2=171.280 (KC lower band, distance 8.68%) ｜ S3=168.790 (Recent 20-day low, distance 10.01%)  
  R1=203.690 (KC mid band, distance 8.59%) ｜ R2=209.610 (20-day MA, distance 11.76%) ｜ R3=215.380 (50-day MA, distance 14.83%)

---

## Candlestick Pattern Recognition
**Scan Range**: D=Last 60 closed candles, H4=Last 100 closed candles. If no effective pattern, note “No typical patterns formed recently (neutral structure)”.

### Daily Pattern (D, latest)

| Latest Effective Pattern | Date       | Freshness | Direction | Notes |
| ------------------------ | ---------- | --------- | --------- | ----- |
| Bearish Engulfing        | 2025-10-10 | Recent    | Bearish   | Volume ratio=2.31>1.3, body engulfed prior day, pullback confirmed; reclaiming R1 may weaken pattern effect |

### 4H Pattern (H4, latest)

| Latest Effective Pattern | Date | Freshness | Direction | Notes |
| ------------------------ | ---- | --------- | --------- | ----- |
| None                     | —    | —         | —         | Structure: last 5 candles 3 up/2 down; no new high; made new low; avg body ≈42.0%; KC: below mid band |

---

## Key Level Analysis

### Supports (S)

| #  | Price(USDT) | Source/Definition         | Use           | Historical Effectiveness (Touches/Validation) | Reliability | Current Distance |
| -- | ----------- | ------------------------- | ------------- | ---------------------------------------------- | ----------- | ---------------- |
| S1 | 174.250     | Daily 200-day MA          | Key support   | Multiple recent approaches without valid break | High        | 7.09%            |
| S2 | 171.280     | Daily KC lower band       | Dynamic channel support | Signs of rebound at lower channel in last 20 days | Medium      | 8.68%            |
| S3 | 168.790     | Daily recent low (10-10)  | Swing point support | Stage low formed after large bearish candle    | Medium      | 10.01%           |

### Resistances (R)

| #  | Price(USDT) | Source/Definition     | Use           | Historical Effectiveness (Touches/Validation) | Reliability | Current Distance |
| -- | ----------- | --------------------- | ------------- | ---------------------------------------------- | ----------- | ---------------- |
| R1 | 203.690     | Daily KC mid band     | Trend reversion resistance | Multiple recent failed holds after retest     | Medium      | 8.59%            |
| R2 | 209.610     | Daily 20-day MA       | Trend resistance | Key resistance in pullback phase               | High        | 11.76%           |
| R3 | 215.380     | Daily 50-day MA       | Mid-term resistance | Need breakout with volume to turn stronger    | High        | 14.83%           |

**Reminder (Not Advice)**: Watch for R1(203.69) breakout and S1(174.25) breakdown with close and volume confirmation.

---

## Future Scenario Analysis

**Scenario ①: Continuation Uptrend**  
If technical/capital conditions improve, price may test mid-term resistances.

| Element             | Content                                                     |
| ------------------- | ----------------------------------------------------------- |
| Probability         | 32%                                                          |
| Expected Window     | 3–5 Days                                                     |
| Trigger (Technical) | IF: Daily close > R1(203.69) AND 4H OBV > EMA9 AND Daily MACD histogram turns positive |
| Trigger (Macro)     | IF: SLP7d > +$1B or DXY falls below MA20; or MWI > +3 and transmission score > 0 |
| Target/Range        | 209.6–215.4                                                  |
| Invalidation        | Daily close < 193 with Volume Ratio >1.2 or 4H breakdown below OBV MA |

**Scenario ②: Range Consolidation**  
Remain between key supports and resistances, awaiting directional confirmation.

| Element             | Content                                                     |
| ------------------- | ----------------------------------------------------------- |
| Probability         | 45%                                                          |
| Expected Window     | 1–2 Weeks                                                    |
| Trigger (Technical) | IF: S1 < daily close < R1 AND ADX(14) < 25                   |
| Trigger (Macro)     | No strong macro trigger                                      |
| Target/Range        | 174–204                                                      |
| Invalidation        | Breakout above R1 with increasing volume or breakdown below S1 with ADX>25 and -DI dominant |

**Scenario ③: Weakening Pullback**  
Short-term rebound fails, price resumes testing lower supports.

| Element             | Content                                                     |
| ------------------- | ----------------------------------------------------------- |
| Probability         | 23%                                                          |
| Expected Window     | 2–3 Days                                                     |
| Trigger (Technical) | IF: 4H close < 4H MA50(190.60) AND MACD histogram continues shrinking <0 |
| Trigger (Macro)     | IF: SLP7d weakens or DXY continues strengthening             |
| Target/Range        | 171–175                                                      |
| Invalidation        | 4H close > 4H MA20(186.54) AND OBV>EMA9 ｜ Daily holds above R1 |

---

## Risk Warnings

1. In weak-trend phases, false breakout risk is high; wait for close and volume confirmation.  
2. Macro-technical divergence (negative NL7 but weak stablecoin inflow), directional signals unclear.

---

## Watchlist (For next day/next session review)

- **Volatility**: Whether H4 nATR stays in the 1–3% healthy band (Current: 2.85% → ⚪ healthy).  
- **Momentum**: Whether D RSI14 exits 40–60 neutral zone (Current: 41.58 → ⚪ neutral); MACD status (Current: below zero/expanding → 🔴 bearish bias).  
- **Volume**: H4 OBV vs EMA9 relationship (breakdown), check if price-volume align.  
- **MA Structure**: Whether D ΔMA20/50/200 expand/contract (-10.47%/-12.94%/+7.65%).  
- **Key Levels**: Watch if S1/R1 triggers or invalidations are met.

---

## Daily Comparison: Change Attribution

**Overall Changes**

* Composite Score: — → -28 (Δ -28)  
* Stance Label: — → Consolidation (new)  
* Confidence: — → 64% (Δ —)  
* Core Driver: Since 10-10, daily momentum continued weakening with MA system death cross, macro transmission weak and risk appetite suppressed.

**Dimension Score Changes and Drivers**

| Dimension      | Yesterday | Today | Change | Main Driver (Key Indicator Changes) |
| -------------- | --------- | ----- | ------ | ------------------------------------ |
| Macro Liquidity| —         | -3    | —      | MWI=-2.7, NL7 significantly negative |
| Transmission Efficiency | — | -3 | —      | SMR ample but CUE negative, SLP weak |
| Structure Pattern | —      | -6    | —      | Bearish engulfing + key level break  |
| MA System      | —         | -4    | —      | 20/50-day MA death cross              |
| Momentum Indicators | —   | -7    | —      | MACD histogram below zero continuing, RSI decline |
| Capital Flow   | —         | 0     | —      | CMF>0 offsetting weak volume          |
| Trend Strength | —         | -3    | —      | ADX transitional, -DI leading         |
| Volatility Position | —    | +1    | —      | nATR in healthy band                  |
| Multi-timeframe Resonance | — | -3 | —      | Weekly/daily divergence, 4H not repaired |

**Top Changing Indicators (≤10 items)**

1. MACD histogram: -3.61 → -3.19 (moving towards zero but still negative) ｜ Conclusion: Bearish momentum not yet repaired.  
2. RSI(14): 45.56 → 41.58 ｜ Conclusion: Near lower neutral bound, risk appetite weakening.  
3. ΔMA20: -3.81% → -10.47% ｜ Conclusion: Widening deviation from short-term MAs.  
4. OBV vs EMA9 (H4): Above → Breakdown ｜ Conclusion: Short-term capital confirmed weakening.  
5. ADX(14): 21.61 → 23.34 ｜ Conclusion: Transitional zone, trend not strengthening.  
6. CMF(21): 0.0666 → 0.0901 ｜ Conclusion: On-chain capital still marginally inflowing.  
7. nATR(4H): 2.85% (unchanged) ｜ Conclusion: Volatility healthy.  

**Pattern & Key Level Changes**

* Pattern: Bearish engulfing formed (10-10), no effective repair pattern seen thereafter.  
* Key Levels: Multiple tests of KC mid band and 20-day MA failed, resistance effect notable.

**Macro Transmission Efficiency Changes**

* Yesterday: —; Today: MWI -2.7, SLP last 3 days +$0.162B, chart score -28 → transmission weak/decoupled.  
* Impact: Confidence 0% (transmission contribution neutral).

---

## Report Notes

This report is produced by HyperManifold based on multi-timeframe technical analysis and macro liquidity assessment, **for reference only, not investment advice**.  
Analysis Time: 2025-10-19T07:11:32.822000+00:00 ｜ Data Source: binance & ByBit ｜ Timeframes: Weekly / Daily / 4H

---