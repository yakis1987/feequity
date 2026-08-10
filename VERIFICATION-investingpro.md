# InvestingPro · verification record

Every figure published on the feequity InvestingPro cluster traces to this file.
Nothing on any cluster page may state a number that does not appear here or in a
dated first-party source listed at the bottom.

- Product: InvestingPro, the premium subscription of Investing.com
- Session date: 10 August 2026
- Method: single logged-in session, one company followed through every tool in sequence
- Access: arranged through Datawave · no editorial review by Investing.com
- Anchor company: AAPL, used across the whole cluster for continuity
- Next scheduled re-check: 8 November 2026, or immediately on any interface change

---

## 1 · Session conditions

Apple traded between $313.33 and $306.24 across the session.

| Time | Price |
|---|---|
| Prior close, 3:59 PM | $313.33 |
| 9:52 AM | $306.24 |
| intraday | $306.31 |
| intraday | $306.52 |
| 11:55 AM | $306.87 |

Screenshots taken at different points in the session therefore differ by a few
dollars. This is disclosed on the page.

---

## 2 · Fair Value

| Item | Verified value |
|---|---|
| Fair Value average | $267.86 |
| Against price $306.31 | -12.5% (also observed -13.4% and -12.7%) |
| Uncertainty | LOW |
| Spread | $204.85 to $293.22 |
| Analyst mean target | $322.82 from 41 analysts, range $215 to $400 |
| Models active for AAPL | 14 |
| Templates in library | 19 |
| Earnings Power Value | unchecked by default, excluded from the calculation |
| Template freshness | all showed "Updated 16 hours ago", so daily refresh |

Individual model outputs:

DDM Stable Growth 204.85 · DDM Multi Stage 230.42 · Price/Book 255.68 ·
10Y DCF EBITDA 264.11 · 10Y DCF Revenue 266.24 · 10Y DCF Growth 267.86 ·
Price/Sales 273.08 · EV/Revenue 279.10 · P/E 281.06 · EV/EBITDA 281.35 ·
5Y DCF Revenue 281.69 · EV/EBIT 283.08 · 5Y DCF EBITDA 288.26 · 5Y DCF Growth 293.22

**Discrepancy on the record.** Investing.com brand documentation cites 17 models.
The product showed 14 active out of 19 available for this company. The count appears
to vary by company and data availability. Publish the counted number with the company
named, never a general claim.

---

## 3 · Financial Health

| Sub-score | Displayed | Actual | Sector range |
|---|---|---|---|
| Cash Flow | 3 | 2.81 | 0.24 to 5.00 |
| Growth | 3 | 3.16 | 2.00 to 5.00 |
| Price Momentum | 3 | 2.76 | 0.58 to 4.18 |
| Profitability | 4 | 4.43 | 2.26 to 5.00 |
| Relative Value | 1 | 1.26 | 0.04 to 5.00 |

- Scored against over 100 factors, versus Information Technology companies in
  developed markets. Relative, not absolute.
- AAPL scored a perfect 5.0 on Revenue Trend, Gross Profit Trend, Operating Income
  Trend and Total Debt Trend, while scoring 1.26 on Relative Value.

---

## 4 · WarrenAI

| Item | Verified value |
|---|---|
| Credit allowance | 500 per month on the tier tested |
| Used at capture | 10 |
| History ceiling stated in response footer | 10 years on Pro+ |

Interface disclaimer, as displayed: WarrenAI may provide incorrect information and is
never financial advice.

Figures cited inside the response: revenue growth 14.7% and EPS growth 19.5% forecast
FY2026 · EBITDA margin 34.8% · WACC 10.0% · P/E LTM 38.1x · forward P/E 35.1x ·
EV/EBITDA 26.4x · 1-year return 37.2% · FY2025 revenue $416.16B · Q3 EPS $2.02 against
$1.89 expected.

**Error found, reproducible.** The comparison table listed the analyst mean of $322.82
as -4.6% against the current price, while the commentary in the same row described mild
upside for analysts. At a price near $306, a $322.82 target is roughly +5%. The sign is
inverted and the table contradicts itself.

---

## 5 · Screener

| Item | Verified value |
|---|---|
| Universe | 152,080 instruments |
| Filters applied | Market Cap > $1,000m · Fair Value Upside > 15% · Sector Information Technology · Overall Health Score > 3 |
| Results | 94 matches |
| AAPL in results | no, consistent with its health scores |
| Metric categories | Growth, Efficiency, Financials, Forecast, Predictions, Health, Technical, ETF, Finance, Misc |
| Metric count | not displayed anywhere in the interface |

