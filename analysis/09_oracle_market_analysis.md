# 09 — Oracle: What the Market Really Thinks

## The Stock Is Telling a Different Story to the Backlog

The headline numbers look extraordinary: $523 billion in contracted backlog, cloud
infrastructure growing 68% year-on-year, GPU revenue up 177%. Yet the stock has collapsed
**more than 55% from its September 2025 high of $345.72** to approximately $148 by February 2026.

The death cross (50-day MA crossing below 200-day MA) formed **January 9, 2026**.
The bond market is pricing Oracle's debt as if it were **already a junk issuer**.
Barclays has warned cash could run out by **November 2026**.

The market is telling Ellison something he doesn't want to hear: the backlog is not the same
as money in the bank.

---

## Market Snapshot: February 2026

| Metric | Value |
|--------|-------|
| Share price (Feb 20, 2026) | **$148.08** |
| 52-week high | $345.72 (Sept 2025) |
| Decline from peak | **~57%** |
| Technical indicator | **Death Cross** (Jan 9, 2026) |
| Analyst consensus | Buy (32 analysts) |
| Average analyst price target | **$301.81** — 103% upside implied |
| Lowest analyst target | $175 (RBC Capital) |
| Highest analyst target | $400 |
| 5-year credit default swap spread | **125+ basis points** — highest since 2009 |

**The analyst consensus says "buy." The bond market says "panic."**
The gap between those two signals is the core of Oracle's dilemma.

---

## What the Credit Markets Are Saying: The Real Oracle Risk

### The Ratings Picture

| Agency | Rating | Outlook |
|--------|--------|---------|
| Moody's | Baa2 (investment grade — just) | **Negative** |
| S&P | BBB (investment grade — just) | **Negative** |
| Bond market implied | **Below investment grade** | — |

Both Moody's and S&P have Oracle at the very bottom of investment-grade territory with
negative outlooks. One notch down at either agency is **junk status** — a designation that
would force institutional investors (pension funds, insurance companies, sovereign wealth
funds) to sell Oracle bonds under their mandates.

**Moody's specifically flagged:**
- Oracle's adjusted **debt-to-EBITDA above 4×**
- Trailing **free cash flow at -$5.1 billion** (as of May 2025)
- **"Significant counterparty risk"** from the $300B OpenAI contract
- Risk of an "extended period of high leverage and negative cash flow"

**The bond market is not waiting for Moody's:**
Oracle bonds are already trading at **junk-equivalent spreads in the secondary market**.
The credit default swap (CDS) spread has widened to 125+ basis points — levels not seen
since the 2009 financial crisis. The market has effectively pre-priced a downgrade.

### The Barclays Cash-Out Warning

In November 2025, Barclays' fixed income research team dropped the most alarming single
datapoint about Oracle's situation:

> **"Even if capital expenditure is not increased further, Oracle's cash will be depleted
> by November 2026."**

Analyst Andrew Keches downgraded Oracle's debt to "Underweight" (equivalent to "sell").
The sensitivity analysis showed:
- Oracle generates negative free cash flow
- Cash reserves deplete within 12 months at then-current capex
- The only path forward: **Oracle must access capital markets continuously, every quarter**

Oracle's response was swift and revealing. In early 2026, Oracle announced an **Equity and
Debt Financing Plan for Calendar Year 2026**, committing to raise up to **$50 billion in
combined debt and equity**. A single bond deal priced at **$25 billion** — one of the
largest corporate bond offerings in history — was completed to address the immediate concern.

**Bank of America Research called this "the key risk going into 2026, defused."**

**The market's response: Oracle stock dropped another 12% in 5 days.**

The market's message: raising $25B in bonds to fund capex is not a sign of strength. It is
a sign that the business model cannot self-fund its ambition. Every dollar borrowed at
current spreads is a dollar that must be repaid with interest before the OpenAI revenue
actually flows.

### The Leverage Comparison That Should Frighten Investors

| Company | Debt-to-Equity | Cash Liquidity Buffer |
|---------|---------------|----------------------|
| Oracle | **500%** | ~$10–11B |
| Amazon | 50% | Large |
| Microsoft | 30% | Very large |
| Meta | Low | ~$80B |
| Google | Very low | ~$70B+ |
| Oracle (off-balance sheet) | $100B+ in lease commitments | Not reflected above |

Oracle's leverage ratio is not just high for a tech company — it is **10× worse than Amazon**
and **16× worse than Microsoft**. And that is before accounting for the $100 billion+ in
long-term data centre lease commitments that sit off-balance-sheet.

---

