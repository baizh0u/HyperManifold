# BNBUSDT Multi-Timeframe Market Analysis Report

**Pair**: BNBUSDT ｜ **Exchange**: binance  
**Analysis Time**: 2025-10-19T07:08:30.787000+00:00(UTC) ｜ **ASOF**: 2025-10-19T15:08:30+08:00(UTC+8)  
**Data Window**: Weekly 32 (to 2025-10-13T00:00:00) ｜ Daily 60 (to 2025-10-19T00:00:00) ｜ 4H 100 (to 2025-10-19T04:00:00)  
**last_closed (Only Closed Candles)**: W=2025-10-06T00:00:00 ｜ D=2025-10-18T00:00:00 ｜ H4=2025-10-19T00:00:00

---

## Core Conclusion

* **Market Status**: {{NEU:Range-bound}}  
* **Market Bias (For Reference Only)**: {{NEU:Range Waiting for Confirmation}}  
* **Confidence Level**: 48% ｜ **Composite Score**: -11/100  
* **Status Badges**: {{BULL:Bullish Alignment}} {{BEAR:OBV Breakdown}} {{NEU:High Volatility}}

**One-Sentence Summary**  
BNB’s mid-to-long-term structure remains in bullish alignment (price significantly above the 200-day MA), but after a recent pullback from highs, it has yet to regain the 20-day MA. Momentum and capital flows have weakened, with the 4-hour timeframe breaking below its own 200 MA and sitting under the KC midline, showing short-term pressure. Key evidence: 1) Daily close at 1092.430, below the 20-day MA (1163.360), above the 50/200-day MAs (1022.620/770.750); 2) Daily MACD above the zero line but with shrinking bars, RSI(14)=47.89 in the neutral zone; 3) Daily CMF(21)=0.0936 indicating light inflow, but OBV below its 9-day MA; 4) 4H OBV broke below EMA9, nATR≈3.23% (high), price within KC lower–mid range; 5) Macro NL7=-$44.3B (notably negative liquidity), TGA surge of +$57.9B reducing reserves, stablecoins saw only small net inflows over the past 3 days, weak transmission. Overall: Range-bound, watch for regaining the 20-day MA and 4H capital recovery.

---

## Key Indicator Snapshot

### Daily Snapshot (D, last_closed)

| Indicator                | Value                                | Threshold/Range       | Status Judgment          |
| ------------------- | ----------------------------------- | ----------------- | ----------------- |
| Close Price             | 1092.430                            | —                 | —                 |
| ΔMA20/50/200(%)     | -6.10% / +6.82% / +41.77%           | MA deviation (>0 above) | {{NEU:Medium}}          |
| MACD Bars / Zero Axis / Bar State | -23.0365 / Above Zero / Shrinking     | Above zero + Shrinking           | {{NEU:Neutral}}         |
| RSI(14)             | 47.89                               | 40–60 Neutral Zone   | {{NEU:Neutral}}         |
| ADX(14) / +DI / -DI | 29.00 / 20.89 / 32.15               | ADX>25 Trend       | {{NEU:Trend}}         |
| CMF(21)             | 0.0936                              | >0 Inflow          | {{BULL:Inflow}}        |

### 4H Snapshot (H4, last_closed)

| Indicator           | Value                                       | Threshold/Range    | Status Judgment         |
| ---------------- | ------------------------------------------ | --------- | -------------- |
| Close Price          | 1091.710                                   | —         | —              |
| ΔMA20/50/200(%)   | -2.21% / -6.82% / -0.09%                   | MA deviation  | {{NEU:Tangent}}       |
| OBV vs EMA9       | 293,481.29 / 309,942.58 (Breakdown)               | Cross Above/Below | {{BEAR:Outflow}}       |
| nATR(%)           | 3.23%                                      | 1–3 Healthy  | {{NEU:High}}        |
| KC Zone            | Lower to Mid                                  | Out-of-band/Midline etc.  | {{NEU:Regression}}       |

### Data Quality Notes
* Open Candles: W=Y ｜ D=Y ｜ H4=Y  
* Missing Fields: None  
* Skip Rules: Daily “20/50 Golden Cross Distance Threshold” and “MA50/MA200 Long-Period Slope Threshold” not provided → relevant specifics skipped in scoring; Weekly candle not closed → downweighted per rules.