Two similarly named metrics exist. "Fair Value (InvestingPro)" filters on the dollar
figure; "Fair Value Upside (InvestingPro)" filters on the percentage gap. Selecting the
first produces a screen that filters essentially nothing.

Investing.com marketing cites 1,200+ metrics. Not verifiable in the product, therefore
not reproduced as fact anywhere in the cluster.

---

## 6 · Financials

Apple ten-year income statement, USD billions, FY2016 to FY2025.

| FY | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 |
|---|---|---|---|---|---|---|---|---|---|---|
| Total revenues | 215.6 | 229.2 | 265.6 | 260.2 | 274.5 | 365.8 | 394.3 | 383.3 | 391.0 | 416.2 |
| Revenue growth | -7.7% | 6.3% | 15.9% | -2.0% | 5.5% | 33.3% | 7.8% | -2.8% | 2.0% | 6.4% |

- Gross margin rose from 39.1% to 46.9% across the decade
- Operating income rose from 60.0 to 133.1
- Ten years is the ceiling, including on Pro+

---

## 7 · ProPicks AI

| Item | Verified value | How confirmed |
|---|---|---|
| Total strategies | 88 | pagination, 15 pages of 6 |
| US strategies | 10 | filtered to United States, 2 pages of 6 + 4 |
| Update cadence | monthly | picks updated 1 Aug 2026, next 1 Sep 2026 |

**Tech Titans (IT15)**

Total Return 13Y +3,387.1% · Outperformance +2,943.2% · Annualised +29.9% ·
Sharpe 0.98 · Risk Med · Backtest Start Date 1 Jan 2013 · Rebalance monthly ·
Size focus mid-cap · Trading region United States · Economic region developed ·
Max holdings 15 · Filters: avg daily volume > 1K, market cap > 1B, unadjusted close > 10.
August 2026 rebalance added HP Inc and Applied Materials, both marked Live; removed
Skyworks at -5.5% and Allegro at -11.9%.

**Beat the S&P 500 (SP20), flagship**

| Measure | Figure |
|---|---|
| Backtested total return | +1,229.0% |
| Backtested index return, same window | +443.9% |
| Backtested outperformance | +785.0% |
| Backtested annualised | +21.0% |
| Beta | 1.10 |
| **Live, one year** | **+17.8%** |
| **Live, five years** | **+83.7%** |

This pairing is the single most important fact in the cluster. Backtested and live
figures appear on every page separated, labelled and attributed, never merged.

**One-year returns, all ten US strategies**

Top Value Stocks +27.3% · Best of Buffett +11.8% · Energy Elite +55.2% ·
Financial Fortresses -4.8% · Quality Compounders +13.3% · Small-Cap Sprinters +62.6% ·
Healthcare Heroes +36.0% · Beat the S&P 500 +17.8% · Dominate the Dow +28.8% ·
Mid-Cap Movers +69.6%

Backtest start dates vary by strategy: 2013, 2015 or 2019.

---

## 8 · Investing.com's own disclosures

Investing.com publishes all of the following itself. Quoted accurately, attributed,
and used as context rather than as an accusation.

- Strategy page, on Tech Titans: the backtest shows how the selections would have
  performed over time
- Chart annotation: simulated on 1000, and past returns do not guarantee future results
- Methodology page: the chart illustrates the hypothetical historical performance of
  the flagship strategy
- FAQ: backtested results do not represent actual trades, only hypothetical trades
  based on historical data
- FAQ: backtesting can be adjusted until past returns seem optimal, so real-world
  results may differ
- FAQ names survivorship bias, look-ahead and restatement bias, and corporate actions,
  with mitigations, and concludes it is impossible to guarantee all biases have been
  eliminated
- Model training uses Google Vertex AI, over 25 years of purchased financial data and
  over 50 financial metrics

---

## 9 · Competitor prices, read at source 10 August 2026

Third-party review sites contradict each other on all of these. Only company-owned
pages are used.

| Tool | Published price | Source |
|---|---|---|
| Seeking Alpha Premium | $299 a year | Seeking Alpha subscription page |
| Seeking Alpha Alpha Picks | $499 a year | same |
| Seeking Alpha bundle | $798 list, $718 first year, then annual list price | same |
| Simply Wall St | no price shown to logged-out visitors | simplywall.st/plans |
| Koyfin Free | $0 | koyfin.com pricing guide, updated 27 Jul 2026 |
| Koyfin Plus | $39 a month billed annually, $468 a year | same |
| Koyfin Premium | $79 a month billed annually, $948 a year | same |
| Morningstar Investor | $249 a year or $34.95 a month | morningstar.com/mm |