## The Moat the Market Is Discounting

Here is where the market may be wrong — or at least, where there is a genuine bull case.

### What Oracle Actually Knows That AWS Doesn't

Ellison's bet is not a random punt on AI infrastructure. It is built on a specific theory
of competitive advantage that is rooted in Oracle's 47-year history:

**1. Data Gravity — The Stickiest Moat in Enterprise Tech**

Fortune 500 banks, hospitals, retailers, and manufacturers run on Oracle Databases.
These databases contain decades of transaction history, financial records, and operational
data. Moving them is not merely expensive — in many cases it is **operationally suicidal**.
The costs of migration, retraining, recertification, and regulatory compliance are so high
that customers simply do not move.

This creates an asymmetric opportunity: Oracle can embed AI **directly inside the database**,
where the data already lives, eliminating the need to copy, move, or expose sensitive data
to external AI services. Competitors (AWS, Azure, GCP) have to ask customers to bring their
data to the cloud. Oracle can bring AI to the data in place.

Oracle 23 AI introduces **automatic data vectorisation** — transforming existing Oracle
database records into AI-ready formats without manual engineering work. No competitor
offers this as a native database feature.

**2. The Multicloud Play — Inside the Enemy's House**

Oracle has done something strategically audacious: it signed deals to **embed OCI hardware
directly inside Microsoft Azure and Google Cloud data centres**. This means:
- Customers can use OpenAI (on Azure) while keeping their sensitive data on Oracle's faster,
  more secure database clusters
- Oracle collects revenue from customers who don't even think of themselves as "Oracle cloud"
  customers
- Oracle bypasses the sales friction of competing with hyperscalers — it co-exists with them

This is not a posture of weakness. It is a recognition that data gravity is a stronger
competitive weapon than raw compute capacity.

**3. The Inference Bet vs. The Training Bet**

While hyperscalers competed on AI training (where you need the biggest, densest clusters
and can tolerate high latency), Oracle is positioning on **AI inference** — running AI models
against real enterprise data in production. Inference is:
- Where the actual revenue is generated (every API call in production)
- Where latency and data proximity matter more than raw training throughput
- Where Oracle's database integration is a genuine differentiator

SemiAnalysis (a respected GPU/cloud research firm) published: **"How Oracle Is Winning the
AI Compute Market"** — validating that Oracle's networking architecture provides measurable
performance advantages for inference workloads specifically.

**4. Network Performance — Provable Advantage**

Oracle claims its RDMA networking configuration delivers **2× the speed at half the cost**
of competitors for distributed AI workloads, and gives a **20% CapEx advantage** over
major cloud competitors for comparable workloads. These claims have been partially validated
by independent benchmarking, particularly for large-scale GPU cluster interconnect
performance.

---

## The Risk/Reward Ratio: What Serious Investors Are Calculating

### The Bull Thesis (Why 32 Analysts Say Buy, Average Target $301)

| Assumption | Bull Value |
|-----------|-----------|
| $523B backlog converts at 70% | ~$366B in revenue over 5–7 years |
| OCI margins reach 30–40% | $109–146B in operating profit over period |
| Enterprise database moat holds | Existing $50B+/yr software revenue protected |
| Stock implied on fundamentals | $300–400 target range |

The bull argues: Oracle is trading at a multi-year low precisely at the moment its backlog
has never been higher and its strategic positioning has never been stronger. If the OpenAI
contract delivers even 60% of its value, and OCI enterprise growth continues at 50%+, the
current stock price represents a once-in-a-decade buying opportunity.

### The Bear Thesis (Why the Bond Market Is Pricing Distress)

| Risk | Bear Impact |
|------|------------|
| OpenAI fails / restructures | $300B RPO collapses; Oracle stranded with $50B/yr capex and no revenue |
| Cash runs out by Nov 2026 | Forced equity dilution or asset sales; current shareholders wiped down |
| Junk downgrade triggered | Forced selling by investment-grade bond mandates; cost of debt surges |
| Rubin generation makes current clusters obsolete | Long-term leases become stranded costs |
| Competitor undercutting | AWS/Azure price wars erode OCI's 20% cost advantage |

The bear argues: Oracle is a 47-year-old enterprise software company that has never
successfully built a cloud business from scratch (it tried, and failed, repeatedly before
2023). It is now borrowing at 500% debt-to-equity to build data centres for a company
(OpenAI) that burns $9 billion per year and will not be profitable until 2029–2030.
The enterprise moat is real but declining as competitors embed AI into their own databases.
At some point the market wakes up to the difference between RPO and cash.

