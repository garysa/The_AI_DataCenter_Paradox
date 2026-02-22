# 02 — Hardware Obsolescence: The Ticking Clock

## Nvidia's Accelerating Release Cadence

Nvidia has deliberately compressed its product release cycle, creating a relentless obsolescence
pressure on anyone who has bought prior-generation hardware:

| Generation | Launch | Key Chip |
|-----------|--------|----------|
| Hopper | 2022 | H100 |
| Hopper Refresh | 2024 | H200 |
| Blackwell | 2024 | B100 / B200 / GB200 |
| Rubin | 2026 | R100 |
| Rubin Ultra | 2027 | — |

**Blackwell offers up to 25× better energy efficiency** than Hopper for specific AI inference
workloads. This is not a marginal upgrade — it is a step change that makes H100 clusters
economically uncompetitive for inference at scale within 2–3 years of their purchase.

---

## The Accounting Fiction vs. Reality

There is a deliberate and revealing mismatch between how companies account for GPU lifespan
and how long the hardware is actually competitive:

| Measure | Timeframe |
|---------|-----------|
| Accounting depreciation (industry standard) | **5–6 years** |
| Actual frontier competitive lifespan | **1–3 years** |
| Standard GPU generation cycle | **18–24 months** |
| Secondary market value at year 3 (H100) | ~**45% of new price** |

Companies use 5–6 year depreciation schedules **because shorter schedules would make the
economics look catastrophic on paper**. It is a legitimate accounting choice, but it
misrepresents the operational reality.

The CNBC headline captures it precisely:
> *"The chips at the heart of the AI infrastructure buildout have a useful lifespan of one to
> three years due to rapid technological obsolescence and physical wear, but companies depreciate
> them over five to six years."*

---

## The Price Collapse of the H100

The H100's rental price trajectory is a case study in GPU commodity collapse:

| Period | H100 Cloud Rental Price |
|--------|------------------------|
| 2023 peak | ~$8 / hr |
| Late 2024 | ~$5–6 / hr |
| Mid 2025 (AWS cuts 30%) | ~$3.50 / hr |
| Late 2025 | **$2.85–$3.50 / hr** (mainstream); $1.80 (spot/secondary) |

**Total price decline: approximately 64–75% from peak.**

Key drivers:
- AWS triggered a market reset by cutting prices ~30% in June 2025
- Over 300 new cloud providers entered the H100 market in 2025
- Aggressive price wars among smaller vendors (RunPod, Vast.ai, etc.)
- B200 availability beginning to create forward-looking price pressure on H100

**A secondary market H100 batch from 2022 was recently available and immediately booked at
95% of new-H100 price** — illustrating that demand for secondary-tier hardware remains, but
at discounted economics. An H100 in its third year resells for approximately **45% of a new H100**.

---

## The Cooling Trap

Hardware obsolescence is not just about compute performance. The physical infrastructure required
for newer, denser AI chips is fundamentally different:

- **H100 era**: air cooling, standard rack density
- **B200/GB200 era**: liquid cooling, direct-to-chip cooling, higher power density
- **Retrofitting cost**: 7–10% more expensive than building new
- **Result**: Many 2022–2024 vintage data centres **cannot physically accommodate** next-gen
  hardware without prohibitively expensive renovation

This means the building itself — designed for one class of hardware — becomes obsolete alongside
the hardware it was built to house. The civil works that were supposed to last 30 years may be
functionally stranded in 5–8 years.

---

## Secondary Market Resilience: A Partial Mitigant

Not all is lost. Older GPUs have a secondary economic life:

- H100 clusters can be **cascaded down** from frontier training to inference workloads
- A three-year-old H100 may not be the best choice for training the next GPT-6, but it
  delivers massive speedups vs CPUs for countless production inference tasks
- Secondary providers (RunPod, CoreWeave mid-tier, etc.) actively market older hardware
  at lower price points

This cascading deployment model extends the economic life of the hardware, but it compresses
margins because secondary-market pricing reflects the age of the asset.

---

## The DeepSeek Effect: Efficiency as Demand Catalyst

In January 2025, DeepSeek released a highly efficient open-source AI model that achieved
comparable performance with significantly fewer high-end servers and lower energy consumption.
This triggered a brief panic in AI infrastructure stocks.

**The paradox:** increased efficiency doesn't reduce demand — it expands it.

When AI becomes cheaper and more accessible, more users adopt it, more use cases become viable,
and aggregate compute demand **rises** even as per-unit compute cost falls. This is a well-known
economic phenomenon (Jevons Paradox / Rebound Effect).

As a result, DeepSeek was ultimately deemed **a net positive for data centre developers** —
more users, more workloads, more demand for compute — even if the efficiency gains temporarily
created overcapacity fears.

---

## Sources
- [CNBC: The question everyone in AI is asking — how long before a GPU depreciates?](https://www.cnbc.com/2025/11/14/ai-gpu-depreciation-coreweave-nvidia-michael-burry.html)
- [WhiteFiber: Understanding GPU Lifecycle](https://www.whitefiber.com/blog/understanding-gpu-lifecycle)
- [CITP Princeton: Lifespan of AI Chips — the $300B question](https://blog.citp.princeton.edu/2025/10/15/lifespan-of-ai-chips-the-300-billion-question/)
- [Stanley Laman: Why GPU Useful Life is the Most Misunderstood Variable](https://www.stanleylaman.com/signals-and-noise/gpus-how-long-do-they-really-last)
- [Introl: GPU Cloud Prices Collapse — H100 Rental Drops 64%](https://introl.com/blog/gpu-cloud-price-collapse-h100-market-december-2025)
- [SiliconData: H100 Rental Price Over Time 2023–2025](https://www.silicondata.com/blog/h100-rental-price-over-time)
- [MBI Deep Dives: Why I don't worry as much about big tech's depreciation schedule](https://www.mbi-deepdives.com/why-i-dont-worry-as-much-about-big-techs-depreciation-schedule/)
- [Introl: Asset Lifecycle Management for GPUs](https://introl.com/blog/asset-lifecycle-management-gpus-procurement-decommissioning)
- [Utility Dive: DeepSeek called a net positive for data centers](https://www.utilitydive.com/news/deepseek-called-a-net-positive-for-data-centers-despite-overcapacity-worrie/740635/)
- [Data Center Frontier: Why DeepSeek is Great for AI and HPC](https://www.datacenterfrontier.com/machine-learning/article/55264838/why-deepseek-is-great-for-ai-and-hpc-and-no-big-deal-for-data-centers)