Also recorded:

- Koyfin retired the Pro plan and moves existing Pro subscribers to Premium at the
  price they already pay, from 30 April 2026. Thirty day satisfaction guarantee.
- Simply Wall St terms state a discounted rate applies for the discounted period only,
  then reverts to standard pricing.
- Morningstar Investor has no free tier once the trial ends, per its help centre.
- Seeking Alpha Pro exists at a professional price point. Figures in circulation range
  from $1,800 to $2,400 and none could be read on a Seeking Alpha page, so no number
  is published.

---

## 10 · Figures deliberately not published

These circulate widely with no consistent source. None appears anywhere in the cluster.

| Claim | Values found in the wild |
|---|---|
| Monthly users | 46m · 50m · 60m · 100m |
| Paid subscribers | 150,000 · 300,000 |
| Instruments | 60,000 · 72,000 · 135,000 · 180,000 |
| Screener metrics | over 1,000 · 1,200+ · 12,000 |
| Ratings | 4.7/5 from 1.2M · 4.6/5 from 687K · Trustpilot around 3.8 |
| ProPicks flagship since Nov 2023 | 147.09% · 177% · 182.4% · 184.79% |
| Backtest since Jan 2013 | 1,052% · 1,076.5% · 1,595.3% |

House rule: cite the lowest figure from the most official source, or omit entirely.
In most cases omitting is better, because the figure adds nothing.

---

## 12 · Pricing, refunds and cancellation · read at source 10 August 2026

**Prices are not retrievable.** investing.com/pro/pricing returns no price in its server
HTML. The plan panel shows a loading state and the discount headline renders empty, then
fills client side and is localised by country and currency. A sale was live, branded as
the August sale, with a countdown. No InvestingPro price figure is published anywhere in
the cluster as a result. Figures found on affiliate pages on the same day ranged from
roughly $91 to roughly $293 a year, each with its own coupon code applied.

**Refunds · Investing.com support article, updated 9 August 2026.** InvestingPro services
are provided on a non-refundable basis. Cancellation is possible at any time, after which
the subscription does not renew beyond the current billing period, and paid access remains
active until that period ends.

**Refunds · Investing.com terms and conditions.** States in capitals that no refund is due
once the subscription is completed, that auto-renewal can be cancelled at any time, and
that by subscribing the member receives immediate access and waives any right of withdrawal.
The terms elsewhere allow cancellation of auto-renewal up to 24 hours before the billing date.

**The 7 day money-back guarantee is not corroborated.** It appears on multiple affiliate
pages. It does not appear in the official terms or in the official support article as of
10 August 2026. The non-refundable statement is what is published on the page. Recheck both
documents at the next 90 day pass before changing this.

**Cancellation path · support article.** InvestingPro homepage, username icon top right,
Plan Summary, Cancel Subscription. Deactivating or deleting the Investing.com account does
not cancel the subscription. App store purchases must be cancelled through the app store
that processed the payment.

**Metric counts, resolved.** Investing.com's own pricing page distinguishes 1,200+ stock
data metrics and 10 years of history across 72,000+ stocks from a screener that filters
through 167 metrics. The two are routinely conflated in third-party reviews. Our session
found no metric count displayed anywhere in the screener interface, which remains true.

**Other first-party claims on the pricing page, recorded not republished.** Averages 17
valuation models · 180,000+ instruments queried by WarrenAI · 25+ years of historical data ·
$4M a year data sourcing cost · 300K+ investors · 4.7/5 from 1.2M reviews · Trustpilot 4.1/5.
Our counted screener universe was 152,080 instruments and our counted active models for AAPL
was 14 of 19 available.

---

## 11 · Open, not yet verified

Nothing below may be stated on any page until it is read at its source and recorded here.

- InvestingPro price for every plan and billing term, from a live checkout, with the
  country and currency recorded alongside each figure
- Renewal price after the promotional term, from the small print under the checkout total
- Whether a 7 day guarantee is offered at checkout despite the published terms. If it is,
  screenshot the checkout screen: that becomes the source, and section 12 gets updated and
  dated rather than rewritten.
- Commission structure of the partnership
- Exact Pro versus Pro+ feature line, tier by tier

---

*Maintained by Jacob Shasha · feequity.com · created 10 August 2026 · sections 9 and 12 added 10 August 2026*