---

## When Will Investors and Banks Bail? The Trigger Map

### Trigger 1: Cash Depletion (Critical — November 2026 Risk Window)

Oracle has partially addressed this with the $25B bond issuance. But the structural problem
remains: **capex of $50B/yr against negative free cash flow is not self-sustaining**.

**If OCI revenue growth slows below 40% in any quarter of 2026:**
→ The refinancing assumption breaks down
→ Credit markets widen spreads further
→ Oracle faces a debt spiral: higher rates → higher costs → lower FCF → higher rates

**Trigger threshold**: Two consecutive quarters of OCI growth below 40% would likely
trigger a wave of institutional selling and potential debt downgrade.

### Trigger 2: Moody's/S&P Junk Downgrade (Catastrophic — Forced Institutional Selling)

Oracle's bonds are rated Baa2/BBB — one notch above junk. Both agencies have negative
outlooks. A downgrade to Ba1/BB+ would:

- Force **mandatory selling** by pension funds, insurance companies, and sovereign wealth
  funds that can only hold investment-grade bonds
- Trigger **covenants** in Oracle's existing credit facilities, potentially accelerating
  debt repayment
- Raise Oracle's **cost of debt dramatically** — making the already-negative FCF worse

**Trigger threshold**: Leverage staying above 4× EBITDA for two consecutive reporting periods,
or FCF failing to improve toward positive by FY2027, would likely trigger the downgrade.

### Trigger 3: OpenAI Distress Signal (Existential — Cascading Collapse)

If OpenAI:
- Misses its FY2026 revenue target of $20–26B
- Faces a major investor pullout or Microsoft relationship deterioration
- Publicly renegotiates its Oracle contract terms

Then Oracle's $523B backlog becomes fictitious overnight. The market has already partially
priced this — the stock's 57% fall from peak correlates exactly with growing scrutiny of
OpenAI's ability to pay for compute at the scale contracted.

**Yahoo Finance headline says it directly: "Oracle made a $300 billion bet on OpenAI.
It's paying the price."**

**Trigger threshold**: Any OpenAI earnings or funding announcement suggesting the company
cannot service $60B/yr in compute costs (its projected compute bill under the Oracle
contract) would immediately cascade into Oracle's equity and debt.

### Trigger 4: Competing Hyperscaler Undercutting (Slow Bleed — 12–24 Month Risk)

AWS, Azure, and Google are not standing still. All three are:
- Building custom AI silicon (reducing Nvidia dependency and cost)
- Developing native database-AI integration features that compete with Oracle's moat
- Offering multi-year capacity contracts to enterprise customers on competing terms

If any major hyperscaler offers a provably better price/performance ratio for enterprise
AI inference workloads — backed by equivalent database integration — Oracle's pipeline
of new enterprise OCI conversions slows dramatically. The existing customer base stays
(switching costs), but growth flatlines.

**Trigger threshold**: OCI losing two or more major enterprise contract competitions to
hyperscalers in a single quarter, reported via earnings commentary or public disclosures.

### Trigger 5: Regulatory/Political Reversal (Black Swan — Low Probability, High Impact)

The Stargate project has presidential backing. That protection is not permanent.
If:
- The next administration takes a different view of AI infrastructure tax treatment
- Environmental regulations impose carbon/energy taxes on data centres
- Antitrust action targets the OpenAI-Oracle-Microsoft relationship

...then the entire financial model (which depends on regulatory goodwill for permitting,
power contracts, and tax treatment) becomes suspect.

**Trigger threshold**: Unpredictable, but the 2026 US midterms are a natural inflection
point for policy risk reassessment.

---

## The "Industry It Knows" Advantage: Is Oracle's Moat Real Enough?

The market's key question is whether Oracle's enterprise software advantage can actually
protect the AI infrastructure investment — or whether it is a comfortable story that obscures
a fundamentally broken capital structure.

**The moat IS real. The question is whether it is big enough.**

Oracle's enterprise database moat has endured for 47 years. It survived the client-server
to internet transition. It survived the SaaS wave (Salesforce, Workday) by migrating to
cloud itself. It survived the AWS hyperscaler wave by offering multicloud deployments.

But each transition took **5–10 years** and enormous capital to navigate.

Oracle is now making a bet that the AI transition will be faster — that the $523B in
contracted backlog will generate cash before the $90B+ in debt matures and before the
$50B/yr capex burns through the balance sheet.

The timing is extraordinarily tight. Barclays says cash runs out in November 2026 at
current trajectory. Oracle has partially addressed this with the $25B bond offering. But
the structural gap between "backlog" and "cash in hand" remains.