---

## Dimension-Level Gauges

* Macro   [-3/12]  {{BEAR:Macro Tightening Bias}}  ★★☆☆☆  [███-------]
* Structure   [+2/13]  {{NEU:Structure Neutral to Bullish}}  ★★★☆☆  [████▎------]
* Moving Averages   [+12/20] {{BULL:MA Bullish Alignment}} ★★★★☆  [██████▎---]
* Momentum   [-6/18]  {{BEAR:Momentum Slightly Bearish}}    ★★☆☆☆  [██▎--------]
* Capital   [-3/15]  {{BEAR:Capital Neutral to Weak}} ★★☆☆☆  [██▎--------]
* Trend   [-2/10]  {{BEAR:Trend Transitional Weakness}} ★★☆☆☆  [██---------]
* Volatility   [-1/5]   {{NEU:Volatility High}}    ★★☆☆☆  [█----------]
* Confluence   [-4/7]   {{BEAR:Confluence Misaligned and Weak}} ★★☆☆☆  [██---------]

**Composite**  [-11/100]  {{NEU:Range-bound}}  ★★★☆☆  [████▏-----]

---

## Macro Environment Analysis

**Macro Transmission Summary**  
MWI=-2.7 (Tight bias) corresponds to macro score -3; NL7=-$44.3B shows net withdrawal, fiscal TGA weekly +$57.9B strongly absorbing reserves, RRP fell but insufficient to offset; stablecoins +$0.162B over last 3 days, SMR=8.21% ample but CUE notably negative, on-chain capital not effectively supporting prices → weak transmission, dampening risk appetite, confidence bonus = 0, minus 10% for 4H misalignment.

### Macro Liquidity Layer (Level & Structure)

| Indicator        | Current Value        | 7d Change        | Structure/Notes                | Impact Interpretation          |
| --------- | ---------- | ------------- | ------------------------ | --------------------- |
| MWI       | -2.7/10    | —             | Tight Bias                      | {{BEAR:Moderate Tightening}} → -3 |
| NL7($B)   | -44.321    | —             | Net withdrawal (Fiscal absorption dominant)        | {{BEAR:Risk Appetite Suppression}}     |
| RRP($B)   | 347.901    | -7.938        | Decline (Money market fund returns)         | {{NEU:Slight Benefit but Weak}}   |
| TGA($B)   | 851.952    | +57.898       | Strong fiscal absorption                 | {{BEAR:Reserve Drain}}       |
| Bank Reserves($B) | 2,988.202  | -45.653       | Buffer down                    | {{BEAR:Risk Appetite Repressed}}     |
| Central Bank Policy Tilt    | Hawkish/Tightening     | —             | Sticky core inflation, limited rate-cut room        | {{BEAR:Limited Easing Expectations}}     |

### Transmission Bridge Layer (Efficiency & Sync)

| Indicator               | Current Value/Notes                     | Threshold/Notes                         | Conclusion           | Confidence Impact |
| ---------------- | ---------------------------- | -------------------------------- | -------------- | --------- |
| Stablecoin Supply SLP(7d,$B) | Insufficient data; ~+0.162 over last 3 days   | >+1B Mild Inflow / <+0.5B Weak Inflow / Negative Outflow | {{NEU:Weak Inflow}}     | 0%        |
| Stablecoin Buffer SMR(%)     | 8.21                         | ≥8 Ample / 6–8 Normal / <6 Tight            | {{BULL:Ample}}      | +2%       |
| Capital Utilization CUE(%)      | ~-189.7 over last 3 days (Negative Efficiency)           | >+5 Efficient / ≈0 Neutral / <-5 Inefficient          | {{BEAR:Inefficient}}     | -5%       |
| Synchronization (NL7 vs SLP)  | NL7 Negative vs SLP Weak Positive               | Smooth/Decoupled/Double Negative/Inverse                | {{BEAR:Decoupled Lag}}    | -5%       |
| Transmission Lag             | 2–3 Weeks (Estimated)                  | 0–2 Fast / 2–4 Normal / >4 Blocked            | {{NEU:Normal Lag}}     | 0%        |

