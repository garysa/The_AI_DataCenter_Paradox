# 15 — Case Study: CoreWeave — The Pure-Play Warning

## What CoreWeave Is

CoreWeave is a cloud computing company that rents GPU clusters — primarily Nvidia H100s and
H200s — to AI companies that need massive compute capacity without building their own
infrastructure. It is the purest expression of the "build it and they will come" data centre
thesis: borrow money, buy GPUs, rent them out, collect the spread.

It is also the clearest early warning signal of what happens when that model meets reality.

---

## The IPO That Told You Everything

CoreWeave's March 2025 IPO was the most revealing corporate event in the AI infrastructure
story. The original plan: list at $35B valuation. The actual outcome: slashed to $23B before
listing, debuted at $40/share, briefly rocketed to ~$180 by summer 2025.

**By December 2025: down more than 60% from peak, trading around $68.**

The IPO filing contained the single most alarming sentence in any AI infrastructure
prospectus:

> *CoreWeave gets more than half its $1.9 billion in revenue from a single customer.*

That customer: **Microsoft.**

---

## The Numbers

| Metric | Value |
|--------|-------|
| Revenue at IPO filing | $1.9B |
| Revenue full year 2025 (guided) | $5.05–5.15B |
| Revenue backlog | **$55.6B** (nearly doubled quarter-over-quarter) |
| Microsoft share of contracts | **$10B of $17B booked contracts** |
| Meta deal | **$14.2B** compute capacity agreement |
| Total debt | **>$14B** |
| Debt due 2025 | $986M |
| Debt due 2026 | **$4.2B** |
| Net loss 2024 | $863M |
| Net loss Q3 2025 | $110M (improving) |
| 2025 capex | $12–14B |
| 2026 capex (projected) | **Well in excess of double 2025** — >$28B |

---

## The Business Model, Simplified

CoreWeave borrows money → buys Nvidia GPUs → rents GPU clusters to AI companies →
collects hourly rates → services debt from the spread.

The spread needs to be sufficient to:
1. Service $14B+ in debt at current rates
2. Fund $28B+ in 2026 capex
3. Eventually generate free cash flow

**The problem:** H100 rental rates fell 64% in 2025. CoreWeave's business model was
designed when H100 rates were $8/hr. They are now $2.85–$3.50/hr.

At $8/hr, the economics are marginal but plausible.
At $3.50/hr, the maths requires near-perfect utilisation and continued demand growth
just to service the debt — let alone generate a return.

---

## The Concentration Risk That Defines Everything

**More than half of revenue from Microsoft. $10B of $17B backlog from Microsoft.**

If Microsoft:
- Reduces its CoreWeave spend (it is simultaneously building its own data centres)
- Routes more workloads internally (Azure's own GPU clusters)
- Renegotiates contract rates downward (leverage increases as alternatives grow)

...CoreWeave's entire financial model is in jeopardy.

And Microsoft has every incentive to do all three. Microsoft is CoreWeave's landlord and
its largest tenant simultaneously — CoreWeave builds data centres, Microsoft fills them,
but Microsoft is also building competing capacity.

The Meta deal ($14.2B) provides some diversification, but Meta is pursuing the same
open-source strategy that reduces long-term third-party compute dependency.

---

## The Debt Maturity Cliff

| Year | Debt Due |
|------|----------|
| 2025 | $986M |
| 2026 | **$4.2B** |
| 2027+ | Remainder of $14B+ |

CoreWeave must refinance or service $4.2B in 2026 — at a time when:
- Its stock is down 60% from peak (equity raise expensive)
- AI infrastructure credit spreads are widening
- GPU rental rates are compressing margins
- Its primary customer (Microsoft) is building competing capacity

The $4.2B 2026 maturity is the cliff edge. If CoreWeave cannot refinance at reasonable rates,
the company faces a choice between equity dilution that destroys existing shareholder value
or a debt restructuring that impairs bondholders.

---

## What CoreWeave Got Right

CoreWeave is not a naive operation. It identified a genuine gap in the market (AI companies
needed GPU access faster than they could build data centres) and filled it at a critical moment.

Its technical execution has been competent:
- Deployed GPU clusters faster than hyperscalers in 2023–2024
- Built high-performance networking specifically for AI workloads
- Attracted top-tier customers (Microsoft, Meta, AI labs)

The business model was right for 2022–2024. The question is whether the window closed
before CoreWeave could achieve financial sustainability.

---

## The Specialisation Principle Applied to CoreWeave

CoreWeave is not a specialist in the sense that matters. It is a generic GPU rental
company. It has no proprietary data, no unique model capability, no enterprise software
moat. It is a commodity infrastructure provider in a market where:

- The commodity (GPU hours) is repricing to marginal cost as supply catches demand
- Its primary customer is also its primary competitive threat
- The technology it rents (H100s) is being superseded by B200s it must now also fund

The businesses that survive AI infrastructure shakeout are the ones with a *reason*
customers stay — data gravity, proprietary models, integration lock-in. CoreWeave has none.
It has contracts. Contracts end.

---

## Verdict: The Clearest Pure-Play Cautionary Tale

CoreWeave is what happens when the infrastructure investment thesis runs directly into:

1. GPU commodity price collapse (-64% in 18 months)
2. Customer concentration (>50% from one client)
3. Debt maturity mismatch (28B+ 2026 capex against $4.2B 2026 maturities)
4. Primary customer building competing capacity

It will either be acquired (most likely by Microsoft, completing the vertical integration)
or it will restructure its debt under pressure in 2026–2027.

**CoreWeave is the canary. Watch it carefully. What happens to CoreWeave in 2026 is
the preview of what happens to the broader pure-play AI infrastructure sector in 2027–2028.**

---

## Sources
- [Yahoo Finance/Fortune: CoreWeave files for IPO, reveals >50% revenue from single customer](https://finance.yahoo.com/news/ai-startup-coreweave-files-2025-030641690.html)
- [Fortune: CoreWeave earnings — $56B contracted revenue, but guidance drops](https://fortune.com/2025/11/10/coreweave-earnings-infrastructure-debt-ai-bubble/)
- [Level Headed Investing: When Growth Runs on Debt — the CoreWeave Case Study](https://www.levelheadedinvesting.com/p/when-growth-runs-on-debt-the-coreweave-case-study)
- [Baptista Research: CoreWeave Stock Forecast 2026 — how debt and delays crushed the IPO dream](https://baptistaresearch.com/coreweave-stock-forecast-2026-ai-debt-crash/)
- [Sacra: CoreWeave revenue, valuation & funding](https://sacra.com/c/coreweave/)
- [Financial Content: CoreWeave results as bellwether for infrastructure supercycle](https://markets.financialcontent.com/stocks/article/marketminute-2026-2-20-the-ai-pulse-check-coreweave-results-loom-as-bellwether-for-infrastructure-supercycle)