**Larry Ellison's personal position:**
He owns ~41% of Oracle — approximately $60B worth at current prices (down from ~$100B+
at the September peak). His personal paper loss in 5 months was approximately $40 billion.
He has not sold. His incentives are precisely aligned with the bull case. He is not
someone who bets against himself.

But Oracle also has $4.2B/yr in share buybacks. At the moment it most needs to conserve
cash, it is returning capital to shareholders — a tension that bond markets have noticed.

---

## The Bottom Line: When Do Banks and Investors Exit?

**Banks (bond market):** They have partially already exited — Oracle bonds trade at
junk-equivalent spreads despite investment-grade ratings. The formal exit event (a ratings
downgrade forcing mandatory selling) is estimated **6–18 months away** if:
- OCI growth slows below 40%
- FCF does not turn positive by FY2027
- OpenAI shows any distress signal

The $25B bond issuance buys time through approximately mid-2026. The next critical window
is **Q3 FY2026 earnings (approximately March 2026)** and **Q4 FY2026 (June 2026)** — the
two quarters that will determine whether OCI revenue growth is accelerating toward the
trajectory needed to justify the capex.

**Institutional equity investors:** Already rotating. The stock's 57% decline from peak
reflects institutional holders reducing positions. Quantitative funds moved to "sell/neutral"
after the death cross. Value investors are holding, watching for a bottom. The next capitulation
event would be a combination of a junk bond downgrade AND a material OpenAI revenue
disappointment — a scenario that could push Oracle toward $100–120/share, at which point
the distressed-value investors and private equity buyers start circling.

