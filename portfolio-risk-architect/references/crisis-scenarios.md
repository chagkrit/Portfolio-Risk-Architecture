# Crisis Scenario Reference
*For stress test simulations — historical data, approximate, not forward projections*
*All figures: approximate peak-to-trough unless noted*

---

## Scenario 1: Global Financial Crisis (GFC) 2008–2009

**Trigger**: US housing collapse → banking system solvency crisis → global credit freeze

| Asset Class | Peak-to-Trough Return | Recovery Time |
|---|---|---|
| S&P 500 (US Equity) | -57% | 4.5 years |
| MSCI World (Intl Dev) | -54% | 5+ years |
| MSCI EM | -66% | 3 years |
| US REITs | -68% | 4 years |
| HY Bonds | -30% | 1.5 years |
| IG Bonds (AGG) | -4% (then +12% total yr) | Immediate |
| Long-term Treasuries (TLT) | +25% | N/A (benefited) |
| Gold | +25% | N/A (benefited) |
| Commodities | -50% | 2 years |
| BTC | Not applicable (didn't exist) | — |

**Key dynamics**:
- Credit markets seized → all "risk assets" sold simultaneously
- Equity-bond correlation went deeply negative (bonds were the hedge)
- Drawdown was slow and grinding over 17 months (Oct 2007 – Mar 2009)
- Recovery was also slow — S&P didn't recover until 2013

**Simulation assumption**: Apply these returns proportionally to portfolio.
60% equity / 40% IG bond portfolio ≈ -22% to -28% drawdown.

---

## Scenario 2: COVID Crash (March 2020)

**Trigger**: Global pandemic → economic lockdowns → liquidity panic

| Asset Class | Peak-to-Trough Return | Recovery Time |
|---|---|---|
| S&P 500 | -34% | 5 months |
| MSCI World | -33% | 6 months |
| MSCI EM | -31% | 6 months |
| US REITs | -41% | 1+ year |
| HY Bonds | -20% | 4 months |
| IG Bonds | -8% (brief spike) | 2 months |
| TLT (Long Treasury) | +20% initially, then sold | Recovery immediate |
| Gold | -12% initially, then +30% | Immediate, then rally |
| BTC | -50% in 2 weeks | 2 months |
| Commodities (Oil) | -80% (negative futures briefly) | 12+ months |

**Key dynamics**:
- Fastest bear market in history: -34% in 33 days
- V-shaped recovery equally fast due to massive fiscal/monetary stimulus
- Gold initial selloff (liquidity crunch) then massive rally
- BTC crashed faster than equities, then recovered faster

**Simulation assumption**: Apply peak-to-trough returns. 
60/40 portfolio ≈ -18% to -22% drawdown, recovered in ~5 months.

---

## Scenario 3: 2022 Rate Shock

**Trigger**: Highest inflation in 40 years → Fed hiking cycle → repricing of all assets

| Asset Class | Full Year 2022 Return | Notes |
|---|---|---|
| S&P 500 | -25% | Growth stocks worst |
| QQQ (Nasdaq) | -33% | Duration-sensitive growth |
| MSCI World | -18% | |
| MSCI EM | -20% | |
| AGG (IG Bond) | -13% | Worst bond year in decades |
| TLT (Long Treasury) | -31% | Duration destruction |
| HY Bonds | -11% | |
| US REITs | -26% | Rate sensitive |
| Gold | -2% (roughly flat) | Modest protection |
| Commodities | +16% | Energy/agriculture inflation hedge |
| BTC | -65% | Risk-off + leverage unwind |

**Key dynamics**:
- Traditional 60/40: ≈ -17% (historically rare negative for bonds AND equities)
- Equity-bond correlation turned POSITIVE for the year
- Only commodities and cash provided real protection
- Long-duration assets (TLT, growth stocks, REITs) hit hardest
- This scenario exposes "duration risk" hiding in bond allocations

**Simulation assumption**: Rate shock. Adjust by duration:
- Every 1yr of bond duration = ~1% loss per 1% rate increase
- Growth/tech stocks: apply 1.3–1.5x S&P 500 drawdown multiplier

---

## Scenario 4: August 2024 Yen Carry Unwind

**Trigger**: Bank of Japan rate hike → yen strengthened → global carry trade unwind

| Asset Class | Aug 5, 2024 Peak-to-Trough | Recovery |
|---|---|---|
| Nikkei 225 | -12% in single day | ~3 weeks |
| S&P 500 | -9% drawdown | ~2 weeks |
| VIX | Spiked to 65 (GFC levels intraday) | Days |
| MSCI EM | -8 to -10% | ~3 weeks |
| Momentum stocks | -12 to -15% | Slower |
| JPY/USD | +10% appreciation (yen strength) | Partial |
| BTC | -20% | ~2 weeks |
| IG Bonds | +2 to +3% (flight to quality) | — |

**Key dynamics**:
- Speed of shock: concentrated in ~3 days
- Carry trade unwind forced selling across all liquid risk assets
- Portfolios with momentum tilt, EM, and Japanese equity exposure hit hardest
- Illustrates "hidden leverage in the system" risk — non-obvious correlation sources

**Simulation assumption**: Short, sharp drawdown. 
Equity-heavy portfolio: -8% to -15% over 3–5 days, full recovery in 2–4 weeks.
This scenario has lower total damage but extreme short-term volatility (psychological risk).

---

## Using These Scenarios in Diagnosis

### How to Apply:

1. **Take portfolio holdings** post look-through
2. **Apply scenario returns** to each asset class proportionally
3. **Sum weighted losses** = estimated portfolio drawdown
4. **Adjust for correlations** (in crisis, correlations rise → less diversification benefit)
5. **Report**: est. max DD, time-to-recover reference, what held up vs what didn't

### Always state:
- These are **historical analogies**, not predictions
- Future crises may be driven by different factors (AI bubble? China conflict? Energy crisis?)
- Portfolio construction should be robust to scenarios we **haven't** seen yet
- Results labeled: *"est. historical analogy stress test — not a forecast"*

### Benchmark References (for comparison):
- 100% S&P 500: GFC -57%, COVID -34%, 2022 -25%
- 60/40 (VOO/BND): GFC -28%, COVID -20%, 2022 -17%
- Risk Parity (approx): GFC -20%, COVID -18%, 2022 -12% (but leveraged versions worse)
- 100% Cash: 0% in all scenarios, but -8% real return over time (inflation)