### External Constraints & Threshold Monitoring

| Indicator   | Current Value | Key Threshold/Level                  | Status         | Notes                    |
| ---- | --- | ------------------------ | ---------- | --------------------- |
| DXY  | 121.52 | 120 Key Level/MA Direction               | {{BEAR:Suppressive}}   | Strong USD suppressing risk appetite         |
| Watch Thresholds | —   | SLP7d > +$1B; NL7 > $20B/7d etc | {{NEU:Not Triggered}}  | Continue monitoring on-chain net inflow & fiscal injection    |

---

## Technical Dimension Scoring
Current weekly/daily structures are bullish but short-term momentum has weakened: Weekly bullish alignment, strong trend (ADX>40), capital flow & volume still supportive at weekly level; daily pulled back from highs, price below 20-day MA but markedly above 50/200-day MAs, MACD above zero line with shrinking bars, RSI back in neutral zone showing cooling momentum; 4H broke below its own 200 MA, OBV below EMA9, in KC lower-to-mid range with high nATR, short-term weak and not aligned with daily trend.

| Dimension      | Score     | Key Evidence (Threshold-based, may include specific values)                         |
| ------- | ------ | ------------------------------------------- |
| Price Structure & Patterns | +2/13 | Daily price significantly above 200-day MA (+41.77%), below 20-day MA (-6.10%); no clear classical pattern recently → +2 |
| Moving Average System    | +12/20 | MA20>MA50>MA200 bullish alignment; price above 200-day MA → +12 |
| Momentum Indicators    | -6/18  | Daily MACD above zero but shrinking bars; RSI14=47.89 in neutral zone; 4H MACD<Signal and RSI weak → -6 |
| Capital Flows    | -3/15  | Daily OBV below its 9-day MA; 4H OBV under EMA9; CMF(21)=0.0936 light inflow → -3 |
| Trend Strength    | -2/10  | Daily ADX=29 (trend zone but weakening), -DI dominates and below MA20 → -2 |
| Volatility & Position  | -1/5   | 4H nATR≈3.23% slightly above healthy; KC in lower-mid range → -1 |
| Multi-Timeframe Confluence   | -4/7   | Weekly/daily bullish, but 4H under its own MA200 with weaker capital, not aligned → -4 |

**Dimension Analysis**  
* Price Structure & Patterns: Long-term bullish position (above 200-day MA), but short-term pullback under 20-day MA; last 20 daily candles showed no high-confidence engulfing/morning/evening star patterns, neutral to range structure.  
* Moving Average System: MA20>MA50>MA200 maintains bullish alignment, 200-day MA trending upwards; this is the most stable positive factor currently.  
* Momentum Indicators: MACD above zero but shrinking bars, RSI falling from strong zone to neutral, short-term cooling; 4H momentum is bearish.  
* Capital Flows: Daily CMF light inflow, but OBV and 4H volume dynamics weakened (OBV breakdown), price-volume coordination lacking.  
* Trend Strength: ADX still in trend zone but weakening; directional divergence (-DI dominant aligns with short-term pullback).  
* Volatility & Position: 4H volatility high, KC midline below, short-term pressure risk.  
* Multi-Timeframe Confluence: 4H not aligned with daily, wait for 4H to return above MA20/MA50 with volume confirmation.

**Conflict Explanation**: Weekly/daily maintain bullish structure, but 4H weakening and below 200 MA; execution cadence anchored to 4H, waiting for alignment with daily.

---

## Price Levels & Relative Distance (Based on last_closed Data)

- **Close vs MA20/50/200 (D, last_closed)**:  
  Price below 20-day MA, above 50/200-day MAs; deviations: -6.10% / +6.82% / +41.77%.  
- **KC Position (H4, last_closed)**:  
  Lower-to-mid (Interpretation: Out-of-band = overspread; midline ≈ higher regression probability).  
- **Support/Resistance Heatmap (Daily Focus)**:  
  S1=1052.340 (4H KC lower) ≈ -3.67% from close; S2=1022.620 (50-day MA) ≈ -6.39%; S3=1021.000 (Recent daily low) ≈ -6.52%.  
  R1=1117.970 (4H KC mid) ≈ +2.33%; R2=1163.360 (20-day MA) ≈ +6.49%; R3=1318.260 (Recent daily high) ≈ +20.72%.  

