# Stock Analysis · verification record

Every figure published on feequity about stockanalysis.com traces to this file.
Nothing on any page may state a number that does not appear here or in a dated
first-party source listed at the bottom.

- Product: Stock Analysis (stockanalysis.com), free tier and its published paid plans
- Session dates: 14 and 15 August 2026
- Method: single logged-in free account, one company followed through the same tools
  used across the InvestingPro cluster, then a non-US listing for coverage
- Access: **free account, opened by us. No affiliate relationship exists with this
  product as of 16 August 2026, and none has been applied for.** If that changes, the
  access log gets a second dated row and both rows stay
- Anchor company: AAPL, the same anchor used across the whole site, so every figure
  here is directly comparable to `VERIFICATION-investingpro.md`
- Next scheduled re-check: 12 November 2026, or immediately on any interface change

**Scope limit.** Everything below was observed on a free account. Statements about
what a paid plan contains are taken from the product's own pricing page, not from
inside a paid account. That distinction is held throughout and is the reason
`STOCKANALYSIS-PROTOCOL.md` exists.

---

## 1 · Session conditions

| Item | Value |
|---|---|
| Anchor price, AAPL | $305.53 |
| Observed at | 15:24 EDT, 14 August 2026 |
| Account state | logged in, free tier, no trial active |

The anchor price is load-bearing. Two percentages recorded below are computed by the
product against the live price, so they only reconcile against this figure.

---

## 2 · Screener, counted by hand

| Item | Verified value |
|---|---|
| Total metrics | **313** across 29 categories |
| Locked on the free tier | **14**, which is 4.47% of 313 |
| Marketing claim on the same product | "300+ indicators" |

**The claim holds.** 313 counted against 300+ advertised. Recorded because the house
method is to count first and report the result either way, not only when it fails.

**What the 14 locked metrics are, by group**

| Group | State on free |
|---|---|
| Fair Value | locked in full · Lynch, Graham, both Upside figures, WACC |
| Top Analyst layer | all four locked |
| Ten year windows | Average PE, Dividend Growth and OCF Growth locked. 1Y, 3Y and 5Y free |
| Risk ratios | Sharpe and Sortino locked |

The pattern is worth stating plainly: the free tier is generous on breadth and gates
on valuation output and long windows. That is a different shape of limit from a row
cap or a results cap.

**Unresolved.** Clicking any locked metric leads to the generic pricing page. **Neither
published plan states which one unlocks Fair Value.** This could not be resolved from
outside a paid account and is carried to section 8.

---

## 3 · Financial history and the second lock layer

| Item | Verified value |
|---|---|
| Financial statement history, free | **five years** |
| 10Y and Max tabs | both redirect to the pricing page |
| Second, less visible layer | operating metrics tables gate older columns independently |
| Worked example | Gross Margin by Type readable back to March 2025 only |

The second layer matters more than the first. A reader who sees five years of income
statement reasonably assumes five years applies everywhere. It does not. The operating
metrics tables cut off far more recently, and nothing in the interface announces it.

---

## 4 · Pricing, as published · read at source 14 August 2026

| Plan | As displayed |
|---|---|
| Pro, annual | $79 a year, presented as $6.58 a month |
| Pro, monthly | $9.99 a month, stated on the same page as $119.88 a year |
| Saving, as printed by the product | $40.88 |
| Unlimited | $16.58 a month, billed annually |

**The arithmetic checks out.** 79 ÷ 12 = 6.583. 9.99 × 12 = 119.88. 119.88 − 79 = 40.88.
All three figures the product prints are internally consistent, which is not the norm
in this category and is worth saying.

**Computed, not observed:** 16.58 × 12 = $198.96 a year for Unlimited. The annual total
was not displayed. Marked as derived and not to be published as an observed price.

**Prices were read logged out and in a single country.** No currency localisation test
was run. Do not state these as the price a reader will see until that is checked.

### Refunds

| Item | Verified value |
|---|---|
| Stated policy | 60 day money back |
| Placement | shown **twice** on the pricing page |
| Path | cancel button in the account area, plus email to support |
| Merchant of record | Paddle |

**This is published policy, not tested behaviour.** Nobody has requested a refund and
observed what happens. Until that exists, the site may describe what the product
publishes and may not describe how it performs. That gap is the entire justification
for the paid session in `STOCKANALYSIS-PROTOCOL.md`, and it applies to every product on
the site equally, none of which has been cancelled first-hand.

---

## 5 · Company data, AAPL

