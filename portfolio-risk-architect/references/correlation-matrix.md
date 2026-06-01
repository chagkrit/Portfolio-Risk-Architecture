# Asset Class Correlation Reference
*Historical ranges — approximate, normal market regime unless noted*
*Source: approximate based on 2000–2024 historical data. Always verify with current data.*

## Pairwise Correlation Matrix (Normal Regime)

|           | US Eq | Intl Eq | EM Eq | IG Bond | HY Bond | Gold  | REITs | Cmdty | BTC  |
|-----------|-------|---------|-------|---------|---------|-------|-------|-------|------|
| US Eq     | 1.00  | 0.80    | 0.70  | -0.10   | 0.60    | 0.05  | 0.65  | 0.20  | 0.30 |
| Intl Eq   |       | 1.00    | 0.80  | -0.05   | 0.55    | 0.10  | 0.60  | 0.25  | 0.25 |
| EM Eq     |       |         | 1.00  | -0.05   | 0.50    | 0.15  | 0.55  | 0.35  | 0.35 |
| IG Bond   |       |         |       | 1.00    | 0.30    | 0.20  | 0.10  | -0.05 | 0.00 |
| HY Bond   |       |         |       |         | 1.00    | 0.00  | 0.55  | 0.25  | 0.25 |
| Gold      |       |         |       |         |         | 1.00  | 0.10  | 0.25  | 0.15 |
| REITs     |       |         |       |         |         |       | 1.00  | 0.15  | 0.20 |
| Cmdty     |       |         |       |         |         |       |       | 1.00  | 0.15 |
| BTC       |       |         |       |         |         |       |       |       | 1.00 |

## Crisis Regime Adjustments (Correlation Shifts)

During severe risk-off events (GFC 2008, COVID crash 2020):
- US Eq ↔ Intl Eq: rises from 0.80 → **0.92–0.95**
- US Eq ↔ EM Eq: rises from 0.70 → **0.85–0.90**
- US Eq ↔ HY Bond: rises from 0.60 → **0.75–0.85** (high yield acts like equity)
- US Eq ↔ Gold: drops from 0.05 → **-0.10 to -0.20** (flight to safety)
- US Eq ↔ IG Bond: drops from -0.10 → **-0.30 to -0.50** (flight to quality)
- US Eq ↔ BTC: rises from 0.30 → **0.60–0.80** (liquidity crunch → sell everything)

**Key insight**: HY bonds and international equities provide almost no diversification
in the worst 5% of market outcomes. Gold and long-duration Treasuries are the
reliable safe havens (though both failed simultaneously in 2022).

## 2022 Rate Shock — Unique Correlation Breakdown

In 2022, the traditional equity-bond negative correlation **broke down**:
- US Equities: -25% (S&P 500)
- AGG (IG Bond): -13% (worst bond year in decades)
- 60/40 Portfolio: ~-17% (historically rare)
- Gold: roughly flat (0%)
- Commodities: +15–20% (inflation regime)

This illustrates the "correlation is regime-dependent" risk. Traditional diversification
failed because the driver was inflation + rate hikes, which hurt BOTH equities and bonds.

## Within-Equity Correlations (US, approx)

| Comparison | Normal | Crisis |
|---|---|---|
| S&P 500 vs QQQ | 0.93 | 0.95 |
| S&P 500 vs SCHD | 0.80 | 0.85 |
| S&P 500 vs Small Cap (IWM) | 0.80 | 0.88 |
| QQQ vs SCHD | 0.72 | 0.80 |
| US Eq vs Intl Eq (VEA) | 0.80 | 0.92 |

**Key insight**: VOO + QQQ in a portfolio adds almost no diversification —
0.93 correlation means they move together 99% of the time in practice.

## Factor Correlations

| Factor | Correlation with Market (Beta) |
|---|---|
| Momentum | +0.8 to +1.0 (amplifies in bull, crashes harder) |
| Value | +0.7 to +0.9 |
| Quality | +0.6 to +0.8 |
| Low Volatility | +0.6 to +0.7 (better drawdown protection) |
| Size (Small Cap) | +0.8 to +0.9 |

## Effective Number of Bets (ENB) Benchmarks

For reference:
- Pure 100% equity portfolio: ENB ≈ 1–2 (effectively one bet)
- 60/40 traditional: ENB ≈ 2–3
- True risk parity (equal-risk): ENB ≈ 4–5
- Maximum diversification: ENB ≈ 5–8 (with uncorrelated alternatives)

Most retail portfolios claiming "diversification" land at ENB ≈ 1.5–2.5.