---

## Candlestick Pattern Recognition
**Scan Range**: D=Last 60 closed candles, H4=Last 100 closed candles.

### Daily Patterns (D, latest)
| Latest Valid Pattern | Occurrence Time | Freshness | Direction | Notes |
| ------------ | -------- | ------ | ---- | ---- |
| None           | —        | —      | —    | No typical high-confidence engulfing/morning/evening star patterns (neutral structure) |

### 4H Patterns (H4, latest)
| Latest Valid Pattern | Occurrence Time | Freshness | Direction | Notes |
| :---------- | :------ | :---- | :-- | :-- |
| None          | —       | —     | —   | Structure: Last 5 candles: 1 bullish, 4 bearish; no break of prior high; broke prior low; avg body ≈41.3%; relative to KC: below midline |

---

## Key Price Level Analysis

### Support Levels (S)

| No. | Price (USDT) | Source/Method            | Use   | Historical Validity (Touch/Verify) | Confidence | Current Distance |
| -- | -------- | ------------------ | ------ | ------------ | ----- | ---- |
| S1 | 1052.340 | 4H KC Lower            | Dynamic Support | Multiple recent touches with regression        | Medium    | -3.67% |
| S2 | 1022.620 | Daily 50-day MA           | Trend Support | Mid-term MA support            | Medium    | -6.39% |
| S3 | 1021.000 | Recent Daily Low (10-17) | Swing Support | Recent low verified            | Medium    | -6.52% |

### Resistance Levels (R)

| No. | Price (USDT) | Source/Method      | Use   | Historical Validity (Touch/Verify) | Confidence | Current Distance |
| -- | -------- | ------------ | ------ | ------------ | ----- | ---- |
| R1 | 1117.970 | 4H KC Mid       | Dynamic Resistance | Multiple retracements suppressed            | Medium    | +2.33% |
| R2 | 1163.360 | Daily 20-day MA       | Trend Resistance | Key MA suppression            | High    | +6.49% |
| R3 | 1318.260 | Recent Daily High (10-14) | Volatility Resistance | High pullback origin            | Medium    | +20.72% |

**Reminder (Not Advice)**: Watch for {{BULL:Break Above R1}} and {{BULL:Regain 20-day MA (R2)}} confirmation; if {{BEAR:Break Below S1}}, watch for accelerated pullback.

---

## Future Scenario Analysis

**Scenario ①: Continued Upside**  
If technicals and capital recover, price likely to return to upper channel and push toward previous high zone.

| Element       | Content                                                         |
| -------- | ------------------------------------------------------------ |
| Probability       | 30%                                                          |
| Expected Window     | 3–5 Days                                                       |
| Trigger (Technical) | If: Daily close > R1(1117.970) and closes above 20-day MA(1163.360); 4H OBV back above EMA9 and price above MA20/MA50 |
| Trigger (Macro) | If: SLP7d > +$1B or DXY falls <120; or MWI > +3 and transmission efficiency score > 0 |
| Target/Range    | 1200–1220 (Initial), 1300–1320 (Extended)                          |
| Fail Condition     | 4H close < MA200(1092.700) or OBV breaks below EMA9 again              |

**Scenario ②: Range-bound**  
Price oscillates between key MAs and channel, waiting for momentum and capital direction.

| Element       | Content                                  |
| -------- | ------------------------------------- |
| Probability       | 45%                                   |
| Expected Window     | 1–2 Weeks                                 |
| Trigger (Technical) | If: S1 < Daily Close < R2(1163.360) and ADX(14) < 25    |
| Trigger (Macro) | No strong macro trigger; maintain NL7 negative without sustained on-chain inflow              |
| Target/Range    | 1050–1160 Range                         |
| Fail Condition     | {{BULL:Break/Above R2}} or {{BEAR:Break S1}}; or ADX>25 with +DI/-DI gap > 10 |

**Scenario ③: Weakening Pullback**  
If 4H remains misaligned with capital weakness, price likely to pull back further to lower support zone.