| Item | Verified value |
|---|---|
| FY2025 revenue | $416.16B |
| Agreement | matches WarrenAI and matches the filing |
| TTM revenue | $466.82B |
| Analyst coverage | 46 analysts |
| Mean price target | $322.28 |
| Upside displayed | +5.48% |

**The upside reconciles exactly.** 322.28 against the anchor price of $305.53 is
+5.482%. The percentage is computed off the live price, which also confirms the anchor
timestamp in section 1.

---

## 6 · Coverage outside the US

Tested on adidas, Xetra listing, 15 August 2026.

| Item | Verified value |
|---|---|
| Page state | full page returned, denominated in euros |
| Filings | German filings present |
| Analyst coverage | 30 analysts |
| Gap | **no operating metrics tab** |
| Gap | **volume unavailable** |

Non-US coverage exists and is real, but it is thinner than the US page in two specific
ways. Both are named above rather than summarised, because "thinner" without the
specifics is not a checkable statement.

---

## 7 · Named data sources and one bug

| Surface | Sources named by the product |
|---|---|
| US company pages | S&P Global and CBOE |
| German company page | S&P Global and Financial Modeling Prep |
| Operating metrics | TipRanks |

The source set changes by geography and by module. A reader comparing a US figure to a
German one is not comparing like with like, and the product does say so if you look.

**Bug observed, 15 August 2026.** In the ASML metrics, "Value of Booked Systems" appears
duplicated. Not present on AAPL. Recorded as observed on one company on one date, with
no claim about how widespread it is.

---

## 8 · Cross-product comparison, and its limits

| Figure | Stock Analysis | InvestingPro |
|---|---|---|
| AAPL mean price target | $322.28 · 14 Aug 2026 | $322.82 · 10 Aug 2026 |
| | | $322.28 on the sidebar · 11 Aug 2026 |
| Analyst count | 46 | 41 · 10 Aug 2026 |
| AAPL FY2025 revenue | $416.16B | $416.16B |

**Read this carefully before publishing anything from it.**

The targets were captured on **different dates**, so this is not a same-day comparison
and cannot be presented as one. Analyst targets move.

What is notable is narrower: the target figure InvestingPro showed on its sidebar on
11 August, $322.28, is identical to the figure Stock Analysis showed on 14 August, while
the analyst counts differ, 41 against 46. Identical means to two decimal places on the
same company.

**Two readings are open and neither is established.** Either the two products draw on an
overlapping estimate set and count contributors differently, or it is coincidence across
dates. **Nothing may be published on this until both are read on the same day, on the
same company, with both timestamps recorded.** That is a fifteen minute task and it is
in section 9.

A separate and firmer point, already recorded in `VERIFICATION-investingpro.md` section
4: InvestingPro itself displayed $322.82, $322.53 and $322.28 across 10 and 11 August.
The internal inconsistency inside one product is the stronger finding and does not
depend on any cross-product claim.

**Where the two agree, they agree exactly.** FY2025 revenue matches to the cent between
both products and the filing. That is the more common outcome and is recorded so the
file is not only a list of discrepancies.

---

## 9 · Open, not yet verified

Nothing below may be stated on any page until it is read at its source and recorded here.

- **Which paid plan unlocks Fair Value.** Unresolved from outside a paid account
- **Same-day capture of the AAPL analyst target and analyst count** on both products,
  with both timestamps, to resolve section 8
- Currency and country localisation of the published prices
- Whether the 60 day refund performs as published, including reply time and elapsed
  time to the money arriving
- Export limits on Pro, stated as one download a day on the pricing page and untested
- Screener universe size. **Not counted.** The InvestingPro record has 152,080 and the
  Finviz count has 11,566, so this gap is visible in any comparison
- Whether Stock Analysis accepts affiliates based in Israel

---

## 10 · Figures deliberately not published

- **$198.96 a year for Unlimited.** Computed from the monthly figure, never displayed.
  Held here as a derivation only
- Any statement about what a paid tier contains, beyond what the pricing page itself
  states. The account tested was free

---

## Sources read at source

| Source | Date read |
|---|---|
| stockanalysis.com company page, AAPL, logged in free | 14 August 2026 |
| stockanalysis.com screener, logged in free | 14 August 2026 |
| stockanalysis.com pricing page | 14 August 2026 |
| stockanalysis.com refund and cancellation terms | 14 August 2026 |
| stockanalysis.com company page, adidas, Xetra | 15 August 2026 |
| stockanalysis.com company page, ASML | 15 August 2026 |

---

*Maintained by Jacob Shasha · feequity.com · created 16 August 2026 from a session run
14 and 15 August 2026 · next re-check 12 November 2026*
