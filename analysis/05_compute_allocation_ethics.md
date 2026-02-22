# 05 — Compute Allocation: Is This the Best Use of the Hardware?

## The Resource Opportunity Cost Question

Every H100 GPU running inference for a chatbot is a GPU not running:
- Climate simulations (CMIP7 models, hurricane path prediction)
- Drug discovery (protein folding, molecular dynamics)
- Materials science (battery chemistry, superconductors)
- Medical imaging (cancer detection at population scale)
- Agricultural optimisation (food security modelling)

This is not a purely hypothetical concern. It reflects a real and growing debate about whether
the global allocation of compute resources — increasingly concentrated in commercial AI data
centres — represents an optimal use of humanity's most constrained technological resource.

---

## The Environmental Paradox of AI

AI occupies a deeply contradictory role in the climate and health debate:

**As a contributor to environmental harm:**
- AI training and inference consumes enormous amounts of energy linked to carbon emissions
- Water usage for cooling depletes local aquifers in drought-prone regions
- The manufacturing of AI chips requires rare materials with significant environmental footprints
- Data centres' electricity consumption projected to rise from 5% to 12% of US total by 2030

**As a potential tool for environmental benefit:**
- AI-enhanced climate models offer regional accuracy improvements over traditional GCMs
- AI-driven materials discovery could accelerate development of better batteries and solar cells
- AI optimisation can improve grid efficiency and reduce overall energy waste
- Drug discovery AI (AlphaFold, etc.) has already identified proteins relevant to disease treatment

The Lancet Global Health (2025) noted:
> *"AI technologies exacerbate climate change due to their intensive use of natural resources
> and energy linked to training and deployment, which is particularly concerning in global health
> given the explicit emphasis on improving health and advancing equity."*

---

## The Equity Dimension

AI-based models — including climate models — perform better in data-rich regions. Vulnerable
regions (Sub-Saharan Africa, South and Southeast Asia, Pacific Island nations) often receive
less accurate outputs precisely because training data from those regions is sparse.

The compute allocation goes primarily to:
- Commercial AI products sold to wealthy consumers and enterprises
- The development of products by companies domiciled in rich countries

The communities bearing the negative externalities (electricity price increases, water stress,
grid instability) are often not the primary beneficiaries of the AI services produced.

---

## Healthcare AI: A Microcosm

In medical AI, the ethical debate around deployment strategy mirrors the broader compute
allocation question:

- **"Selective deployment"**: limit AI tools to populations/use cases where they're proven
  to work, reducing risk of harm from unreliable outputs
- **"Equitable deployment"**: deploy broadly to achieve performance parity across demographic
  groups, even if early-stage performance is uneven

The debate also surfaces questions of who controls medical AI training data, who benefits
from its outputs, and who bears the risk when models perform poorly on underrepresented groups.

---

## The "Better Use" Argument in Policy Debate

Environmental groups, academics, and some technologists have explicitly argued that the compute
currently being consumed by commercial AI — particularly chatbots, image generators, and
code autocomplete tools — represents a poor allocation of scarce resources when compared to:

1. **Scientific compute** (climate, materials, biology) — where a single compute-intensive
   simulation can unlock breakthroughs benefiting billions of people
2. **Medical imaging at scale** — AI-powered early cancer detection programmes globally
   undersupplied with compute
3. **Food systems** — AI modelling of crop yields, pest patterns, soil health to support
   food security for 8 billion people

The counterargument from industry: there is no zero-sum constraint on GPU manufacturing —
building more data centres doesn't reduce the GPUs available for scientific compute. Nvidia
sells to all buyers. However, the constraint is real in practice: energy, water, skilled
labour, and critical manufacturing capacity (TSMC, etc.) are finite.

---

## What Would "Better Use" Actually Look Like?

This is where the debate becomes genuinely difficult. The question is not merely moral but
structural:

- Scientific computing often uses **different hardware** (traditional HPC clusters, A100s
  for research rather than H100/H200 commercial inference clusters)
- Government and university research compute budgets are a tiny fraction of hyperscaler spend
  — reallocating commercial data centre capacity to science isn't straightforward
- Open-weights models (LLaMA, Mistral, DeepSeek) are already enabling scientific users to
  access frontier AI capabilities without hyperscaler infrastructure

A practical proposal gaining traction: **compute quotas or tiered access** to power/water
for data centres, with preferential licensing for facilities demonstrating public-benefit
compute usage above some threshold.

---

## Sources
- [Lancet Global Health: Climate change and health — the next challenge of ethical AI](https://www.thelancet.com/journals/langlo/article/PIIS2214-109X(25)00124-X/fulltext)
- [PubMed: Climate change and health — the next challenge of ethical AI](https://pubmed.ncbi.nlm.nih.gov/40580996/)
- [Springer Nature: AI and climate — ethical sustainability framework](https://link.springer.com/article/10.1007/s00146-025-02615-0)
- [MDPI: Next-Generation Climate Modeling with AI](https://www.mdpi.com/3042-5743/34/1/15)
- [PMC: Ethical debates amidst flawed healthcare AI metrics](https://pmc.ncbi.nlm.nih.gov/articles/PMC11390731/)
- [Nature npj Digital Medicine: Ethical debates amidst flawed healthcare AI metrics](https://www.nature.com/articles/s41746-024-01242-1)
- [PMC: Shaping the Future of Healthcare — Ethical Clinical Challenges and Trustworthy AI](https://pmc.ncbi.nlm.nih.gov/articles/PMC11900311/)
- [EthicalGEO: The Cloud is Drying our Rivers — Water Usage of AI Data Centres](https://ethicalgeo.org/the-cloud-is-drying-our-rivers-water-usage-of-ai-data-centers/)
- [MSCI: When AI Meets Water Scarcity — Data Centres in a Thirsty World](https://www.msci.com/research-and-insights/blog-post/when-ai-meets-water-scarcity-data-centers-in-a-thirsty-world)
- [TechPolicy Press: Policymakers Must Prepare Now for When the AI Bubble Bursts](https://www.techpolicy.press/policymakers-have-to-prepare-now-for-when-the-ai-bubble-bursts/)
