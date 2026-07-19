---
schema: paper-monitor/paper/v1
paper_id: 6382
record_type: PAPER
bibliography:
  title: '[PDF] Evaluating Control Protocols for Untrusted AI Agents'
  authors: Kutasov, Jon, Loughridge, Chloe, Sun, Yuqi, Sleight, Henry, Shlegeris, Buck, Tracy, Tyler, Benton, Joe
  abstract: As AI systems become more capable and widely deployed as agents, ensuring their safe operation becomes critical.
    AI control offers one approach to mitigating the risk from untrusted AI agents by monitoring their actions and intervening
    or auditing when necessary. Evaluating the safety of these protocols requires understanding both their effectiveness against
    current attacks and their robustness to adaptive adversaries. In this work, we systematically evaluate a range of control
    protocols in SHADE-Arena, a dataset of diverse agentic environments. First, we evaluate blue team protocols, including
    deferral to trusted models, resampling, and deferring on critical actions, against a default attack policy. We find that
    resampling for incrimination and deferring on critical actions perform best, increasing safety from 50% to 96%. We then
    iterate on red team strategies against these protocols and find that attack policies with additional affordances, such
    as knowledge of when resampling occurs or the ability to simulate monitors, can substantially improve attack success rates
    against our resampling strategy, decreasing safety to 17%. However, deferring on critical actions is highly robust to
    even our strongest red team strategies, demonstrating the importance of denying attack policies access to protocol internals.
  publisher: arXiv.org.
  published_on: '2025-11-04'
  doi: 10.48550/arxiv.2511.02997
links:
  source: https://openalex.org/W7104293242
  open_access: https://doi.org/10.48550/arxiv.2511.02997
source:
  logical_feed_id: 26
  logical_feed_name: SLR UPDATE
  feed_id: 34
  feed_name: Miage Scholar Import 2026-05-13:17:44:27 RSS
  discovered_at: '2026-06-12T11:34:15.006316Z'
workflow:
  state:
    id: NEW
    label: New
    prisma_bucket: null
  tags: [
    ]
  eligibility:
    exclusion: null
    inclusion:
      criteria: [
        ]
files:
  pdf:
    available: false
    name: null
    original_name: null
---