| Element       | Content                                                     |
| -------- | -------------------------------------------------------- |
| Probability       | 25%                                                      |
| Expected Window     | 2–3 Days                                                   |
| Trigger (Technical) | If: 4H close < MA200(1092.700) and MACD bars <0 and widening (Negative); Daily still below 20-day MA |
| Trigger (Macro) | If: SLP7d weakens or DXY continues strengthening; MWI drops further                     |
| Target/Range    | 1080–1050                                               |
| Fail Condition     | 4H close > MA20 and OBV>EMA9｜Daily effectively breaks R1 and regains 20-day MA        |

---

## Risk Warning

1. Weak trend phase + high volatility increases false breakout and retracement risk.  
2. Macro vs technical divergence (NL7 negative, CUE inefficient), short-term signals unclear, alignment needed.

---

## Monitoring Checklist (For Next Day/Next Session Review)

- **Volatility**: H4 nATR whether stays in 1–3% healthy range (Current: 3.23% → {{NEU:High}}).  
- **Momentum**: D RSI14 leaving 40–60 neutral zone (Current: 47.89 → {{NEU:Neutral}}); MACD zero line/bars (Current: Above Zero/Shrinking → {{NEU:Neutral}}).  
- **Volume**: H4 OBV vs EMA9 relation (breakdown), watch price-volume alignment.  
- **MA Structure**: D ΔMA20/50/200 expansion/contraction (-6.10% / +6.82% / +41.77%).  
- **Key Levels**: Watch S1/R1 triggers and fail conditions.

---

## Comparison with Yesterday: Change Attribution

**Overall Change**

* Composite Score: No historical report → -11 (First generation)  
* Status Tag: No historical report → Range-bound (First generation)  
* Confidence: No historical report → 48% (First generation)  
* Key Drivers: Short-term momentum & capital weakening, 4H misalignment lowering composite score.

**Dimension Score Change & Attribution**

| Dimension    | Yesterday  | Today  | Change  | Main Driver (Indicator Change) |
| ----- | --- | --- | --- | ------------ |
| Macro Liquidity | —   | -3  | —   | NL7 negative & TGA increase           |
| Transmission Efficiency  | —   | -6  | —   | Weak SLP, negative CUE             |
| Structure & Patterns  | —   | +2  | —   | Bullish position but short-term pullback          |
| MA System  | —   | +12 | —   | Stable bullish alignment                  |
| Momentum Indicators  | —   | -6  | —   | MACD bar shrinkage, RSI drop         |
| Capital Flows  | —   | -3  | —   | OBV breakdown, light CMF inflow            |
| Trend Strength  | —   | -2  | —   | ADX high-level decline                  |
| Volatility Position  | —   | -1  | —   | H4 nATR high                  |
| Multi-Timeframe Confluence | —   | -4  | —   | 4H not aligned with daily             |

**Top Change Indicators (≤10 Items)**

1. OBV vs EMA9 (H4): Above → Breakdown｜Interpretation: Volume confirmation weakening.  
2. RSI14 (D): Strong zone → Neutral｜Interpretation: Momentum cooling.  
3. MACD bars (D): Expansion → Shrinkage｜Interpretation: Trend momentum slowing.  
4. KC Position (H4): Upper → Below mid｜Interpretation: Short-term regression to suppressed zone.  
5. nATR (H4): Rise to ≈3.23%｜Interpretation: High volatility, beware of false breakouts.

**Pattern & Key Level Changes**

* Patterns: None forming with high confidence (Neutral structure).  
* Key Levels: R1 (4H KC middle) and S1 (4H KC lower) as short-term watch focus.

**Macro Transmission Efficiency Change**

* Yesterday: No historical report.  
* Today: MWI -2.7, SLP last 3 days +$0.162B, score -11 → Weak/decoupled transmission.  
* Impact: Confidence total -10% (Multi-timeframe misalignment penalty), macro bonus +5%.

---

## Report Notes

This report is generated by HyperManifold using multi-timeframe technical analysis & macro liquidity evaluation, **For Reference Only, Not Investment Advice**.  
Analysis Time: 2025-10-19T07:08:30.787000+00:00 ｜ Data Source: binance & ByBit ｜ Timeframes: Weekly / Daily / 4H

---