**The one scenario where nobody exits:**
OCI revenue accelerates to 80%+ growth in 2026 (driven by Stargate coming online and
OpenAI's revenue also accelerating toward $20B+), Oracle's FCF turns positive by FY2027,
and Rubin-era hardware contracts are signed before B200 clusters show obsolescence.
In that scenario, the $523B backlog begins visibly converting to cash, ratings agencies
reverse their negative outlooks, and Oracle enters 2027 as arguably the most important
infrastructure company in the world.

Ellison's entire bet — with $40 billion of his own wealth behind it — is that this is
exactly what happens.

---

## Sources

- [Bloomberg: Oracle Bonds Trade Like Junk as Spreads Widen](https://www.bloomberg.com/news/articles/2025-12-12/oracle-bonds-trade-like-junk-as-spreads-widen-debt-risk-flares)
- [Bloomberg: Oracle's Debt Unlikely to Trigger Cut to Junk Grade, UBS Says](https://www.bloomberg.com/news/articles/2026-01-06/oracle-s-debt-unlikely-to-trigger-cut-to-junk-grade-ubs-says)
- [Barclays / Tiger Brokers: Barclays Downgrades Oracle's Debt — Cash Could Run Out by November 2026](https://www.itiger.com/news/1140122171)
- [Futunn: Oracle's CDS surge as Barclays downgrades debt rating](https://news.futunn.com/en/post/64756366/oracle-s-credit-default-swaps-surge-as-barclays-downgrades-its-debt-rating)
- [Vogon Today: Oracle drowns in data center debt — Barclays "Junk Bond Risk"](https://www.vogon.today/economic-scenarios/the-first-crack-in-the-ai-boom-oracle-drowns-in-data-center-debt-barclays-warns-junk-bond-risk/2025/11/12/)
- [Investing.com: Oracle's credit ratings affirmed amid AI infrastructure expansion](https://www.investing.com/news/stock-market-news/oracles-credit-ratings-affirmed-amid-ai-infrastructure-expansion-93CH-4253750)
- [Yahoo Finance: Moody's flags significant counterparty risk for Oracle's $300B OpenAI contract](https://finance.yahoo.com/news/moody-ratings-flags-significant-counterparty-145930979.html)
- [AInvest: Moody's Downgrades Oracle's Credit Rating Due to High Counterparty Risk](https://www.ainvest.com/news/moody-downgrades-oracle-credit-rating-due-high-counterparty-risk-2509/)
- [Investing.com: Moody's revises Oracle's outlook to negative](https://www.investing.com/news/stock-market-news/moodys-revises-oracles-outlook-to-negative-amid-ai-expansion-93CH-4155891)
- [NewsAirInsight: Will Moody's and S&P reclassify Oracle's bonds as junk?](https://newsairinsight.com/why-is-oracles-credit-risk-surging-in-late-2025-will-moodys-and-sp-reclassify-oracles-bonds-as-junk-debt-key-points-investors-need-to-know-news-air-insight/)
- [IFR: Oracle makes new pledge on soaring debt to halt brutal selloff](https://www.ifre.com/bonds/2357470/oracle-makes-new-pledge-on-soaring-debt-in-a-bid-to-halt-brutal-selloff)
- [Fortune: Oracle defused key risk — but market isn't buying it](https://fortune.com/2026/02/03/oracle-debt-openai-stock-movement-key-risk-hyperscaler-market/)
- [PR Newswire: Oracle announces Equity and Debt Financing Plan for 2026](https://www.prnewswire.com/news-releases/oracle-announces-equity-and-debt-financing-plan-for-calendar-year-2026-302675778.html)
- [Yahoo Finance: Oracle to Raise Up to $50 Billion in Debt and Equity This Year](https://finance.yahoo.com/news/oracle-raise-50-billion-2026-235033434.html)
- [Financial Content: Oracle ORCL Forms Bearish Death Cross](https://markets.financialcontent.com/wral/article/marketminute-2026-1-9-oracle-orcl-forms-bearish-death-cross-as-massive-ai-capex-weighs-on-investor-sentiment)
- [Yahoo Finance: Oracle stock just made a Death Cross — should Ken Fisher be worried?](https://finance.yahoo.com/news/oracle-stock-just-made-death-160110139.html)
- [Investing.com: Oracle Selloff Tests Confidence in $523B Cloud Backlog](https://www.investing.com/analysis/oracle-selloff-tests-confidence-in-523-billion-cloud-backlog-200674345)
- [Trefis: Is The Selloff In Oracle Stock Justified?](https://www.trefis.com/stock/orcl/articles/585008/is-the-selloff-in-oracle-stock-justified/2025-12-10)
- [Motley Fool: Down 40%, This Growth Stock Could Be Set for Recovery](https://www.fool.com/investing/2025/12/29/down-big-oracle-growth-stock-recover-buy-2026/)
- [Yahoo Finance: Oracle made a $300B bet on OpenAI. It's paying the price.](https://finance.yahoo.com/news/oracle-made-a-300-billion-bet-on-openai-its-paying-the-price-205441863.html)
- [Intuition Labs: Oracle & OpenAI's $300B Deal Analysis](https://intuitionlabs.ai/articles/oracle-openai-300b-deal-analysis)
- [AInvest: Oracle's AI Infrastructure Play — High-Risk, High-Reward](https://www.ainvest.com/news/oracle-ai-infrastructure-play-high-risk-high-reward-bet-openai-debt-fueled-growth-2512/)
- [Medium/Ben Goodman: How Will OpenAI Pay For Their $300B Oracle Contract?](https://medium.com/@hello_9187/how-will-openai-pay-for-their-300-billion-oracle-contract-2357307ca322)
- [SemiAnalysis: How Oracle Is Winning the AI Compute Market](https://semianalysis.com/2025/06/30/how-oracle-is-winning-the-ai-compute-market/)
- [Futurum: Oracle AI World 2025 — Is the Database the Center of the AI Universe Again?](https://futurumgroup.com/insights/oracle-ai-world-2025-is-the-database-the-center-of-the-ai-universe-again/)
- [Valuentum: Oracle Has Turned Into a Net Debt Heavy, Free Cash Flow Burning Enterprise](https://www.valuentum.com/articles/oracle-has-turned-into-net-debt-heavy-free-cash-flow)
- [Tomasz Tunguz: Is Your AI Funded by Junk Bonds?](https://tomtunguz.com/is-your-ai-funded-by-junk-bonds/)
- [Medium/Mike Tseng: Is Oracle's Spread Widening a Buy Signal or a Credit Red Flag?](https://medium.com/@mike_research/yields-in-the-ai-clouds-is-oracles-spread-widening-a-buy-signal-or-a-credit-red-flag-analysis-8fd54333d120)
- [Barchart: Oracle Q3 2026 Earnings — What to Expect](https://www.barchart.com/story/news/37198382/oracle-s-q3-2026-earnings-what-to-expect)
- [FI-DESK: Oracle balances debt issuance with equity reflecting investor caution](https://www.fi-desk.com/oracle-balances-debt-issuance-with-equity-reflecting-investor-caution/)
- [StockAnalysis: Oracle ORCL Forecast & Analyst Price Targets](https://stockanalysis.com/stocks/orcl/forecast/)
- [MarketBeat: Oracle ORCL Stock Forecast and Price Target 2026](https://www.marketbeat.com/stocks/NYSE/ORCL/forecast/)
